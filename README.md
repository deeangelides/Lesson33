# Lesson 33 — Banksy: The Artist Nobody Knows 🖌️

Playful-Detective teaching pack for a one-hour online English lesson (Grade 4/5): an information text about Banksy, then **types of adjectives** (descriptive, quantity, demonstrative, possessive, proper) and a **types of adverbs review**.

**Open `index.html`**, or publish this folder with GitHub Pages and it works as a website.

| File | What it is |
| --- | --- |
| `index.html` | Home page linking the lesson and all three games |
| `lesson-33-banksy.html` | The 20-slide lesson (arrow keys, thumbnail rail, ⛶ Present, print to PDF) |
| `paint-catch.html` | Catch spray cans, heart balloons and stars; dodge rain clouds and sponges. 3 lives |
| `whack-a-rat.html` | 60-second whack-a-mole with street-art rats. Avoid the grey paint blob |
| `alley-maze.html` | Random mazes that grow every level. Tap a direction or use the arrows |

## Publishing on GitHub Pages

1. Upload **everything in this folder**, including the sub-folders and the `.nojekyll` file, to the root of a repository.
2. Settings → Pages → Source: *Deploy from a branch* → branch `main`, folder `/ (root)` → Save.
3. After a minute, open `https://<your-username>.github.io/<repo-name>/`.

Everything is static and uses **relative paths only**. There's no build step and no server code.

**If something won't open:** GitHub is case-sensitive, so keep every file and folder name exactly as it is (all lowercase, no spaces). Make sure the `banksy/`, `stickers/`, `fonts/` and `slides/` folders were uploaded too.

## Folders

- `banksy/` — lesson pictures
- `stickers/` — cat illustrations
- `fonts/` — Bowlby One SC + Quicksand, self-hosted
- `slides/deck-stage.js` — the slide-deck engine
- `*.css` — Playful Detective tokens and lesson skins (`lesson33.css` is this lesson's theme)
