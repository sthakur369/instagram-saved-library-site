# Publishing a new blog post

1. Open this repository:
   `sthakur369/instagram-saved-library-site`

2. Open the `_posts/` folder.

3. Create a new Markdown file using this format:
   `YYYY-MM-DD-your-post-title.md`

   Example:
   `2026-09-01-how-to-back-up-instagram-saved-posts.md`

4. Put the front matter at the top:
   ```yaml
   ---
   layout: post
   title: "Your article title"
   description: "A short description of the article."
   categories: [Instagram]
   tags: [instagram, saved-posts]
   author: Shubham Thakur
   ---
   ```

5. Write the article below the second `---` using normal Markdown.

6. Commit the new file to the `main` branch and push it.

7. GitHub Pages will build the site automatically.

8. Wait for the Pages deployment to finish under **Actions**.

9. The article will appear automatically in:
   `/instagram-saved-library-site/blog/`

10. You do not need to edit `blog/index.html` to add the article.

### Filename rule

Use lowercase words separated by hyphens:

`2026-09-01-instagram-saved-posts-export.md`

Avoid spaces and special characters.

### Publishing checklist

Before pushing:

- [ ] Title is clear and matches what someone would search
- [ ] Description is one short, useful sentence
- [ ] Main keyword appears naturally in the title and opening
- [ ] Headings are simple
- [ ] Links to official Instagram/Meta help are included when giving current UI steps
- [ ] At least one subtle link points to the main app repository
- [ ] No keyword stuffing
- [ ] The article is genuinely useful even if the reader never uses the app
