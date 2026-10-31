# Hope For All Foundation — Part 3

Static educational demonstration website built with HTML, CSS and JavaScript. Based on the submitted Part 2 project. No real payments are collected and no server receives form data. Contact/volunteer/donation forms open the visitor’s email application; the visitor must manually send the message. Confirm the sample contact address and physical address before public use.

## Pages
- `index.html`: homepage with live programme search and filtering.
- `about.html`: image gallery with accessible lightbox.
- `services.html`: programme information.
- `get involved.html`: volunteer and donation enquiry forms.
- `enquiry.html`: validated enquiry with contextual response.
- `contact.html`: contact form and interactive Leaflet/OpenStreetMap map of an **illustrative** area, not a verified office location.
- `thankyou.html`: informational page.

## Running
Open `index.html` in a browser. For the most consistent results use VS Code Live Server or `python -m http.server 8000` and open `http://localhost:8000`. The map requires an internet connection.

## Deployment
Publish the website folder's contents to GitHub Pages or Netlify. GitHub Pages works best when the repository root contains `index.html`. After the site has a real domain, replace `YOUR-REAL-DOMAIN` in `sitemap.xml` and add a Sitemap line to `robots.txt`. Verify all pages and links on the deployed site.

## Part 3 changelog
- Retained Part 2 site content and styles while adding responsive and accessible refinements.
- Fixed broken `membership.html` and `thank-you.html` links, missing script reference and wrong logo filename.
- Added working JavaScript-powered programme search with live results.
- Added keyboard-accessible image lightbox and modal close controls.
- Added interactive map for the Centurion area, explicitly marked illustrative.
- Added separate enquiry and contact pages, HTML5 validation, error messages and context-sensitive enquiry response.
- Added email-composition workflow for contact, volunteering and donation enquiries; no false claim of server-side submission or payment processing.
- Added page-specific title tags, descriptions, keywords, image alt text, `robots.txt` and placeholder `sitemap.xml`.
- Improved responsive layouts, keyboard focus and reduced-motion support.
- Removed duplicate development notes from the release archive.

## SEO / off-page checklist
Share the deployed website through appropriate social channels and obtain genuine relevant backlinks. Verify business information before using local SEO claims. Measure page speed with Lighthouse after deployment. Never add unverified reviews or locations.

## References
- MDN Web Docs: https://developer.mozilla.org/
- Leaflet documentation: https://leafletjs.com/reference.html
- OpenStreetMap contributors: https://www.openstreetmap.org/copyright
- Google Search Central SEO Starter Guide: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- W3C WAI forms guidance: https://www.w3.org/WAI/tutorials/forms/

### Reference and attribution details
Accessed 31 October 2026. These are documentation sources used as technical guidance; they are not evidence of the foundation's real-world activities or contact details.

1. Mozilla (n.d.) *MDN Web Docs: HTML forms and client-side validation*. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Form_validation (Accessed: 31 October 2026).
2. Leaflet (n.d.) *Leaflet API reference*. Available at: https://leafletjs.com/reference.html (Accessed: 31 October 2026).
3. OpenStreetMap contributors (n.d.) *Copyright and licence*. Available at: https://www.openstreetmap.org/copyright (Accessed: 31 October 2026).
4. Google Search Central (n.d.) *SEO Starter Guide*. Available at: https://developers.google.com/search/docs/fundamentals/seo-starter-guide (Accessed: 31 October 2026).
5. W3C Web Accessibility Initiative (n.d.) *Forms Tutorial*. Available at: https://www.w3.org/WAI/tutorials/forms/ (Accessed: 31 October 2026).

**Image provenance:** Existing photographs and logos were carried over from the provided Part 2 archive. Their original creators/licences were not documented in the available files. Confirm usage rights and add image-by-image attribution before public deployment. The map tiles are credited to OpenStreetMap contributors on the map.

**Submission verification:** The site has not been tested in every browser or deployed. The example `info@hfa.org` email and Centurion map point must be confirmed/replaced. `sitemap.xml` uses a placeholder domain and must be edited after a live URL exists. The enquiry form generates a local response, not an actual submission; contact forms open a mail client, which requires user action. Do not claim emails were sent automatically.

### Part 3 map restoration
The Contact page restores the two original Google Maps embeds from the Part 2 submission (Centurion Mall and the Ga-Rankuwa care centre). These are real, interactive Google Maps embeds rather than an illustrative map. They require an internet connection and may be subject to Google Maps availability. Verify that each map represents the intended organisation location before submission.
