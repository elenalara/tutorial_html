# Sunnydale School: Webpage Enhancement
## Scenario
Sunnydale School has a basic webpage that serves as an information hub for students, parents, and staff. The current page features general information about the school, including its mission, upcoming events, and contact details. While functional, the webpage lacks the interactive and visual appeal necessary to engage its audience fully. As a budding web developer, you have been approached by the school to revamp this webpage.

Your task is to apply your HTML knowledge to enhance the page's aesthetics, usability, and interactivity, making it a more inviting and informative resource for the Sunnydale community.

## Instructions
Follow the instructions below to create the webpage step by step:
1. **Enhance the Page Title**
- Within the head section of your HTML file, create a `<style>` element. This is where you will add CSS rules for styling.
- Target the `<h1>` element to modify the title's appearance. Specifically, use `font-size: 24px;`, `font-weight: bold;`, and `color: #1E90FF;` to make the title larger, bolder, and blue.
2. **Customize Fonts and Section Colors**
- In the same `<style>` element, set the body font to a friendly and readable option, such as `font-family: 'Arial', sans-serif;`.
Assign unique colors to each `<h2>` heading to differentiate the sections. Use CSS rules like `color: #32CD32;` for the _Mission Statement_, `color: #FFA07A;` for _Upcoming Events_, and `color: #20B2AA;` for _Contact Us_.
3. **Emphasize Upcoming Event Dates**
- Wrap the dates in your Upcoming Events list in `<span></span>` tags. Example: `<li>Science Fair - <span>June 10</span></li>`.
- Apply inline styles to these `<span>` tags to highlight them. Use the `style` attribute directly in the tag with rules like `font-weight: bold;` and `color: red;`.
4. **Make Contact Information Interactive**
- For the "Contact Us" section, add a `title` attribute to the email and phone number, offering a tooltip when hovered: "Click to copy email".
- While actual `onclick` behavior requires JavaScript, describe how it would work by adding a comment at the end of the "Contact Us" section: "Imagine clicking here shows a message: 'Thanks for reaching out!'".
5. **Style Specific Sections with IDs and Classes**
- Assign an `id` to the "Upcoming Events" section by adding `id="upcoming-events"` to the relevant `<h2>` tag.
- In your internal stylesheet, use this ID to style the background in the following way: `background-color: #FFFFE0;`.
- For outdoor events (_Art Exhibition_ and _Sports Day_), add the `outdoor` class to the list items, and style this class in your internal stylesheet (create a CSS rule for the `.outdoor` class) to represent outdoor activities visually: `background-color: ##AFEEEE;`, `padding: 5x;`, and `border: 1px solid #B0E0E6;`.
6. **Utilize Data Attributes for Additional Information**
- Add `data-event-type="indoor"` or `data-event-type="outdoor"` to each list item under _Upcoming Events_ respectively.
- Use the `title` attribute to display this information on hover. For example: `<li title="Event Type: Outdoor">Sports Day - June 20</li>`.
7. **Add a Box for Contact Info and Make It Look Nice**
- Group all the "Contact Us" info by wrapping it in a `<div>` tag. This makes everything inside it, like the email and phone number, sit together in one area on the page.
- Add the `section` class to the `<div>` element, and style this class in your internal stylesheet by changing the background color and adding some space around the text: `background-color: #f8f3f3;` and `padding: 10px;`.
8. **Testing and Review**
- Review your webpage to ensure that all content is properly displayed and functional.
- **Suggest Changes** – After creating the Sunnydale School webpage according to initial specifications, you realize that the result might be excessively colorful, potentially overshadowing the essential information. To address this, you propose suggestions to moderate the color scheme, aiming to cultivate a more professional and visually coherent presentation. For example:
    - Refine the Color Palette – Choose a more restrained color palette that still reflects the school's spirit but in a subtler way. Opt for complementary colors or different shades of the same color for a harmonious appearance.
    - Background and Font Colors – If you've used bright colors for the background or fonts, try softer shades that are easier on the eyes. This can help make the text more readable and the overall design more appealing.
    - Consistency in Headings – Instead of using different colors for each heading (`<h2>`), consider using the same color for all headings but vary the font weight or style (font-weight, font-style) to distinguish between sections.
- Experiment and Customize – Experiment with these design adjustments on your webpage. The goal is to balance creativity with clarity and cohesion, enhancing the user experience while staying true to Sunnydale School's identity. After making changes, revisit your testing and review process to assess the impact of your design modifications.