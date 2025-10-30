# Harmony Heights: The Official Band Page
## Scenario
You've been approached by "Harmony Heights," an emerging band known for their eclectic mix of genres and compelling live performances. As they prepare to broaden their audience and establish a stronger online presence, they need a dynamic and engaging official webpage. This page will serve as a central hub for fans to explore the band's music, learn about band members, view upcoming show dates, and connect with the band.

Your task is to craft a webpage that reflects the band's vibrant personality and musical diversity, incorporating multimedia elements such as images, music samples, videos of performances, and a contact form for booking inquiries or fan messages.

## Instructions
Follow the instructions below to create the webpage step by step:
1. **Initial Setup**
- Start by creating a new HTML file named _harmony-heights.html_.
- Use the HTML5 doctype and include the basic HTML structure (`<html>`, `<head>`, `<body>` tags)
- Specify the language as English using the lang attribute.
2. **Head Section**
- Title the webpage "Harmony Heights: Feel the Music".
- Add meta tags for a brief description of the band (set the _content_ attribute to "Official webpage of Harmony Heights, featuring our latest music, tour dates, and exclusive content for our fans.") and set the _charset_ to UTF-8.
3. **Body Section: Band Introduction**
- Introduce the band with an `<h1>` tag ("Welcome to Harmony Heights"), followed by a captivating paragraph about their musical journey: "We are Harmony Heights, a band that blends genres to create unique sounds. Our journey through music has been incredible, and we're excited to share it with you."
- Include professional photos of the band and individual members using the `<img>` tag, emphasizing the importance of the alt attribute for accessibility:
    - The first photo – source: "/resources/media/band-photo.jpg", alt text: "Harmony Heights Band Photo".
    - The second photo – source: "/resources/media/member1-amy.jpg", alt text: "Harmony Heights Vocals/Sampling: Amy Duncan".
    - The third photo – source: "/resources/media/member2-john.jpg", alt text: "Harmony Heights Bass/Guitars: John Smith".
    - The fourth photo – source: "/resources/media/member3-trevor.jpg", alt text "Harmony Heights Drums: Trevor G.".
4. **Music and Video Showcases**
- **Audio**
    - Add an `<h2>` element with the following content: "Listen to Our Latest Tracks". Feature a selection of the band's latest tracks using the `<audio>` tag, allowing fans to listen directly from the site. Include the _controls_ attribute.
    - Set the _src_ attribute of the `<source>` tag to the path of the audio file: "/resources/media/track1.mp3". Then, set the _type_ attribute to "audio/mpeg". If the browser does not support the `<audio>` tag, the following text should be displayed: "Your browser does not support the audio element."
- **Video**
    - Add an `<h2>` element with the following content: "Watch Our Performances". Embed a video of live performances or music videos using the `<video>` tag, showcasing the band's stage presence and engagement with their audience. Include the controls attribute.
    - Set the _src_ attribute of the `<source>` tag to the path of the audio file: "/resources/media/performance1.mp4". Then, set the _type_ attribute to "video/mp4". If the browser does not support the `<video>` tag, the following text should be displayed: "Your browser does not support the video element."
5. **Tour Dates and Brand News**
- Add an `<h2>` element with the following content: "Upcoming Tour Dates". Then, create an unordered list to display upcoming tour dates and locations:
    - The first listed item – "March 12, 2029, Orlando, FL", with the URL of the ticket purchasing website "https://example.com/purchase-tickets-harmony-heights-orlando", and the link text "Get Tickets".
    - The second listed item – "March 14, 2029, Salt Lake City, UT", with the URL of the ticket purchasing website "https://example.com/purchase-tickets-harmony-heights-slc", and the link text "Get Tickets".
- Include the _target_ attribute within the `<a>` tag, and assign the appropriate value to it, which instructs the browser to open the link in a new tab or window.
6. **Connect with the Band**
- Add an `<h2>` element with the following content: "Follow Us". Underneath, create a paragraph to provide a short message: "Stay updated with our latest news and releases:".
- **Insert Social Media Links** – create a section for fans to follow the band on social media, using hyperlinks to direct users to the band's official social media pages:
    - Link to the band's Faceblock profile ("https://www.example.com/faceblock/hh"). Between the opening and closing tags, place the text "Faceblock". After the Faceblock link, add a line break to ensure the next link appears on a new line.
    - Repeat this process for the band's Instagrump and Twotter profiles, adjusting the URLs and link texts accordingly. For Instagrump, use "https://www.example.com/instagrump/hh", and for Twotter use "https://www.example.com/twotter/hh".
7. **Create a Contact Form**
- Implement a simple contact form at the bottom of the page for fans to send messages to the band or inquire about booking. The form should include fields for the user's name, email, subject, and message, along with a submit button. Begin by introducing the contact section – use an `<h2>` tag to create a heading, and inside the `<h2>` tags, insert the text "Contact Us".
- Directly below the heading, initiate a form by adding the `<form>` tag, and create input fields for user information:
    - **Name Field** – begin with a `<label>` tag for the user's name. Use the _for_ attribute with a value of "name" to associate the label with the input field. Inside the `<label>` tags, type "Name:". Insert a line break to ensure the input field appears on a new line. Then, add an `<input>` tag for the name input field. Set the _type_ attribute to "text", the _id_ to "name", and the _name_ to "name" as well. Follow the input field with another line break.
    - **Email Field** – repeat the label and input field process for the email address. Use a `<label>` with _for="email"_ and type "Email:" inside. Use an `<input>` tag for the email input field, setting _type_ to "email", _id_ to "email", and _name_ to "email". Add line breaks for spacing.
    - **Subject Field** – for the subject of the message, again use a `<label>` tag with _for="subject"_ and include "Subject:" as the label text. Create an `<input>` field for the subject, setting _type_ to "text", _id_ to "subject", and _name_ to "subject". Add line braks for spacing.
- **Add a Textarea for the Message** – use a `<label>` tag for the message area, with _for="message"_, and type "Message:" as the label text. After the label, insert a line break. Introduce a `<textarea>` tag for the message input, assigning _id_ to "message" and _name_ to "message". Place another line break tag for spacing.
- **Include a Submit Button** – add an `<input>` tag and set _type_ to "submit" and _value_ to "Send". Close the `<form>` tag.
8. **Testing and Review**
- Review your webpage to ensure that all multimedia content is properly displayed and functional.
- Experiment and Customize – Feel free to explore further by integrating more content or features to enrich your webpage according to your preferences.