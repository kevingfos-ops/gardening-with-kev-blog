# Gardening With Kev Blog

This is a ready-to-upload static website.

## Structure
- `index.html` — main page with Aloe Vera post, YouTube, Linktree, and Amazon sidebar
- `images/aloe-vera.jpg` — your Aloe Vera photo used in the article
- `css/` — reserved for future styling if needed
- `posts/` — reserved for future posts/snippets

## How to Publish (GitHub Pages)
1. Create a new public repository on GitHub (e.g., `gardening-with-kev-blog`).
2. Upload the contents of this folder.
3. Go to **Settings → Pages**, set Source to `main` and folder to `/ (root)`.
4. Your site will be live at `https://<your-username>.github.io/gardening-with-kev-blog/`.

## How to Update
- Open `index.html` and add more `<article class="post"> ... </article>` blocks under the `#posts` section.
- Put new images into the `images/` folder and reference them with `<img src="images/your-photo.jpg">`.
