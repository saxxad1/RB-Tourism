# RB Tourism — Coming Soon

A static Coming Soon page with a full-screen mountain travel image. The logo, announcement, and assistance number fit within one viewport on desktop and mobile, including short landscape screens. The complete website is in `dist/` and can be uploaded directly to the document root of any static web host. No Node.js, build step, database, or server application is required.

The page uses the supplied brand guidelines' original vector logo in Deep Emerald (`#025A42`) and Crimson (`#E3163D`). At the owner's request, only the TOURISM wordmark uses Warm Ivory (`#F7F4EE`), matching the Coming Soon heading, for visibility over the photo. The original logo was extracted from the supplied PDF and is preserved as a separate asset. Keep the green and red monogram and light wordmark as the website default; change logo colors only at the owner's explicit request. The photo has an emerald overlay with Crimson and Warm Ivory page accents. Inter is the approved digital fallback and is hosted locally; its license is included in `dist/assets/Inter-LICENSE.txt`.

The displayed assistance number is `01810-688210`. Its call link uses the international format `tel:+8801810688210`.

The mountain image is original AI-generated scenery, not a photograph of a named destination. Its generation prompt and asset provenance are in `IMAGE-PROVENANCE.md`. No navigation, social links, visitor tracking, subscription form, or third-party runtime is included.

To preview locally, serve `dist/` with any static HTTP server, for example `python3 -m http.server 4173 --directory dist`.

For Vercel, import this repository with the repository root as the Root Directory. The included `vercel.json` selects the static-site preset, skips a build command, and serves `dist/` as the Output Directory. Pushes to `main` deploy through the connected Vercel project.
