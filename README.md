# Module 1 Horiseon Website Project
## Description:

This project was cloned from: https://github.com/coding-boot-camp/urban-octo-telegram 

For this project, I was instructed to design the website to improve accessibility and refactor related code; from Canvas Module 1 description: "…make sure that all links are functioning correctly. Also, rework the CSS to make it more efficient by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page." My goal is to address the above points, along with proper deployment, and application and repo quality. 

To start, I added the company name as the title instead of "website." Next, I added alt= to all images; this allows me to add a description to each for better accessibility (following https://accessibility.huit.harvard.edu/describe-content-images). To make the background image more accessible re a description, I added img and alt text in the html and linked css accordingly (https://stackoverflow.com/questions/872389/html-img-tag-title-attribute-vs-alt-attribute). 

Next, I replaced div with header for better semantics in the respective section. This was done for descriptive purposes, along with better accessibility: https://www.w3schools.com/html/html5_semantic_elements.asp Similarly, I replaced div with footer for the same purpose(s). Also, all div was replaced with section where deemed appropriate, such that no div exists in the code at all. 

Then, I consolidated the navigation items in css to use one class (nav-item), rather than multiple reductant code, and changed respective html class names. Similarly, I consolidated the benefit items in css and changed respective class names in html (benefit) to remove redundant code. 

Next, I added id="search-engine-optimization" for clickability and linking to the respective area on the website, similar to other links on the page.

After scanning the html some more, I changed div to nav in the header section. Ultimately, I decided to keep this within the header code, as it is meant to be located there on the website. Also, while inspecting with devtools, I noticed the sidebar had a low/red accessibility score, so I changed the background color to the same blue #0072bb as the main section. 

Throughout this entire process, I added relevant comments in both the html and css; these comments act as snippets of the general outline of the content herein. Moreover, in css, I took the appropriate action to compile related code in respective sections and notated each (header, body, nav bar, footer) ultimately organizing them to follow the semantic structure of the HTML elements. 

## Link:

Link to deployed application: https://mslzbry.github.io/module-1-horiseon/

## Screenshot:

![Alt text](assets/images/salisbury_module1.png "screenshot")

Further references for this project: https://en.wikipedia.org/wiki/Agile_software_development