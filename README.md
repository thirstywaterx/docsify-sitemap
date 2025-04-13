# Docsify Sitemap Generator

[![MIT License](https://img.shields.io/badge/license-MIT-brightgreen)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/thirstywaterx/docsify-sitemap?style=social)](https://github.com/your-username/your-repo-name/stargazers)
[![Demo](https://img.shields.io/badge/demo-online-blue)](https://your-demo-url.com)

Generate a `sitemap.xml` file for your GitHub Pages or Docsify-powered site by extracting all `.md` files from your public repository — great for SEO and indexing!

---

## Features

- **Zero install:** No dependencies, fully client-side  
- **GitHub API powered:** Pulls `.md` files from any public GitHub repo  
- **Directory filtering:** Limit sitemap generation to a subfolder (e.g., `docs/`)  
- **SEO friendly:** Outputs sitemap XML compatible with search engine crawlers  
- **One-click download:** Generate and save your `sitemap.xml` in seconds  
- **Docsify-friendly:** Converts `.md` paths to clean URLs  

---

## Usage

1. Open the generator [live site](https://your-demo-url.com)  
2. Fill in your GitHub repo info:
   - Base Domain (optional): `https://username.github.io/repo/`
   - Owner: your GitHub username
   - Repository Name: your repo name
   - Branch: e.g., `main`
   - Directory Filter: (optional, e.g., `docs/`)
3. Click **Generate Sitemap**
4. Review the generated XML
5. Click **Download sitemap.xml**

You can then upload this file to your GitHub Pages root to improve SEO.

---

## Example

**Sample repo structure:**
```
docs/
├── index.md
├── guide/
│   └── intro.md
```

**Resulting sitemap:**
```xml
<url>
  <loc>https://username.github.io/repo/</loc>
  <priority>1.0</priority>
</url>
<url>
  <loc>https://username.github.io/repo/docs/guide/intro</loc>
</url>
```

---

## Screenshot

![Screenshot](https://pic1.imgdb.cn/item/67fb462f88c538a9b5ccbf1b.png)

---

## Tech Stack

- HTML + CSS + Vanilla JS
- GitHub REST API

---

## License

MIT

---

## Contributions

PRs and feedback welcome! If you like this tool, give it a star!