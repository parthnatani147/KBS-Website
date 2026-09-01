# Khandelwal Bath Studio — website

A simple, single-page static site: logo, one photo, a line about the business, and contact info.

## Files

- `index.html` — the page content
- `style.css` — all styling
- `logo.svg` — placeholder logo (swap for your real one)
- `photo.jpg` — **not included** — add your own photo with this exact filename and it will appear automatically (until then, the panel shows a plain placeholder pattern)

## Before you publish, edit these

Open `index.html` in any text editor and update:

1. **Tagline** — the sentence under the business name.
2. **Contact bar** at the bottom — replace:
   - `Shop address, Jaipur, Rajasthan` with your real address
   - `+91 00000 00000` with your real phone number (also update the `tel:` link right next to it)
   - `hello@khandelwalbathstudio.com` with your real email (also update the `mailto:` link)

Add your photo:
- Rename any photo of your showroom/work to exactly `photo.jpg` and drop it into this folder, replacing nothing (there's no existing photo.jpg — you're just adding it).

Add your real logo (optional):
- Replace `logo.svg` with your own logo file. If it's a `.png` instead, open `index.html` and change `logo.svg` to `logo.png` (there's one place it's mentioned).

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `khandelwalbathstudio`).
2. On the repo's main page, click **Add file → Upload files**.
3. Drag in `index.html`, `style.css`, `logo.svg`, and your `photo.jpg`, then click **Commit changes**.
4. Go to **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**.
6. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
7. Wait a minute or two — GitHub will give you a live URL, usually `https://<your-username>.github.io/khandelwalbathstudio/`.

That's it — no build step, no dependencies to install.
