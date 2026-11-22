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
- GitHub repo: https://github.com/SukeshBairy/wedding-template (branch `main`).
- Live site: https://sukesh-weds-aishwarya.vercel.app/ (Vercel project `sukesh-weds-aishwarya`,
  no build step, static output from the root folder). Every push to `main` deploys automatically.
- The "Copy Invite Link" button copies `WEDDING.siteUrl`; update it if the domain changes.
- Claude's shell can't sign in to GitHub. After Claude commits, the user pushes from
  VS Code (Source Control → Sync Changes).
