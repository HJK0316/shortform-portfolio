# Portfolio maintenance policy

This repository hosts the **canonical, public** portfolio:
https://hjk0316.github.io/shortform-portfolio/

## Source of truth

- Use `HJK0316/shortform-portfolio`, default branch `main`, root `index.html`.
- The previously distributed Notion portfolio is retained **only as an archive for old links**. Never use Notion for new video listings or update its project catalog.
- Do not create another portfolio repository or change existing non-portfolio GitHub repositories.
- Do not automatically add synchronization services, workflows, scheduled tasks, databases, or third-party dependencies unless specifically requested.

## Adding a video

1. Read the latest `index.html` and GitHub blob SHA before editing.
2. Verify that the video is publicly available; check the canonical video ID and compare against all existing links/cards. Avoid duplicate entries.
3. Add the new work to the correct existing gallery: `#celebrity` for celebrity/K-pop/entertainment; `#shopping` for shopping/product shorts.
4. Match the original static site style, typography, thumbnail aspect ratio, animations, Korean editorial voice, and responsive layout. Use actual video thumbnail URLs and verified titles/dates. Do not invent performance claims.
5. Preserve all existing cards and their YouTube/Google Drive URLs. Do not add the previously removed third-party copyright disclaimer.
6. Commit the minimal necessary edit to `main`; verify the GitHub Pages deployment and that the public HTML contains the new unique video ID. Check the new thumbnail, playback link, and mobile layout before claiming success.
7. If authorization or deployment fails, report the failure; never fall back to writing Notion.

The public site is **the portfolio to share with clients**. The GitHub repository is its editable source; the old Notion page is not the current portfolio.
