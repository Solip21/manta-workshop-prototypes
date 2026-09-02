# Content Ownership (콘텐츠 소장감 강화)

Clickable prototype for the "콘텐츠 소장감 강화" spec — the 최애작(Favorite Series) flow, 소장률 progress bar, and Fandom Board badges.

Related Notion doc: [상세 스펙](https://app.notion.com/p/3c22d79d7707806ab82dfa13615f5495)
Figma reference: Task 솔잎, `소장감` page

## What's covered (v1)

- **Series Home** — simplified (cover, title, function row, Fandom Board entry, a few episode rows). Tapping **+** opens the favorite prompt.
- **Favorite prompt** — "Make this a favorite?" overlay, `Add to Favorite Series` → Add Note screen, `Not now` dismisses.
- **Add to My Favorite Series** — optional note, Save toasts and returns to Series Home.
- **My Series** — tab row (Saved / Current reads / Favorite / Unlocked / Notification) and 소장률 progress bars per owned series, matching the Figma spec (full-width bar, title/type grouped separately from ratio+bar).
- **Fandom Board** — post feed with the `Favorite` (Purple) and `Top Reader` (Pink) badges next to nicknames.

## Not yet covered

- Fandom Board Write Free Post / Create Poll / Tap Write
- Life Series Archive (Default / Card Detail)
- The `Active` (Mint) activity badge — no post/highlight/poll action wired to award it yet
- Real cover art (uses gradient placeholders instead of downloaded Figma assets, to keep this pass lightweight)

## Stack

Same self-contained single-file pattern as the other folders in this repo (device chrome, `push`/`back` router, Poppins font, Manta dark tokens) — no build step, open `index.html` directly or serve statically.
