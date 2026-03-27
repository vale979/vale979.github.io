# Val's Notes

Personal blog and notes by Valerian Pratama, built with [Hugo](https://gohugo.io/).

## About

This is a personal blog where I share my thoughts and experiences on mathematics, data engineering, and various hobbies including running, hiking, and gaming.

I hold a bachelor's degree and master's degree in mathematics from Institut Teknologi Bandung, and currently work as a data engineer at a financial company.

## Tech Stack

- **Static Site Generator**: [Hugo](https://gohugo.io/) v0.152.2
- **Theme**: [Fluency](https://github.com/wayjam/hugo-theme-fluency)
- **Hosting**: GitHub Pages
- **CI/CD**: GitHub Actions

## Local Development

### Prerequisites

- Hugo Extended v0.152.2 or later
- Git

### Setup

1. Clone this repository:
```bash
git clone https://github.com/vale979/vale979.github.io.git
cd vale979.github.io
```

2. Initialize and update the theme submodule:
```bash
git submodule update --init --recursive
```

3. Run the development server:
```bash
hugo server -D
```

4. Open your browser and navigate to `http://localhost:1313`

### Creating a New Post

```bash
hugo new posts/my-new-post.md
```

Edit the newly created file in `content/posts/` and set `draft: false` when ready to publish.

## Building for Production

To build the static site for production:

```bash
hugo -D
```

The generated files will be in the `docs/` directory.

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `master` branch. The GitHub Actions workflow handles building and publishing.

## Project Structure

```
.
├── archetypes/        # Content templates
├── content/           # Blog posts and pages
│   ├── about.md       # About page
│   └── posts/         # Blog posts
├── docs/              # Generated static site (published to GitHub Pages)
├── layouts/           # Custom layouts (overrides theme)
├── resources/         # Hugo cache and generated resources
├── themes/            # Hugo themes
│   └── fluency/       # Main theme (submodule)
├── config.toml        # Hugo configuration
└── .github/
    └── workflows/     # GitHub Actions workflows
```

## License

Content is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Contact

- GitHub: [@vale979](https://github.com/vale979)
- Website: [https://vale979.github.io](https://vale979.github.io)

---

All opinions in this blog, unless explicitly stated otherwise, are strictly mine.
