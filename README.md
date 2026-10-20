# Fresh Bread By IZA - Website Project

## 1. Project Overview
This website was developed for **Fresh Bread By IZA**, an artisan bakery located in Observatory, Cape Town. The goal of the website is to provide customers with information about business hours, menu, location, and a contact form for enquiries and orders.

The site consists of 5 main pages: Home, About, Menu, Enquiry, and Contact. All pages follow a consistent navigation and layout structure as required for Part 1 of the Web Development assignment.

## 2. Site Structure
The website includes the following 5 HTML pages:

| Page | File Name | Purpose |
| --- | --- | --- |
| Home | `index.html` | Welcome message and summary of bakery services |
| About | `about.html` | History, mission and values + FAQ Accordion (Part 3) |
| Menu | `menu.html` | List of artisan breads with prices + Search + Lightbox + Cart (Part 3) |
| Enquiry | `enquiry.html` | Contact form for orders, catering and general questions |
| Contact | `contact.html` | Business hours, baking times, address, map, and contact details |

Additional folders:
- `/css` - Contains `style.css` for site styling
- `/CONTENT-RESEARCH` - Contains text files with all site content
- `/IMAGES` - Contains images used on the website

## 3. Technologies Used
- **HTML5**: For semantic structure of the website. Used elements like `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` as per W3C standards.
- **CSS3**: For styling, layout, and responsive design. External stylesheet linked to all pages.
- **JavaScript (ES6)**: For dynamic features - Search Filter, Lightbox Gallery, Accordion FAQ, Shopping Cart with localStorage.
- **Git & GitHub**: For version control and project submission.

## 4. Design Principles & Academic References
1.  **Usability**: The navigation is consistent across all 5 pages to reduce cognitive load. This follows Nielsen's 10 Usability Heuristics【Nielsen, 2020】.
2.  **Semantic HTML**: Proper use of semantic tags improves accessibility and SEO【W3C, 2024】.
3.  **User-Centered Design**: Content is organized based on user needs【Garrett, 2011】.

## 5. Project Features (Part 2 & 3)

- **5 Core Pages:** Home, About, Menu, Enquiry, Contact
- **Responsive Design:** Flexbox & Media Queries (mobile, tablet, desktop)
- **SEO Optimized:** `robots.txt`, `sitemap.xml`, meta descriptions, semantic HTML, image alt-text and file naming (Part 3 Requirement)
- **Accessibility:** ARIA labels, alt text, keyboard navigation, form validation
- **Interactive Features (Part 3):**
    - **Search Functionality:** Dynamic search filter on menu.html - filters breads instantly by name (data-name attribute)
    - **Lightbox Gallery:** Click image to enlarge in modal overlay - improves product viewing
    - **Accordion FAQ:** Interactive FAQ on about.html using DOM manipulation - click to expand/collapse
    - **Esri Leaflet Map** on Contact page
    - **AJAX Enquiry Form** with live cost calculation (R325 per catering quote)
    - **Shopping cart** logic with localStorage and WhatsApp checkout

## 6. Changelog

### v3.0 - Part 3 Implementation (2026-05-13)
- **ADDED:** Search functionality on menu.html - JavaScript filter using input event listener and data-name attributes. Allows users to search "sourdough", "baguette", etc.
- **ADDED:** Lightbox Gallery on menu.html - onclick="openLightbox(this.src)" enlarges bread images in fixed overlay modal. Includes close on click.
- **ADDED:** Accordion FAQ on about.html - Interactive accordion with 3 FAQs (flour, opening hours, catering). Uses querySelectorAll and class toggling for DOM manipulation.
- **IMPROVED:** SEO - Updated all image alt-text with descriptive keywords (e.g., "Fresh artisan sourdough bread loaf 750g baked daily Cape Town")
- **IMPROVED:** File naming - Verified all images use SEO-friendly names
- **Feedback Changes Implemented:** Added user-requested interactive elements to improve UX based on Part 2 feedback

### v2.0 - Part 2 Implementation
- Added robots.txt, sitemap.xml, updated contact.html with Esri map, updated enquiry.html calculation

### v1.0 - Initial release with 5 pages

## 7. How to Run
1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Ensure the `styles.css` file is in the correct folder

## 8. References

Duckett, J. (2014). *HTML and CSS: Design and Build Websites*. John Wiley & Sons.
Garrett, J. J. (2011). *The Elements of User Experience*.
Meyer, E. A. (2017). *CSS: The Definitive Guide*.
Nielsen, J. (2020). *10 Usability Heuristics*. Nielsen Norman Group.
W3C. (2024). *HTML5 Specification*.

### Code References for Part 3
- MDN Web Docs. (2024). *Element.querySelectorAll() and input event*. https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll
- W3Schools. (2024). *How TO - Lightbox*. https://www.w3schools.com/howto/howto_js_lightbox.asp
- W3Schools. (2024). *How TO - Accordion*. https://www.w3schools.com/howto/howto_js_accordion.asp
- Google Search Central. (2024). *Image SEO - alt text best practices*. https://developers.google.com/search/docs/crawling-indexing/images

## 9. Author
**Student Name:** Aminata Manuel / st10529568
**Course:** WEDE5020 - Web Development POE Part 3
**Institution:** Rosebank College
**Date:** 13 May 2026
**Live Sites:**
- Netlify: https://famous-puffpuff-bae97d.netlify.app/
- GitHub Pages: https://aminatamanuel2005-lab.github.io/Fresh-Bread-BY-IZA/
