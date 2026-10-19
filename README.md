# Fresh Bread By IZA - Website Project

## 1. Project Overview
This website was developed for **Fresh Bread By IZA**, an artisan bakery located in Observatory, Cape Town. The goal of the website is to provide customers with information about business hours, menu, location, and a contact form for enquiries and orders.

The site consists of 5 main pages: Home, About, Menu, Enquiry, and Contact. All pages follow a consistent navigation and layout structure as required for Part 1 of the Web Development assignment.

## 2. Site Structure
The website includes the following 5 HTML pages:

| Page | File Name | Purpose |
| --- | --- | --- |
| Home | `index.html` | Welcome message and summary of bakery services |
| About | `about.html` | History, mission and values of Fresh Bread By IZA |
| Menu | `menu.html` | List of artisan breads, cakes, and savory items with prices |
| Enquiry | `enquiry.html` | Contact form for orders, catering and general questions |
| Contact | `contact.html` | Business hours, baking times, address, map, and contact details |

Additional folders:
- `/css` - Contains `style.css` for site styling
- `/CONTENT-RESEARCH` - Contains text files with all site content
- `/IMAGES` - Contains images used on the website

## 3. Technologies Used
- **HTML5**: For semantic structure of the website. Used elements like `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` as per W3C standards【W3C, 2024】.
- **CSS3**: For styling, layout, and responsive design. External stylesheet linked to all pages.
- **Git & GitHub**: For version control and project submission.

## 4. Design Principles & Academic References
The website design follows established web usability and development principles:

1.  **Usability**: The navigation is consistent across all 5 pages to reduce cognitive load. This follows Nielsen's 10 Usability Heuristics for User Interface Design【Nielsen, 2020】.
2.  **Semantic HTML**: Proper use of semantic tags improves accessibility and SEO. As defined by the W3C HTML5 Specification【W3C, 2024】.
3.  **User-Centered Design**: Content is organized based on user needs - menu, hours, and contact info are easily accessible. This approach is supported by Garrett's Elements of User Experience【Garrett, 2011】.
4.  **CSS Best Practices**: External CSS file used for separation of content and presentation, following guidelines in Meyer’s CSS: The Definitive Guide【Meyer, 2017】.

## 5. Content Sources
All textual content was sourced from the files in `/CONTENT-RESEARCH`:
- `ABOUT US.txt`
- `MENU - FRESH BREADS BY IZA.txt` 
- `OPENING HOURS.txt`

## 6. Academic References
Duckett, J. (2014). *HTML and CSS: Design and Build Websites*. John Wiley & Sons.

Garrett, J. J. (2011). *The Elements of User Experience: User-Centered Design for the Web and Beyond* (2nd ed.). New Riders.

MDN Web Docs. (2024). *HTML: HyperText Markup Language*. Mozilla. https://developer.mozilla.org/en-US/docs/Web/HTML

MDN Web Docs. (2024). *CSS: Cascading Style Sheets*. Mozilla. https://developer.mozilla.org/en-US/docs/Web/CSS

Meyer, E. A. (2017). *CSS: The Definitive Guide* (4th ed.). O'Reilly Media.

Nielsen, J. (2020). *10 Usability Heuristics for User Interface Design*. Nielsen Norman Group. https://www.nngroup.com/articles/ten-usability-heuristics/

W3C. (2023). *Cascading Style Sheets Level 2 Revision 2 (CSS 2.2) Specification*. World Wide Web Consortium. https://www.w3.org/TR/CSS22/

W3C. (2024). *HTML5 Specification*. World Wide Web Consortium. https://www.w3.org/TR/html5/

Krug, S. (2014). *Don't Make Me Think, Revisited: A Common Sense Approach to Web Usability* (3rd ed.). New Riders.

Lawrence, J., & Tavakol, S. (2007). *Web Design: Introductory*. Cengage Learning.

## 7. How to Run
1.  Clone or download this repository
2.  Open `index.html` in any modern web browser
3.  Ensure the `/css/style.css` file is in the correct folder for styling to apply

