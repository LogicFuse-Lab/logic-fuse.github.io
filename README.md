# logic-fuse ⚡

Personal blog powered by [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, ready for deployment to [GitHub Pages](https://pages.github.com/).

---

## 🚀 Quick Start (Localhost Development)

To start the local development server with live reload:

```bash
hugo server -D
```

Open your browser at **[http://localhost:1313/](http://localhost:1313/)**.

> `-D` (or `--buildDrafts`) ensures any posts marked as `draft: true` are rendered in your local preview.

---

## 📝 Creating New Posts

Run the following command to generate a new post from the archetype template:

```bash
hugo new content posts/my-new-post.md
```

This creates a file in `content/posts/my-new-post.md`. Open it, write your content in Markdown, and set `draft: false` when you're ready to publish!

---

## 🌐 Deploying to GitHub Pages

1. **Create a new repository** on GitHub named `logic-fuse` (or `blueforge.github.io` if user-level site).
2. **Link your local repository to GitHub and push**:
   ```bash
   git remote add origin https://github.com/<YOUR_USERNAME>/logic-fuse.git
   git push -u origin main
   ```
3. In your GitHub repository:
   - Go to **Settings** > **Pages**
   - Under **Build and deployment** > **Source**, select **GitHub Actions**
4. Whenever you push to `main`, GitHub Actions will automatically build and publish your blog!
