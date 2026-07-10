# Mediante Landscape & Pool Design Co. — Website

Static multi-page site generated from the Google Stitch "Mediante Design Studio" brand hub export.

## Pages
- `index.html` — Home (hero, pedigree strip, Beach Pool intro, service pillars, founder's note, final CTA)
- `beach-pool.html` — The Beach Pool flagship product page (Lagoon Philosophy + 4-stage Architectural Journey)
- `founder-story.html` — Michael Mediante's founder story / credentials

## Notes
- Built with Tailwind CSS (via CDN) + Google Fonts (Playfair Display, Inter, Material Symbols). No build step required — open `index.html` directly or serve the folder with any static host.
- Navigation and footer links between the three pages are wired up (`Beach Pools`, `Founder`, `Portfolio`, `Services`, `Process` anchors).
- Some links are intentionally still placeholders (`#`) pending real destinations: social icons, "Contact Us" / "WhatsApp Support" / "Booking" (no contact page or number yet), and the individual pillar "DETAILS" links (Services subpages not yet built).
- Design tokens (colors, type scale, spacing, component rules) are documented in `mediante_design_strategy.md` and the original `DESIGN.md` from the Stitch export, kept here for reference.

## Suggested next steps
- Build out Services (Softscape/Hardscape), Portfolio/Credentials, Process & Quality, Partner With Us, and Contact pages per `mediante_design_strategy.md`.
- Replace placeholder social/contact links once real accounts, phone/WhatsApp number, and a booking flow are available.
- Consider hosting on Vercel/Netlify/GitHub Pages for a live preview.
