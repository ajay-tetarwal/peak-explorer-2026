# Mountain Explorer v2 — minimalist multi-page-style PWA prototype

## UX direction
Minimalist editorial design, warm off-white canvas, forest-green accents, serif mountain headings, generous spacing, compact facts and dedicated mountain detail pages.

## How to run
Serve this folder over HTTPS or localhost for installable PWA/service-worker behavior. Open `index.html` for a preview. Mountain cards open dedicated detail views with a distinct route-like URL hash (`#mountain/everest`); the app includes separate Discover, Mountain Index, Field Journal, About and Archive Tools views.

## Prototype functionality
- Mountain catalogue with filters/search
- Dedicated mountain detail page per mountain
- History, first ascent, route/camps, season/safety, summit register
- Add/edit/delete mountain records
- Community field-note submissions and local review queue
- Summit record submission
- Import/export archive JSON
- LocalStorage persistence and PWA shell

## Not production yet
This is a client-side prototype. LocalStorage data is only on this browser/device. Archive Tools are not protected by real authentication, and image URLs are used instead of cloud uploads. Demo content needs source verification before public release.

## Production backend plan
Connect Supabase (Postgres, Auth, Storage) or Firebase. Tables/collections: mountains, routes, camps, expeditions, climbers, summit_records, submissions, media, source_references. Add server-enforced roles and access policies. Registered climbers submit changes; admins approve and publish. Store image files in object storage with attribution, licence and source fields. Deploy over HTTPS. Content updates will then appear across devices without rebuilding the app.
