#Responsive Portfolio Assignment

##Purpose of page

The assignment was to create a personal portfolio website using responsive design via Bootstrap. All styling was implemented via Bootstrap classes rather then a local style sheet. This is subject to change with future updates.

##Contributors

This was a solo project coded by myself (Daniel Boren). Additional royalty free images were sourced from unsplash.com.

##Index page

Primary content is a photograph of myself and a brief introductory statement. These two elements were arranged into their own columns within a row on the bootstrap grid, for the purpose of displaying side-by-side on large enough screens, but with the intro text moving beneath the photo on smaller displays.

A header and footer were added to this page and repeated identically for the portfolio and contact pages (aside from changing the page titles within). Both use Bootstrap bg and border classes to apply red background and yellow border, and text classes to apply white text. The footer has also has an offset class in order to better line up with the rest of the page elements.

The header consists of an h1 element for page titles and a navbar made using a horizontally displaying unordered list element. Both are in P-2 class divs nested within a d-flex classed div, which also has the Bootstrap class "justify-content-between" for the purpose of keeping the title and navbar inline with each other while displaying at opposite horizontal ends of the browser on large enough displays.

![Index Screencap](Assets/Images/IndexScreencap.jpg)

##Portfolio page

As I am still at an early stage of this course and do not have real projects to my name thus far, this page is essentially just a visual mockup at this time. Each "project" is arranged within its own row, with a column for the placeholder image and a column for the associated text. All images were assigned the "img-fluid" class to allow for responsive sizing, both to fit within their rows and to resize according to browser window size.

As build my portfolio, the current mockup seen here will be replaced with my actual projects. Placeholder images will be replaced with screenshots and the placeholder text will have descriptive information and links.

![Portfolio Screencap](Assets/Images/PortfolioScreencap.jpg)

##Contact page

This page is comparatively simple, just containing my contact info, including LinkedIn and GitHub profiles. Offset classes were added to the text elements to line them up with the other page elements.

![Contact Screencap](Assets/Images/ContactScreencap.jpg)