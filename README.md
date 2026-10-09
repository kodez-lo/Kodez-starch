# Kodez Starch

A responsive Diwali demo store built with HTML, CSS and JavaScript. No backend or build step.

## Run
Serve the `dist` directory with any static server, for example `python -m http.server 8080 --directory dist`, then open http://localhost:8080. Deploy `dist` on any static hosting service.

## Included
- 60 sample catalogue entries across 6 categories
- 32 downloaded product photographs, plus a hero photo; optimised WebP assets
- Search, category filters, price/name sorting and incremental catalogue browsing
- Accessible quick-view dialogs, wishlist, cart quantity controls, removal and demo checkout
- Local browser persistence, empty states, keyboard focus handling and reduced-motion support
- Scroll reveals and a dependency-free interactive 3D terracotta diya with a light switch

Edit products and demo prices in `dist/catalog.js`. Images are local in `dist/assets`. Sample pack variants reuse representative imagery. `dist/asset-sources.json` records the source URLs. Confirm image reuse permissions and actual product specifications before using commercially. Demo checkout never creates orders, takes payment or ships goods.

## Verification
JavaScript syntax checks and automated catalogue, asset and interaction checks. Browser visual QA was unavailable in the build environment.
