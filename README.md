# Stats Final — Drill

Flashcard drilling for 308 practice questions from lectures 1–15 (lecture notes, homework,
practice midterm, midterm).

**Live: https://reyr13.github.io/stats-drill/**

Grade yourself on each card. *Right* clears it, *half right* drops it back ~6 cards later,
*wrong* drops it back ~3 later — so anything you miss keeps coming back until you clear it.

Progress is saved in your browser automatically.

---

## Sync across devices

Progress can sync between your laptop and phone through a private GitHub Gist. Setup is once
per device.

1. Go to **github.com/settings/tokens** → **Tokens (classic)** → *Generate new token (classic)*
2. Tick the single **`gist`** checkbox. Nothing else — it doesn't need repo access.
3. Expiration: 90 days is plenty.
4. Generate, copy the token. It starts with `ghp_`.
5. Open the app → **Progress** → **Connect sync** → paste the token → **Connect**.

Repeat steps 4–5 on your other device with the same token. The app finds the gist by itself.

> **It has to be a classic token.** Fine-grained tokens are rejected by GitHub's gists API —
> it only accepts the classic `gist` scope. A fine-grained one fails with "Bad credentials"
> no matter which permissions you tick.

The token is stored only in that device's `localStorage`. It is never committed to this repo —
and it must not be, since this repo is public and GitHub revokes tokens it finds in public code.
If a token ever leaks, delete it at github.com/settings/tokens; it can only touch your gists.

**Download backup file** on the Progress screen still works and doesn't need any of this. It's
the safety net if sync ever misbehaves.
