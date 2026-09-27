# Fang & Forge Productions

Public studio website and project hub for **Fang & Forge Productions**.

The site is intentionally built as a simple static HTML/CSS/JavaScript website so it can be hosted directly with GitHub Pages and moved to another web host later without requiring a framework or build process.

## Structure

```text
fang-and-forge-site/
├── index.html
├── about/
│   └── index.html
├── worlds/
│   ├── index.html
│   └── veyra/
│       └── index.html
├── projects/
│   └── index.html
├── support/
│   └── index.html
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── main.js
```

## Hosting

The current site can be served directly from the repository root with GitHub Pages. No Node.js, npm, Astro, or build step is required.

Future applications such as a VTT or supporter/member backend should remain separate from this public static site.
