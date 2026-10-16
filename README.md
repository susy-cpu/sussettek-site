# sussettek.com

Portfolio of Sussette Kalife. Hosted on Cloudflare Pages; every push to `main` goes live in about a minute.

## Files
- `index.html` — the whole site (layout + all project text)
- `assets/<project>/` — images and videos, one folder per project
- `Sussette_Kalife_CV.pdf` — linked from "Download CV"
- `support.js`, `image-slot.js` — required runtime files, don't edit

## Adding images to a project
1. Compress: WebP, ~2000px on the long side, under 400 KB (squoosh.app). Videos: MP4, muted, under 5 MB.
2. Put files in `assets/<project-name>/`, e.g. `assets/oum-calma/01.webp`.
3. In `index.html`, find the project (search its title) and add:
   `"images": ["assets/oum-calma/01.webp", "assets/oum-calma/02.webp"]`
   `"captions": ["Caption one", "Caption two"]`
4. Commit and push.

Frames without an image are hidden on the live site.
