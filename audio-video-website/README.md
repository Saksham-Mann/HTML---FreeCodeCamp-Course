Markdown
# HTML Audio and Video Lab - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage designed to demonstrate how to natively embed multimedia content. It serves as a practical exercise for understanding the structure and attributes of HTML5 `<audio>` and `<video>` elements, as well as reinforcing basic page structure and semantic grouping.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates several core HTML concepts focused on media embedding and page semantics:

### 1. Semantic Structure
* **`<main>`**: Acts as the primary container for the dominant content of the `<body>`, signaling to screen readers and search engines where the core material is located.
* **`<section>`**: Used to logically divide the page into distinct thematic blocks (one for the video player, one for the audio player), each appropriately introduced by an `<h2>` heading.

---

### 2. The `<video>` Element
* **`<video>`**: The standard HTML5 container for embedding video content without relying on third-party plugins.
* **`width="640"`**: Explicitly sets the display width of the video player in pixels.
* **`controls`**: A crucial boolean attribute that tells the browser to display its native user interface for the video (play/pause button, volume slider, timeline, fullscreen toggle).
* **`<source>`**: Nested inside the `<video>` tag, this defines the media file's location (`src`) and its MIME type (`type="video/mp4"`). Using `<source>` is best practice because it allows developers to provide multiple alternative formats (like `.webm` or `.ogg`) as fallbacks, though only one is used here. *(Note: The code contains a small typo with a duplicate `type="video/mp4"`, but the browser will safely ignore the repetition).*

---

### 3. The `<audio>` Element
* **`<audio>`**: The standard HTML5 container for embedding sound, music, or podcasts.
* **`src` Attribute**: In this section, the media source file is declared directly on the `<audio>` tag itself. This is a valid, simpler alternative to using the nested `<source>` tag when only providing one file format.
* **`controls`**: Just like with the video element, this adds the browser's default play, pause, and volume controls for the audio track so the user can interact with it.
* **`loop`**: A boolean attribute that tells the browser to automatically restart the audio file from the beginning once it reaches the end, playing it on an infinite loop.

---

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered page.
3. Test the media players by clicking the "Play" buttons on both the video and audio sections, and observe how the audio track automatically loops when it finishes!