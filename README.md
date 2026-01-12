# Personal Website

A clean, minimalist personal portfolio powered by [Zola](https://www.getzola.org/) and the [Apollo](https://github.com/not-matthias/apollo) theme.

## Setup

```bash
# Clone with submodules
git clone --recursive <repo-url>

# Or if already cloned, init submodules
git submodule update --init --recursive

# Serve locally
zola serve

# Build for production
zola build
```

The site will be available at `http://127.0.0.1:1111`

## Structure

```
.
├── config.toml          # Site configuration
├── content/
│   ├── _index.md        # Homepage
│   ├── about.md         # About page
│   ├── posts/           # Blog posts
│   └── projects/        # Projects showcase
├── static/              # Static assets
└── themes/apollo/       # Apollo theme (submodule)
```

## Customization

- Edit `config.toml` to update site title, social links, and menu
- Edit markdown files in `content/` to update pages
- Add new blog posts in `content/posts/`
- Add new projects in `content/projects/`

## Deployment

Build the static site and deploy the `public/` folder:

```bash
zola build
```

Deploy to GitHub Pages, Netlify, Vercel, or any static hosting service.

## License

MIT License
