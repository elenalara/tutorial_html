# Harbor Light Community Center Website: Adding Accessibility and Structured Data
## Scenario
The local community center, "Harbor Light Community Center," currently has a basic website that provides information about its services, events, and educational programs. While the website is functional, it lacks semantic structure, accessibility features, and modern web practices that could enhance user experience and accessibility. You, as an aspiring web developer, have volunteered to revamp the website.

Your goal is to apply your understanding of semantic markup, accessibility, and HTML best practices to make the website more informative, accessible, and user-friendly for everyone in the community.

## Instructions
Follow the instructions below to create the webpage step by step:
1. **Semantic HTML Implementation**
- Convert the first `<div>` that includes the community center's logo and welcome message into a `<header>` element.
- Transform the second `<div>` with textual navigation into a `<nav>` element containing a list (`<ul>`) of navigation links (`<li>` with `<a>` tags). Assign href attributes to these links for in-page navigation.
2. **Main Content Structure**
- Enclose the content starting from "About Us" to "Join Our Events" in a `<main>` element for the primary content area.
- For each major section ("About Us", "Our Services", "Join Our Events"), replace the `<div>` with a `<section>` element and ensure the use of appropriate headings (`<h2>` instead of `<h1>` for section titles to maintain hierarchy).
- Ensure the event listed in the "Join Our Events" section ("Annual Summer Festival") is enclosed with the `<p>` tag. Separate the name of the event and the time it takes place with a line break. Add importance to the event name using the `<strong>` tag.
3. **Optimizing Events SEO with Schema.org**
- For the event's start date, enclose the date within a `<time>` element, ensuring to use the datetime attribute for specifying the machine-readable date format.
- Implement Schema.org's Event microdata in this section for better SEO and structure, wrapping the event details. Start with a `<section>` element attributed with itemscope and `itemtype="http://schema.org/Event"`. Make sure that the description and start date of the event are marked up with `itemprop="description"` and `itemprop="startDate"`, respectively.
4. **Contact Section and Footer**
- Convert the last `<div>` into a `<footer>` element.
- Add an actual email link using *info@harborlight.com* and the `mailto` protocol in the "Contact Us" section for direct email communication.
- Add a paragraph at the end of the `<footer>` to include the copyright symbol followed by the year and the organization's name: "© 2050 Harbor Light Community Center".
5. **Accessibility Enhancements**
- Apply descriptive `alt` attributes to the *logo.jpg* and *community-center.jpg* images ("Harbor Light Community Center Logo" and "Harbor Light Community Center People" respectively).
- Add the `navigation` ARIA role to the navigation for better accessibility.
- For the decorative banner added to the website, ensure it's correctly marked to be ignored by screen readers to enhance accessibility – apply the `aria-hidden="true"` attribute to the `<img>` tag of the decorative banner. Ensure the `alt` attribute is set to an empty string (`alt=""`) to reinforce that this image does not convey essential information.
6. **Adding Anchor Links for Navigation**
- Assign unique IDs to each section (`id="about"`, `id="services"`, `id="events"`, and `id="contact"`) corresponding to the navigation links.
- Add anchor links by updating the `<nav>` links to point to these IDs, enabling smooth scrolling to each section.
7. **Replace Deprecated Tag and Introduce CSS**
- Locate and remove the deprecated `<font>` tag. In the `<head>` section of your HTML, add an internal stylesheet (`<style>` element). Within this stylesheet, set the font style for the `<body>` element to ensure all text inherits this style, effectively replacing the visual effect previously applied with the `<font>` tag.
- Remove the deprecated `<center>` tag and apply CSS for centering and spacing:
    - Wrap the webpage image logo element in a `<div>` container.
    - In the `<style>` block of the `<head>` section, define a class named `.center-and-space-content`. The class should center the content horizontally within its `<div>` container (use the `text-align: center;` property) and introduce padding for both vertical and horizontal spacing (use the `padding: 10px;` property), enhancing the visual layout.
8. **Testing and Review**
- Validate the HTML to ensure it meets web standards.
- Test for accessibility, ensuring all content is accessible and navigable.
- Experiment, experiment, experiment!