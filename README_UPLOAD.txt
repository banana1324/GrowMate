GrowMate minimal launch build

UPLOAD TO THE REPOSITORY ROOT:
- index.html
- about.html
- heart.html
- program.html
- apply.html
- styles.css
- site.js
- GrowMate.png
- CNAME
- robots.txt
- sitemap.xml

IMPORTANT:
1. GrowMate.png MUST be uploaded as an image file. The header uses <img src="GrowMate.png">.
2. All Apply Now buttons currently go to apply.html.
3. When the Google Form URL is ready, open apply.html and change:
   const FORM_URL = "";
   to your public Google Form URL.
4. Home page Learn More goes to the #problem section on the same page.
5. About Us has a Learn More About HEART button that goes to heart.html.
6. The parent testimonial placeholder section is removed.
7. Member Login is intentionally non-functional until the membership section is built.

DESIGN CHECKS PERFORMED:
- Rendered index, about, heart, and program at 1440px desktop width.
- Rendered all four pages at 390px mobile width.
- Fixed mobile horizontal overflow on About HEART.
- Verified no page-level horizontal overflow remains.
- Verified referenced local files exist.
- Verified no em dash characters remain in the HTML copy.
- Browser rendering produced no JavaScript page errors.
