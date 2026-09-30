N63CB SHOPIFY 360 VIEWER

WHAT THIS PACKAGE IS
- Responsive KeyShotXR 360 viewer prepared for embedding in Shopify.
- 90 source frames retained (30 horizontal x 3 vertical views).
- Frames optimized from 5000x5000 to 2500x2500 JPEG for much faster web delivery while preserving zoom detail.
- User can drag/pan around the aircraft and zoom up to 2x.
- Viewer is responsive and fullscreen-capable.

HOSTING
Shopify product descriptions should not be used to host this whole folder directly. Host this folder on a static web host such as GitHub Pages, then embed the hosted URL with the iframe in shopify-embed-snippet.txt.

GITHUB PAGES QUICK SETUP
1. Create a GitHub repository, e.g. n63cb-360.
2. Upload ALL contents of this folder to the repository root, preserving the viewer/ subfolder.
3. In GitHub: Settings > Pages > Build and deployment > Deploy from a branch.
4. Choose main branch and / (root), then Save.
5. Your viewer URL will normally be:
   https://YOUR-GITHUB-USERNAME.github.io/n63cb-360/
6. Open shopify-embed-snippet.txt and replace the placeholder URL.
7. Paste that iframe block into the HTML source of the Shopify product description.

SHOPIFY NOTE
If your theme/editor removes the iframe from the product description, add the same code in a Custom Liquid block on that product template instead.
