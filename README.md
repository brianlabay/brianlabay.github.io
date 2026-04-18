# Zero Hour — Star Wars Legion Blog
**brianlabay.github.io**

A Star Wars Legion strategy and hobby blog covering army lists, battle reports, painting guides, and competitive meta analysis.

---

## Repo Structure

```
brianlabay.github.io/
│
├── index.html                          ← Homepage (GitHub Pages entry point)
├── site.css                            ← Shared stylesheet for all site/category pages
├── article.css                         ← Shared stylesheet for all article pages
│
├── assets/
│   ├── images/                         ← Site-wide images (hero art, thumbnails)
│   └── list-images/                    ← Army list screenshots
│
├── army-lists/
│   ├── army-lists.html                 ← Army Lists category index
│   ├── 501st-article.html              ← LIVE: 501st analysis
│   └── drafts/                         ← WIP army list articles (not linked yet)
│
├── battle-reports/
│   ├── battle-reports.html             ← Battle Reports category index
│   └── drafts/                         ← WIP battle reports
│
├── painting/
│   ├── painting.html                   ← Painting category index
│   └── drafts/                         ← WIP painting guides
│
├── meta/
│   ├── meta.html                       ← Meta category index
│   └── drafts/                         ← WIP meta analysis articles
│
└── pages/
    ├── about.html                      ← About page
    ├── battle-report-pending.html      ← Pending article placeholder
    ├── painting-pending.html           ← Pending article placeholder
    ├── meta-pending.html               ← Pending article placeholder
    └── darktrooper-pending.html        ← Pending article placeholder
```

---

## Writing a New Article

1. Write your article using the template below
2. Save it in the correct folder (e.g. `army-lists/my-new-article.html`)
3. Add a card to the category index page (e.g. `army-lists/army-lists.html`)
4. Add a card to `index.html` if it should appear on the homepage grid
5. Update the nav dropdown on `index.html` if it is the first article in a category

### Relative Path Reference

| File location                    | CSS link           | Images prefix           | Home link        |
|----------------------------------|--------------------|-------------------------|------------------|
| `army-lists/article.html`        | `../article.css`   | `../assets/images/`     | `../index.html`  |
| `battle-reports/article.html`    | `../article.css`   | `../assets/images/`     | `../index.html`  |
| `painting/article.html`          | `../article.css`   | `../assets/images/`     | `../index.html`  |
| `meta/article.html`              | `../article.css`   | `../assets/images/`     | `../index.html`  |

---

## CSS Components (article.css)

Copy HTML structure from `army-lists/501st-article.html`

| Class | Purpose |
|---|---|
| `.article-lead` | Bold intro paragraph with gold left border |
| `.callout` | Info box — add `data-label="LABEL"` attribute |
| `.callout-warning` | Red warning box |
| `.callout-tip` | Green tip box |
| `.stat-block` | Unit stat card with grid |
| `.list-card` | Army list points breakdown |
| `.list-image-wrap` | Centred list screenshot with caption |
| `.key-point` | Numbered key point row |
| `.art-divider` | Section divider with gold diamonds |
| `.verdict` | Final conclusion/verdict box |

---

## Article Status

| Article | Category | Date | Status |
|---|---|---|---|
| 501st Isn't Bad — People Just Build It Fundamentally Wrong | Army Lists | Apr 18, 2026 | Live |
| The Double Dark Trooper Standby Castle — Worlds Top 2 | Army Lists | TBC | Pending |
| White Armour Made Easy — Why Your Airbrush Changes Everything | Painting | TBC | Pending |
| How AMG's Legion 2.6 Update Is Shaking Up the Meta | Meta | TBC | Pending |
| Battle Report — TBC | Battle Reports | TBC | Pending |
