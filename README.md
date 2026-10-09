# Host It Yourself

A six-page website mockup for a Web design course project — a friendly guide to
self-hosting your photos with [Immich](https://immich.app) as a private,
Google-Photos-style cloud you run on your own hardware.

## Pages

| Page | File | Question it answers |
|---|---|---|
| Home | `index.html` | Why would I quit Google Photos? |
| Meet Immich | `meet-immich.html` | What does it do, and is it any good? |
| Requirements | `requirements.html` | What do I need? |
| Getting Started | `getting-started.html` | How do I get it running? |
| Keep Them Safe | `keep-them-safe.html` | What happens when the disk dies? |
| Contact | `contact.html` | Work in progress |

## Design

- **Desktop only** — fixed **1440px** width, deliberately **not responsive**.
- **Fonts** — [Prompt](https://fonts.google.com/specimen/Prompt) for headings,
  [Roboto Serif](https://fonts.google.com/specimen/Roboto+Serif) for body text.
- **Type scale** — H1 `3.875rem` · H2 `3rem` · H3 `2.5rem` (all `120%`
  line-height); small `0.875rem/170%`; regular `16px/160%`; large `20px/160%`.
- **Colour palette**
  - `#732439` primary — homepage hero, footer, content headings
  - `#3C4E2F` secondary — dark band, detail-page header
  - `#BCC9A7` text-secondary — buttons, detail-page hero band
  - `#F2F2F2` background
  - `#734636` bright text
  - `#281913` text

## Structure

```
.
├── index.html            # Home
├── meet-immich.html
├── requirements.html
├── getting-started.html
├── keep-them-safe.html
├── contact.html
├── style.css             # single shared stylesheet
└── images/               # illustrations used across the pages
```

## Viewing it

Open `index.html` in a browser at a 1440px-wide window. No build step, no
dependencies — just static HTML and CSS.

---

© Max Swart 2026
