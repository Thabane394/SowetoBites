# SowetoBites - Community Food & Culture Website

## Student Details
**Name:** Thabane Makoro
**Student No:** ST1049766
**Course:** WEDE5020 - Web Development 
**GitHub Pages Live Link:** https://Thabane394.github.io/SowetoBites-main/

## Project Description
SowetoBites is a community-focused website celebrating Soweto's food culture. The purpose is to act as an online guide where tourists, students and locals can discover authentic foods like Kota (R45), Shisa Nyama (R85) and Magwinya (R15), find trusted vendors in Vilakazi Street area, and support small businesses. Built with HTML5 semantic elements and external CSS3.

## Website Structure and Planning
**Sitemap:**
The site has 5 pages all linked from Home:
- Home (index.html) -> About, Products, Enquiry, Contact
- All pages share same header/footer and css/style.css
  
![Sitemap](images/sowetobites_sitemap.png)

**Planning:**
- Target audience: Local residents, students, tourists visiting Johannesburg
- Goal: Promote local culture and create job opportunities

## Folder Structure
- index.html, about.html, products.html, enquiry.html, contact.html - Main pages
- css/style.css - External stylesheet (CSS Reset, Typography, Grid/Flexbox, Media Queries)
- images/ - Business images optimized with srcset (480w, 800w, 1200w)
- README.md - Project documentation
- CHANGELOG.md - Record of development and feedback fixes

## Features and Functionality
- Responsive design: Desktop 3-column Grid -> Tablet 2-column -> Mobile 1-column
- Flexbox navigation
- Responsive images using srcset and sizes attributes
- Visual styles: box-shadow, border, hover effects, focus states
- Relative units: %, em, rem used throughout

## Technologies Used
- HTML5 (semantic: header, nav, main, footer)
- CSS3 (Flexbox, Grid, Media Queries, Pseudo-classes :hover :focus :active)
- GitHub for version control with descriptive commits

## How to Run / View Website
1. Clone repo or download ZIP
2. Open index.html in browser OR use VS Code Live Server
3. Navigate via header menu

## Screenshots - Responsive Evidence (Required for Part 2)
### Desktop (1200px)
![Desktop 1200px](images/deskop-1200px.png)

### Tablet (768px)
![Tablet 768px](images/deskop-768px.png)

### Mobile (480px)
![Mobile 480px](images/deskop-480px.png)

## Changelog - Record of Development and Feedback Fixes
### [2.0] - 2026-09-02 - Part 2: Designing Visuals
- Added CSS Reset for consistent styling across browsers
- Added Typography styles with font-family, line-height, letter-spacing, text-transform
- Added Layout structure using Flexbox (header) and Grid (products)
- Added Visual styles: color, background, border, box-shadow
- Added Breakpoints: @media 768px and 480px for responsive
- Added Relative units: % for width, rem/em for fonts/padding
- Added Responsive images: srcset, sizes, picture element
- Added HTML comments explaining structure

### [1.1] - 2026-09-02 - Fixes from Part 1 Feedback (Lecturer Rubric)
- FIXED 0/5 Changelog: Created CHANGELOG.md file
- FIXED 0/5 Sitemap: Created sitemap.png and sitemap.xml
- FIXED 0/5 Comments: Added <!-- comments --> to all HTML files
- FIXED 0/5 References: Added reference list below
- FIXED 1-2/5 README: Expanded from 15 lines to comprehensive doc with sitemap, tech, screenshots
- FIXED 2/10 Content Research: Added real descriptions, prices, vendor locations

### [1.0] - Initial Part 1 Submission
- Created 5 HTML pages, basic style.css

 ### [3.0] - 2026-10-26 - Part 3: Adding Interactivity and SEO (FINAL POE)

#### Fixed from Part 2 Feedback (95% -> aiming 100%)
- FIXED Hiding Navigation on Home: Changed header to `position: fixed; top:0; width:100%; background:#fff; box-shadow; z-index:1000;` - nav now always visible on scroll
- Added hamburger toggle (☰) for mobile with JS: menuToggle + navLinks.show class
- Applied consistently across all 5 pages

#### 2.1 Interactive Elements Added (Requirement 2.1)
- Hamburger Menu Toggle - All pages - click ☰ to open/close nav
- Tabs Filtering - products.html - All / Kotas / Burgers / Plates
- Accordion FAQ - about.html - 3 FAQs about SowetoBites, Halal, Delivery
- Lightbox Gallery - products.html - Click image to enlarge (modal)
- Cost Calculator - enquiry.html - Calculates (guests x R45 + delivery) = total in real time

#### 2.2 Dynamic Content (Requirement 2.2)
- Menu loaded from JS array (menuData) - not hardcoded HTML - products.html
- Live search filter - search box filters kota, burger, shisa nyama instantly
- Interactive Leaflet Map - contact.html - OpenStreetMap with marker at Vilakazi Street (-26.235, 27.908)
- Dynamic total price updates without page reload

#### Section 4: Forms and Validation (Requirement 4)
- enquiry.html: Full JS validation - name, email regex, guests number, event type - shows error messages in red
- Prevent default submission (e.preventDefault) - no reload
- Quote calculator: qty x price logic
- Success message: "Enquiry Sent! We will WhatsApp you"
- contact.html: Form compiles into mailto email (user's email client)
- WhatsApp ordering links kept: wa.me/27769746429

#### SEO Optimization (Requirement)
- Meta description + keywords on all pages (e.g. Best Kotas in Soweto, Vilakazi Street)
- Optimized titles with keywords
- Alt text for all images with keywords (e.g. Kota Special Soweto - quarter loaf)
- robots.txt created - Allow all + Sitemap link
- sitemap.xml created - 5 pages listed with priority
- Live link updated: https://thabane394.github.io/SowetoBites/

#### References Added for Part 3
- Leaflet.js - https://leafletjs.com - Interactive map
- OpenStreetMap tiles - Map data
- Unsplash - Kota Special, Magwinya images with srcset optimization


## References
- South African History Online. (2024). Soweto. Available at: https://www.sahistory.org.za
- The IIE. (2026). WD101 Learning Unit 2: CSS Styling.
- Images: Pexels.com and Unsplash.com - Free license images of South African food.
- Mozilla Developer Network. (2024). Responsive images srcset.

## Licence
Educational project for IIE WEDE5020.
