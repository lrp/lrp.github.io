# lrp.io

Personal site for Larry R. Price, PhD. Hosted on GitHub Pages at [lrp.io](https://lrp.io).

## Repo structure

```
index.html            # Self-contained single page (inline CSS + JS)
medium_headshot.jpeg   # Headshot used in About section
favicon.ico
CNAME                  # GitHub Pages custom domain config
```

## Design system

- **Background**: `#0F0F0F`
- **Text**: `#E8E8E8`
- **Muted text**: `#9A9A9A`
- **Accent**: `#D946EF` (used for name, links, section labels)
- **Accent dim**: `rgba(217, 70, 239, 0.15)`
- **Display font**: Space Grotesk 700 (hero name, section labels, nav logo)
- **Body font**: DM Sans 400/500/700 (everything else)
- Both loaded via Google Fonts

## Sections and nav

Nav: Home / About / Career / Contact

- **Home** (`#home`): Hero with name and tagline
- **About** (`#about`): Headshot + bio grid
- **Career** (`#career`): Koddi, Capital One, OpenX, Caltech (Senior Postdoc), University of Wisconsin-Milwaukee (Postdoc), University of Florida (PhD), Reed College (BA). Includes both professional history and education — no standalone Education section.
- **Recognition** (`#recognition`): Breakthrough Prize, Gruber Prize. Section exists on the page but is not in the nav.
- **Contact** (`#contact`): LinkedIn, Google Scholar, email

## Conventions

- No em dashes in copy (use en dashes for ranges)
- No resume/CV downloads
- No GitHub links
- Content changes require Larry's approval. The live site copy is canonical, not the original draft
- Everything is inline in `index.html`. No external CSS or JS files
- Mobile-first responsive layout with breakpoint at 640px
