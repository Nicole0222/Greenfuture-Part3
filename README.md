# WEDE5020 Part 3 - GreenFuture NGO - [MOYANA NICOLE KAMOHELO METLER] [ST10529094]

## Project Overview Part 3
Added for Part 3: SEO, interactive map, accordion with jQuery, gallery lightbox, dynamic search filter sort, enquiry cost calculation, contact email compilation, JS validation with AJAX, sitemap and robots.

Keyword Research: tree planting NGO Johannesburg, environmental NGO Soweto

## Changelog - THIS IS REQUIRED

### New Entries for Part 3
- 2026-10-29: Added SEO title, meta description, H1 H2, alt text with Johannesburg keyword - all pages
- 2026-10-29: Added accordion using jQuery slideToggle() - index.html and about.html
- 2026-10-29: Added interactive map using Leaflet - index.html #map
- 2026-10-29: Added gallery with lightbox openLightbox() - index.html
- 2026-10-29: Added dynamic content loading loadPrograms() + search + sort + filter - programs.html and index.html
- 2026-10-29: Added hover animations transform scale - about.html
- 2026-10-29: Added enquiry form cost logic R50 x qty and availability - enquiry.html
- 2026-10-29: Added contact form with action=mailto:info@greenfuture.org.za compilation - contact.html
- 2026-10-29: Added JS validation validate() + error handling + AJAX fetch() no reload - enquiry.html and contact.html
- 2026-10-29: Added sitemap.xml and robots.txt for SEO
- 2026-10-29: Added page speed - compressed images, simple inline CSS

### Feedback Edits from Part 2
- 2026-10-28: Feedback: Images had no alt text - Fixed: Added alt="Tree planting in Soweto Johannesburg" to all <img> tags in index.html line 20, about.html line 25 etc
- 2026-10-28: Feedback: No mobile view - Fixed: Added viewport meta and flex layout still works on mobile
- 2026-10-28: Feedback: No form validation - Fixed: Added validate() function checking 10 digit phone and 20 chars message in enquiry.html and contact.html

## On-Page SEO Done
- Title Tags: Unique title on each page
- Meta Descriptions: Each page has description with Johannesburg keyword
- Header Tags: H1, H2, H3 used
- Image Optimisation: All img have descriptive alt, e.g alt="GreenFuture volunteers Johannesburg"
- URL Structure: index.html, about.html, programs.html, enquiry.html, contact.html clean
- Internal Linking: Nav links + links to enquiry.html and sitemap.xml
- Mobile-Friendly: viewport meta tag + responsive inline styles

## Off-Page and Additional SEO
- Backlinks: Plan to submit to NGO directory South Africa
- Social: Will link Facebook/Instagram of GreenFuture
- Local SEO: Johannesburg keyword + map coordinates -26.2041, 28.0473 + Soweto address
- robots.txt and sitemap.xml included
- Page Speed: Simple inline styles, compressed images, no large files
- Security: https on Netlify, inputs sanitized with trim()
- Performance: Minimal JS, one jQuery import
- Accessibility: Labels for inputs, alt text, color contrast #245C36 on white

## References Part 3 Updated
- Leaflet Maps https://leafletjs.com/ - Used for interactive map in index.html
- jQuery 3.6.0 https://jquery.com/ - Used for accordion slideToggle
- MDN Form Validation https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation
- Formspree https://formspree.io/ - Used for AJAX form handling
- Google Fonts Lora, Poppins

## How to Run
Open index.html in browser. Or live link: https://yourname.netlify.app