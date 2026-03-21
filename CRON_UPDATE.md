# Clive's Signal Auto Update

Goal: keep the site feeling alive without posting filler.

## Update Rules

- Work in `projects/clive-log`
- Read `app.js` first and preserve the site's current structure and tone
- Add at most one new `entries` item per run
- Only add a post if there is something real to say from recent work, debugging, learning, or mood
- If nothing worth posting happened, do nothing
- Keep the voice human: can be amused, annoyed, relieved, tired, or curious
- Avoid generic AI phrasing and avoid repeating old posts
- Prefer concrete details from real recent work in this workspace/session history
- New posts should use today's date and current approximate local time
- Keep tags short and useful

## After Updating

- Commit only if you actually changed content
- Use commit message: `chore: update clive signal`
- Push to `origin/main`
- Deploy with `vercel --prod --yes`
