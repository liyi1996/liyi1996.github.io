# Yi Li — Academic Website

An English academic website for Yi Li, postdoctoral researcher at Shanghai Jiao Tong University.

## Deploy with GitHub Pages

1. Upload the *contents* of this folder (not the folder itself) to the `main` branch of `liyi1996/liyi1996.github.io`.
2. Open **Settings → Pages** in the repository.
3. Set **Build and deployment → Deploy from a branch**.
4. Select **main** and **/(root)**, then click **Save**.
5. Open https://liyi1996.github.io/ after GitHub Pages finishes deploying.

No build tools or frameworks are required. Visitor statistics load one external counter image from flagcounter.me.

- `index.html`: primary one-page website
- `cv.html`: print-friendly CV
- `styles.css`: themes and responsive layout
- `script.js`: mobile menu, theme switching, publication filters
- `favicon.svg`: visual identity

Edit publication titles and links in both `index.html` and `cv.html` when updating the website. Update the publication filter counts if the list size changes.

**Note:** The academic content is a first draft based on existing CV details. Verify coauthor details and manuscript statuses before publication. Add Google Scholar and ORCID only after verifying the correct profile URLs.

## Visitor statistics

- Provider: [flagcounter.me](https://flagcounter.me/).
- Public dashboard: <https://flagcounter.me/details/kNE>.
- Both `index.html` and `cv.html` use the same counter image, `https://flagcounter.me/kNE`, so they share their visitor totals.
- A unique visitor means a unique IP address over the life of this counter. Refreshing or moving between pages adds pageviews but does not add another unique IP. Shared IP addresses and VPNs affect the estimate.
- Countries/regions are based on IP geolocation, not nationality. Tracking started on 4 November 2026; earlier visits are not included.
- The widget shows up to 12 country flags and their visitor counts. The linked dashboard provides the total unique visitors and the full country breakdown.
- Load the image eagerly even though it is in the footer: lazy loading would miss visitors who do not scroll to the bottom.
- The owner password is stored outside this repository in a Windows-encrypted local management record. It must not be added to HTML, JavaScript, or Git.

See the provider's [counting methodology and FAQ](https://flagcounter.me/faq) and [privacy notice](https://flagcounter.me/privacy).
