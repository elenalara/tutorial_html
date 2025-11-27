# World Discovery Web Page
## Scenario
You are part of a collaborative project aiming to create an interactive web page titled "Discover Your World". This page is designed to educate users about different continents and their unique geographical features through a fun and engaging interactive map. You've been tasked with setting up the HTML structure and ensuring that the page is visually appealing and functional. Another developer from your team will handle the JavaScript functionality, providing scripts for geolocation features and interactions with the map.

As the front-end developer, your job is to prepare the groundwork for this interactive experience. You will:

- Add a Favicon – ensure the web page stands out with a globe-themed favicon to match the world discovery theme.
- Embellish with Emojis – make the header more inviting by incorporating a globe emoji.
- Prepare for Geolocation – insert a button that will later be linked to geolocation functionality, allowing users to discover which continent they're currently on based on their physical location.
- Create an Interactive Map – using an image of the world map, define clickable areas corresponding to each continent. This map will later be scripted to display information about each continent, such as major rivers, mountains, and landmarks.

Once your tasks are completed, the web page will display a beautiful world map, inviting users to click on a continent to learn more about it. The geolocation button will enhance the interactive experience by providing users with personalized information based on their location. This project, when combined with the JavaScript functionality provided by your teammate, will offer an educational and engaging way to learn about our world.

Remember, the JavaScript functionality, including handling clicks on the map areas and implementing the geolocation feature, will be provided by another developer on your team. Your focus is on setting up the HTML structure and ensuring the page is ready for those interactive elements to be integrated.

## Instructions
Follow the instructions below to create the webpage step by step:
1. **Favicon Addition**
- Start by adding a globe favicon to the page to give it a distinctive appearance in browser tabs, drawing users into the global theme immediately. Use the _web-favicon.png_ file as your favicon. In the `<head>` section of your HTML document, use the `<link>` tag to link to your favicon file. Use the `rel` attribute with the value "icon" and the `href` attribute to specify the path to your favicon file: "/resources/media/web-favicon.png".
2. **Link to an External JavaScript File**
- Prepare for dynamic interactions by linking an external JavaScript file. This script will handle user interactions and display continent-specific information. In the `<head>` section or just before the closing tag of your HTML document, add a `<script>` tag with the `src` attribute pointing to the location of your _script.js_ file: "script.js".
3. **Add an Emoji to Your Heading**
- Add a globe emoji to the page title to emphasize the world exploration theme. Insert the emoji with the codepoint code point U+1F30D directly into the HTML content of your `<h1>` tag. Remember, to specify this emoji in HTML using the codepoint, you need to replace the "U+1" part with the characters "&#x".
- Go to [Unicode.org/emoji/charts](https://unicode.org/emoji/charts/full-emoji-list.html), choose an emoji that fits the theme of the page, and insert it somewhere into your HTML code.
4. **Add a Button for Displaying Geolocation Information**
- Implement a feature that allows users to find out which continent they are currently on. Below the paragraph tag, add a `<button>` that, when clicked, uses the Geolocation API to display the user's current continent along with interesting geographical facts..
- Give the button an `id` attribute with the value `getLocation`, and set its text content to something descriptive, like "Discover Location".
5. **Define the Continent Areas on Your World Map Image**
- Enhance the page with an image map of the world. Users should be able to click on different continents to learn about key geographical features. For each continent on your world map, add an `<area>` tag within the `<map>` tag.
- Use the following attributes to define each continent area:
    - `alt` and `title` for "North America", "South America", "Europe", "Africa", "Asia", and "Australia and Oceania"
    - `id` for "north-america", "south-america", "europe", "africa", "asia", and "australia-and-oceania"
    - `shape` – "rect" for each of the areas
- The `coords` attribute values will depend on the specific areas of your image map. Use an image map generator or manually determine the coordinates. Alternatively, use the following values: "386,283,41,17" (North America), "209,501,358,288" (South America), "391,68,505,217" (Europe), "533,217,387,448" (Africa), "893,153,506,1" (Asia), and "679,353,872,480" (Australia and Oceania).
6. **Test and Review**
- Validate the HTML to ensure it meets web standards.
- Experiment, experiment, experiment!