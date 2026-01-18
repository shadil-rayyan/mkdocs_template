# MkDocs Material Template

A high-performance, feature-rich template for MkDocs using the Material theme.

## ✨ Features

- **Standard Plugins**: `minify`, `search`, `git-revision-date-localized`, `git-authors`, `tags`.
- **Advanced Markdown**: Admonitions, Tabs, Mermaid diagrams, Math (Latex), Footnotes, Tasklists, Emojis, and more.
- **Premium UX**: Instant loading, sticky navigation, "Back to Top" button, social links, and code copy button.
- **CI/CD Ready**: GitHub Actions workflow included for automatic deployment to GitHub Pages.
- **Reproducible**: `requirements.txt` included for easy setup.

## 🚀 Quick Start

1. **Clone/Use this template**.
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Start the dev server**:
   ```bash
   mkdocs serve
   ```
4. **Edit `mkdocs.yml`**: Update the `site_name`, `repo_url`, and other metadata.

## 🌐 Deployment

This template is set up to deploy automatically via GitHub Actions.

1. **Push to `main`**: Any push to the `main` branch triggers the deployment workflow.
2. **Configure GitHub Pages**:
   - Go to your repository **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, select **"Deploy from a branch"**.
   - Select the **`gh-pages`** branch (created after the first successful action run) and the **`/(root)`** folder.
   - Click **Save**.

## 📁 Structure

- `docs/`: Markdown files and documentation source.
- `mkdocs.yml`: Configuration file.
- `.github/workflows/ci.yml`: GitHub Actions for automated deployment.
- `requirements.txt`: Python dependencies.
- `.gitignore`: Standard git exclusions.

## 📄 License

This template is open-source and free to use.
