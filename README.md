# 🌟 logchange Organization Configuration

This repository contains the **default community health files** for the **logchange** organization. These files help standardize and streamline project management across all repositories within the organization. 

---

## 📋 What's Included?

- **Issue Templates**: Predefined formats for reporting bugs, requesting features, and more. 🐛✨  
- **Pull Request Templates**: Guidelines to ensure clear and consistent contributions. ✅  
- **Code of Conduct**: Our expectations for a welcoming and inclusive community. 🤝  
- **Contributing Guidelines**: Instructions to help contributors get started quickly. 🛠️  
- **Organization Profile**: A central README to provide an overview of logchange's mission and projects. 📜  

---

## 🔧 How It Works

- These files are automatically inherited by all repositories in the **logchange** organization.  
- Individual repositories can override these files with custom versions if needed.  

---

## 🤝 Contributing

Contributions to improve these defaults are always welcome! Simply open an issue or submit a pull request with your suggestions.

---

## ❤️ Thank You

Thank you for being part of the **logchange** community! Together, we can build better tools and foster a collaborative environment. 🎉  


---

## 📚 Organization Docs Site

This repository now hosts the Logchange documentation site built with MkDocs (Material theme).

- Live site (after first deploy): https://logchange.github.io/.github/
- Source docs: ./docs
- Config: ./mkdocs.yml

### Local preview

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

### Contributing

- Use the pencil icon on any page to edit directly on GitHub (it links to the file under ./docs).
- See docs/Contributing: https://logchange.github.io/.github/contributing/

### Structure

- Organization overview: docs/index.md
- Tools: docs/tools/{logchange|hofund|valhalla}/
  - getting-started.md, usage.md, faq.md, reference.md

### Deployment

Publishing is automated with GitHub Actions on push to main. The workflow builds MkDocs, uploads the artifact, and deploys to GitHub Pages.
