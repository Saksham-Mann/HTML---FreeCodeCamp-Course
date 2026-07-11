# Mr. Whiskers' Blog - HTML Fundamentals Practice

## Overview
This project is a static HTML blog webpage showcasing a simple layout for personal articles. It serves as a fantastic practice exercise for mastering **HTML5 semantic elements**, internal page navigation, accessible image grouping, and specialized hyperlink protocols for contact information.

## HTML Fundamentals Practiced

This code snippet heavily emphasizes using the correct tags to give meaning and structure to a document, which is vital for SEO (Search Engine Optimization) and accessibility:

### 1. Semantic Landmarks
Instead of using generic `<div>` tags, this page uses HTML5 landmarks to define the major regions of the page:
* **`<header>`**: Contains introductory content, the main title, and the navigation menu.
* **`<main>`**: Wraps the dominant, unique content of the page (the "About" and "Posts" sections).
* **`<footer>`**: Contains the closing information for the page, such as the contact details.

---

### 2. Accessible Image Grouping
* **`<figure>` and `<figcaption>`**: These tags are used together to semantically link an image (`<img>`) with its description. This tells the browser and screen readers that the caption ("Mr. Whiskers in the Garden") directly applies to the image above it, keeping them logically tethered.
* **`alt` Attribute**: The image includes `alt="a cat in the garden"`, which is crucial for visually impaired users and displays if the image fails to load.

---

### 3. Internal Page Navigation (Anchors)
* **`<nav>`**: Semantically defines a block of navigation links.
* **Unordered Lists (`<ul>`, `<li>`)**: Best practice dictates wrapping navigation links inside a list, as a menu is structurally just a list of destinations.
* **Hash Links (`href="#about"`)**: The anchor tags use a `#` followed by an ID name. When clicked, instead of taking the user to a new web page, it scrolls the browser directly to the element on the *current* page that has the matching ID (e.g., `<section id="about">`).

---

### 4. Structuring Content: `<section>` vs. `<article>`
* **`<section>`**: Used to group related, thematic content together (like the entire "About" area or the overall "Posts" list).
* **`<article>`**: Nested inside the "Posts" section, the `<article>` tag is used for content that makes sense on its own and could potentially be syndicated or shared independently (like an individual blog post). 

---

### 5. Contact Information & Special Links
* **`<address>`**: A semantic tag specifically designed to house contact information for the author or owner of the document.
* **`mailto:` Protocol**: `<a href="mailto:fake@email.com">` tells the browser to open the user's default email client (like Outlook or Apple Mail) with a new draft addressed to that email.
* **`tel:` Protocol**: `<a href="tel:5555555555">` turns the phone number into a clickable link. On mobile devices, clicking this will prompt the phone's dialer app to call the number!

---

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered blog.
3. Click the links in the top navigation menu ("About", "Posts", "Contact") to see how the internal anchor links smoothly jump you to different sections of the page!