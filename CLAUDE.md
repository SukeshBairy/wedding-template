# Wedding invitation site

- This is the wedding invite site for Sukesh & Aishwarya, 25 Feb 2027, Sambhrama, Bengaluru.
- All event details (times, events, schedule, venue) live in the `WEDDING` config block
  inside the `<script>` at the bottom of `index.html`. Edit there first.
- Keep both English and Kannada text in sync. Every visible string has an EN and a KN version.
- Keep the page a single self-contained `index.html` (images are inlined as base64; don't remove them).
- After every change: open/check the HTML is valid, then `git add -A`,
  commit with a short clear message, and `git push`. Vercel deploys automatically.
- After pushing, tell me what changed and remind me the live URL updates in about a minute.

## Deployment
- GitHub repo: `sukesh-weds-aishwarya` (public), branch `main`.
- Vercel project: `sukesh-weds-aishwarya`, no build step, static output from the root folder.
  Every push to `main` deploys automatically.
