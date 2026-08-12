# V.Grow — Site Files

## 1. Upload to GitHub
1. Create a new repository on GitHub named `your-username.github.io` (this exact format gives you a free live URL).
2. Upload every file/folder here into that repository, keeping the same folder structure.
3. Go to repo Settings → Pages → set Source to "Deploy from branch" → branch `main` / folder `/ (root)`.
4. Your site goes live at `https://your-username.github.io` within a few minutes.

## 2. Add a new article (do this anytime)
1. Go to the `_posts` folder in your repo.
2. Click "Add file" → "Create new file."
3. Name it exactly like this: `2026-08-20-my-article-title.md` (date must come first, YYYY-MM-DD).
4. Paste this at the very top, then write your article in plain text/Markdown below it:
   ```
   ---
   title: "Your Article Title Here"
   ---
   ```
5. Commit the file. It appears on your homepage automatically within about a minute.

## 3. Add a product (affiliate link)
1. Upload your product photo to `assets/images/products/`.
2. Open `_data/products.yml` and add a new block, copying the existing format exactly:
   ```yaml
   - name: "Product Name"
     description: "Short honest description."
     image: "/assets/images/products/yourphoto.jpg"
     link: "https://your-affiliate-link.com"
   ```
3. Commit the file. The product card appears on the Products page automatically.

## 4. Before applying to AdSense
- Update the email address in `about.html`, `footer.html`, and `privacy.html`.
- Rewrite `privacy.html` with your real details — it's a starting template, not legal advice.
- Publish at least 15–20 real articles first.
