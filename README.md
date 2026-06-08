# ImpressIV — 3D Model Viewer

A dead-simple web viewer for `.glb` / `.gltf` models exported from Blender.
No installing, no terminal, no setup. Just open it and drag your file in.

---

## 🟢 The easy way — use the website (recommended)

Open this link in any browser (Chrome, Edge, Safari):

> **https://adhamaltony.github.io/blender-test-viewer/**
>
> _(this link goes live after GitHub Pages is turned on — see the bottom of this file)_

Then:

1. **Drag your `.glb` file** from your computer and drop it anywhere on the page.
2. That's it — your model appears. 🎉

You can also click **📂 Open a model** in the top-right corner to pick a file.

**Tip:** bookmark the link so you can come back any time.

---

## 🖱 How to move around

| Action | Mouse |
|--------|-------|
| Rotate / orbit | **Left-click + drag** |
| Pan / slide | **Right-click + drag** |
| Zoom in/out | **Scroll wheel** |
| Re-center the view | Click **↺ Reset view** |
| See the mesh / edges | Click **▢ Wireframe** |
| Light/dark background | Click **◐ Background** |

The little colored axes in the bottom-right corner show which way is X / Y / Z —
click them to snap to front/top/side views.

---

## 🎛 Tuning the look (Settings panel, top-right)

Click the **⚙ Settings** panel in the top-right corner to fine-tune everything live.
Nothing here changes your model file — it only changes how it's shown, and your
choices are remembered the next time you open the page.

- **Model & View** — open a model, reset the camera, turn auto-rotate on/off and set its speed.
- **Ambient Light** — turn it off, or drag intensity/colour.
- **Sun / Directional Light** — turn it off, change intensity, colour, and which direction it shines from.
- **Environment Light** — turn reflections on/off and set their strength.
- **Scene** — background (Dark / Light / Custom colour / Transparent), show or hide the grid, wireframe mode.
- **Render Quality** — tone mapping style (ACES, AgX, Neutral, …) and exposure (overall brightness).
- **⟲ Reset all settings** — puts everything back to default.

---

## 💻 The offline way — no internet needed

If you'd rather run it from your own computer:

1. Click the green **Code** button on the GitHub page → **Download ZIP**.
2. Unzip it.
3. Double-click **`index.html`**.

> ⚠️ Some browsers block the bundled demo model when opened this way, but
> **drag-and-drop of your own files always works**. The online link above
> has no such limitation, so it's the easier option.

---

## 📦 What's in here

- `index.html` — the whole viewer (one file, nothing else needed).
- `models/` — a sample model so the page isn't empty on first open.

---

## ⚙️ For whoever sets this up (one-time, technical)

Turn on the free hosted website:

1. Go to the repo on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment → Source**, pick **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)** → **Save**.
4. Wait ~1 minute. The site appears at the link at the top of this file.

Then add the designer as a collaborator:
**Settings → Collaborators → Add people**.
