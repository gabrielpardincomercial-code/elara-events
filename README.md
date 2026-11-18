# Elara Events — Luxury Event Planner Website

A standalone, pixel-perfect clone and replication of [Elara Events](https://elara-events-wbs.framer.website/).

## Features
- **100% Localized Assets**: All web fonts (`.woff2`), high-res photography, SVG icons, and looping video backgrounds (`.mp4`) are stored locally in `assets/`.
- **Framer Runtime Preserved & Localized**: Complete self-hosted `.mjs` modules and `.framercms` binary databases with byte-range slicer patches for static servers (LiteSpeed/Apache).
- **Clean URLs**: Server-side URL rewriting via `.htaccess` (`/about`, `/service`, `/service/full-planning-design`, `/case-study/sofia-luca`).
- **Telemetry & Watermark Free**: Removed Framer analytics, editor overlays, and badge containers.
- **Production Optimized**: Immutable caching headers, Brotli/Gzip compression, and SEO discoverability (`sitemap.xml`, `robots.txt`).

## Structure
```
elara-events/
├── index.html
├── about.html
├── gallery.html
├── contact.html
├── blog.html
├── case-study.html
├── service.html
├── 404.html
├── blog/
│   ├── index.html
│   ├── create-a-wedding-full-of-elegance.html
│   ├── creating-a-smooth-wedding-timeline.html
│   ├── designing-a-wedding-your-way.html
│   ├── questions-before-hiring-a-planner.html
│   ├── wedding-planning-mistakes-to-avoid.html
│   ├── your-guide-to-wedding-planning.html
│   └── your-guide-to-wedding-venues.html
├── case-study/
│   ├── index.html
│   ├── clara-james.html
│   ├── mei-thomas.html
│   ├── sofia-luca.html
│   └── true-moments.html
├── legal/
│   ├── privacy-policy.html
│   └── terms-conditions.html
├── service/
│   ├── index.html
│   ├── day-of-coordination.html
│   ├── destination-weddings.html
│   ├── full-planning-design.html
│   └── partial-planning.html
└── assets/
    ├── css/
    ├── cms/
    ├── fonts/
    ├── framer/
    ├── images/
    └── videos/
```
