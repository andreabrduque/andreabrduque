# Adding a new blog post

1. Create a new file in `_posts/` named `YYYY-MM-DD-your-title.md` (the date and
   filename format are required by Jekyll).
2. Add front matter at the top, then your content in Markdown below it:

   ```markdown
   ---
   layout: post
   title: "Your Title"
   date: YYYY-MM-DD 00:00:00 +0000
   ---

   Your post content here.
   ```

3. Preview locally:

   ```bash
   bundle exec jekyll serve
   ```

   Open `http://localhost:4000/andreabrduque/` in your browser.

4. Commit and push to `main` — GitHub Pages rebuilds the site automatically.
