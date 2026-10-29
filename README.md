# Himalaya · Parvat Explorer (prototype v3)

## What's updated
- Home branding now features **HIMALAYA · PARVAT EXPLORER** and a custom mountain mark.
- Search across mountain name, range, region, country and continent.
- Filters for continent, country and elevation bands (8,000–8,999 m; 6,000–7,999 m; 4,000–5,999 m; under 4,000 m).
- The same filters are available on the full Mountain Index page.
- Country and continent choices are populated from the catalogue.

## Upload to GitHub Pages
In the repository, open **Add file → Upload files** and upload/replace `index.html`, `manifest.json`, `sw.js`, and `README.md` from this folder. Commit the changes to `main`. Wait a few minutes and refresh the live site. If the old UI remains on a phone, close the installed app and clear/reload the site cache; service-worker cache can delay updates.

## Prototype limitations
This is still a client-side prototype. LocalStorage changes stay on the same browser/device; Archive Tools are not protected by real authentication. For public launch, connect a backend (e.g. Supabase) with database-enforced admin-only editing, public read access, anonymous mountain requests, moderation, and image storage. Demo facts and geography need source verification before public release.
