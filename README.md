# TM_Digitalmarketing


1. Introduction
TM Digital Tech is a modern, responsive static website designed to serve as the online presence for a digital marketing agency. It effectively showcases the company's brand, services, and expertise to attract potential clients. The website is structured to provide a clear and engaging user experience, detailing the company's story, vision, and a comprehensive list of its service offerings.

2. Project Overview
The primary objective of this project is to create a professional and informative web presence that generates leads for the TM Digital Tech agency. The website is built to highlight the company's core competencies in web development, SEO, and digital marketing. It features a clean design, smooth animations, and a functional contact system to capture user inquiries.

2.1 Target Audience
Businesses and startups looking to build or improve their online presence.

Companies in need of branding, web development, SEO, and social media marketing services.

Potential clients seeking a creative and results-driven digital marketing partner in India, particularly in Madurai.

3. Technologies & Tools Used
The project leverages a combination of standard frontend and backend technologies to deliver a dynamic and interactive user experience.

Frontend:

HTML5: Used for the structure and semantic markup of all web pages.

CSS3: Used for custom styling, layout, responsiveness, and animations.

Bootstrap v5.3.3: A major CSS framework used for the grid system, responsive design, and pre-styled components like the navbar and modals.

JavaScript (AOS Library): The "Animate On Scroll" (AOS) library is used to trigger animations as the user scrolls down the page, enhancing user engagement.

Google Fonts & Font Awesome: Used for custom typography and icons throughout the website.

Backend:

PHP: A server-side scripting language used to process the contact form submission. It handles connecting to the database and inserting user data.

MySQL: The relational database used to store messages received from the contact form. The script connects to a database named contactus and a table named customer_feedback.

4. Key Features & Flows
4.1 Interactive Frontend
Responsive Design: The layout is fully responsive and adapts to various screen sizes, from mobile phones to desktops, ensuring a consistent user experience.

Scroll Animations: Elements fade in, zoom, and slide up as the user scrolls, guided by the AOS.js library, making the site feel dynamic and modern.

Expandable Service Details: On the Services page, each service card features a "View More" button that expands a hidden section with more details. This is achieved purely with CSS using a checkbox and the :checked pseudo-selector, avoiding the need for JavaScript.

Support Modals: The Contact Us page includes a "Help & Support" section where clicking on cards for Feedback, FAQ, or Terms & Conditions opens a Bootstrap modal window with the relevant information.

4.2 Contact Form Backend Flow
The contact form provides a direct line for lead generation and is a key functional component of the site.

A user fills out the Name, Phone, Email, and Message fields on the contact.html page and clicks "Submit".

The form data is sent via the POST method to the contact.php script on the server.

The PHP script receives the data and establishes a connection to a local MySQL database with the credentials ('localhost','root','','contactus').

It executes an SQL INSERT query to store the user's details in the customer_feedback table.

Upon successful insertion, the script returns a JavaScript alert to the user: "Thank you for contacting us. We will get back to you shortly.".

If the query fails, an error alert is shown: "There was an error submitting your message. Please try again later.".

In both cases, the user is then redirected back to the home.html page.

5. Page Structure
The website is composed of four main pages, each serving a distinct purpose.

Home Page (home.html):

Hero Section: Features a main headline, a descriptive paragraph, and a call-to-action button linking to the services page.

Why Choose Us: A section with three cards highlighting the company's strengths: Expert Team, Innovative Solutions, and Proven Growth.

Vision & Mission: Two distinct sections that detail the company's long-term goals and strategic objectives.

Footer: A consistent footer used across all pages, containing contact info, quick links, and social media icons.

About Us Page (about.html):

Banner: A full-width header image with an overlay and the page title.

Company Information: Sections dedicated to "About Our Company," "Our Story," "Who We Are," and "What We Do," providing a deep dive into the agency's background and expertise.

Services Page (services.html):

Hero Banner: A large banner displaying the page title and a subtitle.

Services Grid: A grid layout of service cards for Digital Marketing, Web Development, SEO, Graphic Design, UI/UX, and Content Writing. Each card is interactive with an expandable details section.

Call-to-Action Banner: A banner at the bottom of the page encouraging users to get in touch.

Contact Us Page (contact.html):

Banner: A header image with the title "Get in Touch".

Contact Section: A two-column layout displaying contact details (Phone, Email, Address) on one side and the functional contact form on the other.

Help & Support: An interactive section with clickable cards that launch modals for Feedback, FAQ, and Terms & Conditions.

6. Conclusion
The TM Digital Tech website is a well-rounded and functional project that successfully serves its purpose as a digital brochure and lead-generation tool. It combines a clean, modern frontend design with a simple yet effective backend for data capture, making it a complete solution for a small digital agency's online presence.
