# Chuma Gqodi Portfolio Website

# Overview

This project is a responsive multi-page portfolio website that introduces me as a Junior Software Engineer. It presents my technical skills, certifications, projects and contact information. The website was developed using HTML5 and CSS3 and contains Home, About, Projects and Contact pages.

# Issues Found

After reviewing the starter code using the W3C HTML and CSS validators and manually checking all four pages, I identified the following major issues:

The pages were missing the character encoding, language attribute and viewport metadata.

The stylesheet path was incorrect.

Semantic HTML elements were missing or used incorrectly.

The four pages did not have complete navigation menus.

Five images were missing alternative text, and the images folder was incomplete.

The About page did not contain the required data table.

The Projects page contained only two of the three required projects.

The Contact form did not have labels, enough control types or HTML5 validation.

The CSS used limited selector types and did not demonstrate the box model properly.

Navigation, table and form styles were incomplete.

Hover and keyboard focus states were missing.

The footer was incorrectly aligned.

The website had inconsistent spacing and was not fully responsive.

# Fixes Implemented

I added the missing HTML metadata and corrected the stylesheet path. I replaced unnecessary generic elements with semantic elements such as header, nav, main, section and footer. I also added a consistent navigation menu to all four pages and connected every link correctly.

I created an images folder and added descriptive alternative text to the images. I added the missing third project and created a technical-skills table on the About page.

I improved the Contact form by adding labels and five different controls: text, email, select, textarea and radio. I also added HTML5 validation using attributes such as required and minlength.

# HTML Structure

Every page includes a document type, language attribute, character encoding, viewport setting, header, navigation, main content and footer. The About page contains a table using table, thead, tbody, tr, th and td. The Contact page uses accessible labels, a fieldset and a legend.

# CSS Styling

I used element, class, descendant, universal, attribute and pseudo-class selectors. Flexbox and CSS Grid were used to organise the content. The box model was demonstrated through margins, padding and borders.

The website uses a navy, blue and white colour scheme with readable contrast. Hover effects, focus states, shadows, transitions and alternating table-row colours improve the visual hierarchy. Media queries make the website responsive on desktop, tablet and mobile screens.

# Accessibility Improvements

I added descriptive alternative text to images and connected form labels to their controls. I added accessible labels to the navigation menus and used aria-current="page" to identify the current page. Keyboard focus styles and clear colour contrast make the website easier to use.

# How to View the Website

Download or clone this repository.
Open the project folder in Visual Studio Code.
Open index.html in a browser or use the Live Server extension.
Use the navigation menu to move between the four pages.
No additional packages or installation commands are required.

# Screenshots

Home Page

[Home page](screenshots/homepage.png)

About Page

[About page](screenshots/about-page.png)

Certifications

[Certifications](screenshots/certificates.png)

Projects Page

[Projects page](screenshots/projects-page.png)

Contact Page

[Contact page](screenshots/contact-page.png)

Contact Details

[Contact details](screenshots/contact-details.png)

Contact Form

[Contact form](screenshots/form.png)

Technical Skills Table

[Technical skills table](screenshots/table.png)

Navigation Hover Effect

[Navigation hover effect](screenshots/navigation-hover.png)

# Reflection

The main challenge was finding errors that were not immediately visible, especially incorrect file paths, missing accessibility features and incomplete form requirements. I solved these problems by checking each page separately, testing the navigation and form, reviewing the requirements and fixing the HTML and CSS step by step. This process helped me understand semantic HTML, accessibility, responsive layouts and code organisation better.
