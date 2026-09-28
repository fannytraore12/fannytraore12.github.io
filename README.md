# Fanny Traore | Portfolio

My bilingual (English/French) portfolio website. I'm a Computer Systems Engineering student at Carleton University.

**Live site:** https://fannytraore12.github.io · **Version française :** https://fannytraore12.github.io/fr.html

## What's on it

- **About:** who I am and what I'm looking for, with links to my resume (PDF), GitHub and LinkedIn
- **Projects:** Mochadoro, ScamFree and my PYNQ-Z2 Morse code decoder, shown as cards (Mochadoro has an image carousel)
- **Skills, Experience and Contact**

## Built with

- HTML5 and CSS
- [Bootstrap 5](https://getbootstrap.com/) (navbar, grid, cards, carousel), loaded from a CDN
- [Judson](https://fonts.google.com/specimen/Judson) from Google Fonts for headings
- Hosted on GitHub Pages; layout planned in Figma first

## Accessibility

I designed the site to meet the Web Content Accessibility Guidelines (WCAG) and audited it with [WAVE](https://wave.webaim.org/) and Lighthouse.

**Built in from the start**
- A "Skip to content" link for keyboard users
- A visible focus outline on every link and button (`:focus-visible`)
- `lang="en"` / `lang="fr"` on each page and on the language switcher links
- `aria-label`s on the navigation and menu button, in both languages
- An image carousel that only moves when the user clicks, with labelled buttons

**Fixed during the audit**
- Darkened the accent colour from a 3.93:1 to a 5.04:1 contrast ratio
- Rewrote alt text that did not match its image
- Darkened the carousel arrows so they stand out on light images
- Reviewed two WAVE contrast flags; they were visually hidden screen reader labels, so no change was needed

**Lighthouse results (September 2026)**

| Page | Performance | Accessibility | Best Practices | SEO |
|---|---|---|---|---|
| English | 94 | 100 | 100 | 100 |
| French | 99 | 100 | 100 | 100 |

## Files

```
index.html     English page
fr.html        French page
style.css      Colours, fonts and focus styles (shared by both pages)
images/        Project images
*.pdf          Resume (English and French)
```

## Run it locally

No build step: clone the repo and open `index.html` in a browser.

```
git clone https://github.com/fannytraore12/fannytraore12.github.io.git
```
