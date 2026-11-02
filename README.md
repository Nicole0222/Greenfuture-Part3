# GreenFuture NGO Website - WEDE5020 Part 3

**Student:** MOYANA NICOLE KAMOHELO METLER - ST10529094
**Module:** WEDE5020 - Part 2 & Part 3
**Organization:** GreenFuture NGO - Sustainable Development NGO based in Johannesburg, South Africa
**GitHub Repo:** https://github.com/Nicole0222/Greenfuture-Part3
**Live Site:** https://Nicole0222.github.io/Greenfuture-Part3/

---

## Project Overview
GreenFuture is a 5-page responsive website for an environmental NGO in Johannesburg, Gauteng. Built with HTML5, CSS3, JavaScript, jQuery, and Leaflet maps. Features SEO optimization, interactive elements, dynamic filtering, cost calculator, and AJAX form validation.

## Site Map
- `index.html` - Home - Overview, mission, Johannesburg keywords
- `about.html` - About Us - Team + Leaflet Map (-26.2041, 28.0473 Johannesburg)
- `programs.html` - Programs - Search/filter/sort + Accordion FAQ + Lightbox Gallery
- `enquiry.html` - Enquiry - Cost calculator (R50 x qty) + Availability + Validation + AJAX
- `contact.html` - Contact - Form validation + AJAX + Mailto compilation + Map
- `sitemap.xml` - XML sitemap for SEO
- `robots.txt` - Robots file for crawlers
- `images/` - All images with descriptive alt text
- `README.md` - This file

## Changelog

### Part 2 - Initial Website (Commit 1)
- Created 5 HTML pages: index, about, programs, enquiry, contact
- Added inline CSS styling with GreenFuture brand color #2E8B57
- Created responsive navigation
- Added basic structure and placeholder images
- Commit Message: `Part 2 - Initial GreenFuture NGO website with 5 pages and inline styles`

### Part 3 Development

#### Commit 2: On-Page SEO
- Added unique `<title>` tags for each page (50-60 chars) with "Johannesburg, South Africa"
- Added `<meta name="description">` 150 chars per page
- Added `<meta name="keywords">` with location keywords
- Added `<meta name="author">` and robots
- Added descriptive `alt` attributes for all images (e.g., "Solar panel training program in Johannesburg township")
- Created `sitemap.xml` with all 5 URLs and priority
- Created `robots.txt` with sitemap reference
- Used H1, H2 hierarchy correctly
- Commit Message: `Part 3: Added on-page SEO - title tags, meta descriptions, H1-H2, alt text, Johannesburg keywords, sitemap.xml, robots.txt`

#### Commit 3: Interactive Elements
- **Leaflet Map:** Added interactive OpenStreetMap in about.html centered on Johannesburg (-26.2041, 28.0473) with 2 markers (Office + Soweto site)
- **jQuery Accordion:** FAQ section in programs.html using jQuery slideToggle
- **Lightbox Gallery:** Custom JS lightbox for program images
- **Hover Effects:** CSS transform scale and box-shadow on gallery and program cards
- Commit Message: `Part 3: Added interactive elements - Leaflet map for Johannesburg, jQuery accordion FAQ, lightbox gallery, hover effects`

#### Commit 4: Dynamic Content & Enquiry Calculator
- **Search/Filter/Sort:** programs.html - text search + category filter (energy/food/education) + sort by name/price using JS data attributes
- **Cost Calculator:** enquiry.html - R50 x quantity formula, displays total, quantity display, discount logic for 10+ people (10% off)
- **Availability Logic:** Checks quantity >20 = Limited, shows date-based availability, reserves spots message
- Commit Message: `Part 3: Added dynamic content - program search/filter/sort + enquiry cost calculator R50 x qty + availability logic`

#### Commit 5: Form Validation + AJAX + Mailto
- **Validation:** Both enquiry.html and contact.html - name min 3 chars, email regex, phone 10 digits, message min 10 chars, error spans in red
- **AJAX No Reload:** e.preventDefault() + setTimeout simulation, form status messages, page does NOT reload
- **Mailto Compilation:** Enquiry data saved to localStorage, passed via URL params to contact page, compiled into mailto: link with subject and body encoded
- **Enquiry to Contact Link:** enquiry.html button "Open Contact Page with Mailto" loads contact.html?enquiry=...
- Commit Message: `Part 3: Added JavaScript form validation, error handling, AJAX submission without reload, mailto compilation`

#### Commit 6: README & Final Polish
- This file
- Commit Message: `Part 3: Updated README - changelog, Part 2 feedback fixes, site map, references`

## Part 2 Feedback & Fixes
**Feedback Received in Part 2:**
1. Navigation not consistent across pages - Fixed: Same nav in all 5 pages
2. Images missing alt text - Fixed: Added descriptive alt with Johannesburg/Gauteng keywords
3. No mobile responsiveness - Fixed: Added viewport meta + max-width + grid responsive
4. No SEO - Fixed: Full SEO implementation in Commit 2
5. Inline styles only - Kept inline as required but organized with <style> blocks

## Technical Implementation

### SEO Techniques Used
- Title tags with location: "GreenFuture NGO Johannesburg"
- Meta descriptions unique per page
- Heading hierarchy H1 (one per page) + H2 + H3
- Alt text with keywords
- Sitemap.xml and robots.txt
- Canonical link

### Interactive & Dynamic
- Leaflet.js v1.9.4 CDN for map
- jQuery 3.6.0 CDN for accordion
- Vanilla JS for lightbox, filter, calculator, validation
- localStorage for enquiry compilation

### Form Validation Regex
```js
Email: /^[^\s@]+@[^\s@]+\.[^\s@]+$/
Name: length >=3
Message: length >=10