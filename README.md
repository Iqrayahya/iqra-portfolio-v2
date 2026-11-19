# Iqra Yahya: Portfolio Website (v2)

Portfolio for Iqra Yahya, who creates AI videos and ads, builds AI agents and automates workflows with Claude Code.

Cream-and-crimson design: floating pill navigation, a hero where project cards fan out from the portrait as you scroll, expandable service cards, playable client ads, plans, process, FAQ, contact and a curved image carousel.

A single static page: plain HTML, CSS and JavaScript. No build step and no dependencies.

## Structure

```
index.html     the whole site (styles and scripts included)
images/        portrait, ad cover frames and project tiles
videos/        web versions of the client ads (H.264, 540p)
```

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the `main` branch and the `/ (root)` folder, then save.

The site goes live at `https://<your-username>.github.io/iqra-portfolio-v2/` within a minute or two.

## Editing

- **Contact form:** set `FORM_ENDPOINT` near the bottom of `index.html` (for example, a Formspree URL) so messages are actually sent. Until it is set, the form copies the visitor's message so they can send it on WhatsApp or email.
- **Book a Call:** the buttons open a WhatsApp chat; change the `wa.me` links to use another booking link.

© 2026 Iqra Yahya. All rights reserved.
