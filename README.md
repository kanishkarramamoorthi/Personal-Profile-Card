# Developer Profile Card

A single-file, responsive developer profile card built with pure HTML & CSS — no frameworks, no dependencies.
## Overview

A dark, terminal-inspired profile card designed for developer portfolios, personal sites, or "about me" sections. It mimics a code editor / terminal window aesthetic, using monospace typography and subtle animations to give it a distinct, professional feel.

## Features

- **Terminal-style title bar** — macOS-style traffic light dots and a fake file path
- **Animated cursor** — blinking text cursor next to the name, like a live terminal prompt
- **Status badge** — glowing "available for work" indicator
- **Bio section** — written like a terminal command (`$ whoami`)
- **Stats grid** — years of experience, projects completed, client satisfaction
- **Tech stack tags** — skill badges, with the primary skill styled like a git branch (`⎇ main`)
- **Call-to-action buttons** — Hire Me / Resume
- **Social links footer** — GitHub, LinkedIn, Twitter, Email
- **Fully responsive** — adapts down to mobile screens

## Tech Stack

- HTML5
- CSS3 (custom properties, gradients, flexbox, grid, keyframe animation)
- Google Fonts: [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (headings/code) & [Inter](https://fonts.google.com/specimen/Inter) (body text)

## File Structure

```
├── profile-card.html   # Main file — open directly in a browser
└── README.md           # This file
```

## Getting Started

No build step or install required.

1. Download `profile-card.html`
2. Open it in any modern browser

Or embed it directly into an existing site by copying the `<style>` block and the `.card` markup into your page.

## Customization

Open `profile-card.html` and edit:

| What to change      | Where                                  |
|----------------------|-----------------------------------------|
| Name, role, status   | `.name`, `.role`, `.status` elements   |
| Avatar initials       | `.avatar` text content                 |
| Bio text              | `.bio` element                         |
| Stats                 | `.stats` → each `.stat` block          |
| Tech stack tags       | `.tags` → each `.tag` element          |
| Button links           | `.actions` → `href` attributes         |
| Social links           | `.footer-links` → `href` attributes    |
| Colors                 | CSS custom properties in `:root`       |

## License

Free to use and modify for personal or commercial projects.
