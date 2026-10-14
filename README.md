# Foundational Language Skills Screener

Sentence comprehension task by Claire Dolly. Students hear 20 sentences about plants and tap the picture (of four) that matches each one. The examiner gets a scored report at the end.

## Publish on GitHub Pages

1. Upload everything in this folder to the repository (keep the `images` and `audio` folders).
2. In the repository, go to **Settings > Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Editing the task

All content is near the top of the `<script>` in `index.html`:

| What | Where |
|---|---|
| Sentences and answer key | `ITEMS` list. `key` is the correct picture: A top-left, B top-right, C bottom-left, D bottom-right. Remove `check` once a key is confirmed. |
| Plant background video | `BG_VIDEO` |
| Student directions video | `DIRECTIONS_VIDEO` (set to a YouTube link) |
| Overview video on the front page | `INTRO_VIDEO` (set to a YouTube link) |
| Recorded sentences | Add `item01.mp3` ... `item20.mp3` to `audio/` (see `audio/README.md`) |

YouTube links play right on the page, with a backup link to open them on YouTube.

## Privacy

Nothing is sent anywhere. Student names and responses stay in the browser tab and are cleared when the page is closed or reloaded. Use **Copy results for a spreadsheet** on the report screen to save them.

Note that a public repository makes the answer key readable to anyone who opens the page source.