## 8. Author
**Student Name: Aminata Manuel/ st1052956
**Course**: Web Development - Part 1  
**Institution**: Rosebank College  
**Date**: September 2026


# Fresh Bread By IZA

A responsive, accessible website for a local artisan bakery based in Cape Town, South Africa. Built for the WEDE5020 POE.

**Live Sites:**
- Netlify: https://famous-puffpuff-bae97d.netlify.app/
- GitHub Pages: https://aminatamanuel2005-lab.github.io/Fresh-Bread-BY-IZA/

## Project Features

- **5 Core Pages:** Home (index.html), About, Menu, Enquiry, Contact
- **Responsive Design:** Flexbox & Media Queries (mobile, tablet, desktop)
- **SEO Optimized:** `robots.txt`, `sitemap.xml`, meta descriptions, semantic HTML
- **Accessibility:** ARIA labels, alt text, keyboard navigation, form validation
- **Interactive Features:**
    - Esri Leaflet Map on Contact page (interactive store location)
    - AJAX Enquiry Form with live cost calculation (R325 per catering quote)
    - Shopping cart logic with localStorage
- **Performance:** Optimized images, lazy loading, external CSS

## Folder Structure
/Fresh-Bread-BY-IZA
index.html
about.html
menu.html
enquiry.html
contact.html
styles.css
enquiry.js
robots.txt
sitemap.xml
/images (logo.png, bread images)
README.md


## How to Run Locally
1. Download / Clone the repo
2. Open `index.html` in any browser
3. No server needed - pure HTML/CSS/JS

## Changelog
- v2.0 - Added robots.txt, sitemap.xml, updated contact.html with Esri map, updated enquiry.html calculation
- v1.0 - Initial release with 5 pages

## References - FRESH BREAD BY IZA

This section lists all sources consulted for code, design and content, as required by IIE academic guidelines.

1.  **HTML & CSS Structure**
        - MDN Web Docs. (2024). HTML: HyperText Markup Language. Mozilla Developer Network. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML
        - W3Schools. (2024). HTML Forms and Input Attributes. Available at: https://www.w3schools.com/html/html_forms.asp
        - W3Schools. (2024). CSS Flexbox Layout. Available at: https://www.w3schools.com/css/css3_flexbox.asp

2.  **JavaScript & Interactivity**
        - MDN Web Docs. (2024). Using Fetch / AJAX for form handling. Available at: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
        - W3Schools. (2024). JavaScript Form Validation. Available at: https://www.w3schools.com/js/js_validation.asp

3.  **Maps & Location API**
        - Esri. (2024). Esri Leaflet - An open-source JavaScript library for Esri ArcGIS. Available at: https://developers.arcgis.com/esri-leaflet/
        - OpenStreetMap Contributors. (2024). OpenStreetMap data for Cape Town. Available at: https://www.openstreetmap.org

4.  **SEO Implementation**
        - Google Search Central. (2024). Introduction to robots.txt. Available at: https://developers.google.com/search/docs/crawling-indexing/robots/intro
        - Google Search Central. (2024). Build and submit a sitemap. Available at: https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
        - Moz. (2024). What is SEO? Search Engine Optimization Guide. Available at: https://moz.com/learn/seo/what-is-seo

5.  **Design & Images**
        - Unsplash. (2024). Royalty-free bakery images used for mockup (bakery-display.jpg, shop-interior.jpg, sourdough images). Available at: https://unsplash.com/s/photos/bakery
        - Canva. (2024). Logo design inspiration for Fresh Bread By IZA.

6.  **Deployment**
        - Netlify Docs. (2024). Deploying a static site by drag and drop. Available at: https://docs.netlify.com/site-deploys/create-deploys/
        - GitHub Docs. (2024). Configuring a publishing source for GitHub Pages. Available at: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Student Details
- Module: WEDE5020
- Project: POE - Part 2 & 3
- Student: Aminata Manuel ST10529568
