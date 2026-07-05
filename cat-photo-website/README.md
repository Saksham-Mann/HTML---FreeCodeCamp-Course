# CatPhotoApp - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage built as a "CatPhotoApp." It serves as an excellent practice exercise for structuring web content, focusing heavily on semantic HTML5 elements, embedding media, creating hyperlinks, and organizing data into lists. 

## HTML Fundamentals Practiced

This code snippet demonstrates several core HTML concepts and best practices:

### 1. Document Structure & Boilerplate
* **`<!DOCTYPE html>`**: Declares the document type as HTML5.
* **`<html>`**: The root element, utilizing the `lang="en"` attribute to specify English for accessibility and search engines.
* **`<head>`**: Contains the meta-information (`<meta charset="UTF-8">`) and the page title (`<title>CatPhotoApp</title>`).
* **`<body>`**: Contains all the visible content of the application.

### 2. Semantic HTML5 Landmarks
Instead of using generic `<div>` tags, this code uses semantic elements that describe their meaning to both the browser and the developer:
* **`<main>`**: Wraps the dominant content of the `<body>`, indicating the core focus of the page.
* **`<section>`**: Used to group related content together (e.g., separating "Cat Photos" from "Cat Lists").
* **`<footer>`**: Represents the footer of the document, containing copyright information.

### 3. Hyperlinks & Navigation
* **`<a>` (Anchor Tag)**: Used to create links to external web pages.
* **`href` Attribute**: Specifies the destination URL.
* **`target="_blank"`**: Used on the second link to instruct the browser to open the destination in a new tab or window.
* **Image Links**: Demonstrates wrapping an `<img>` tag inside an `<a>` tag to make the image itself clickable (linking to the gallery).

### 4. Media Elements & Accessibility
* **`<img>` (Image Tag)**: Embeds images into the page using the `src` attribute.
* **`alt` Attribute**: Provides alternative text for screen readers (accessibility) and displays if the image fails to load. This is a crucial best practice demonstrated throughout the code.
* **`<figure>` and `<figcaption>`**: Semantically pairs an image with its specific caption, grouping them as a single self-contained unit.

### 5. Lists
* **`<ul>` (Unordered List)**: Creates a bulleted list for items where order doesn't matter (Things cats love).
* **`<ol>` (Ordered List)**: Creates a numbered list for items where sequence is important (Top 3 things cats hate).
* **`<li>` (List Item)**: Used inside both `<ul>` and `<ol>` to define individual items.

### 6. Semantic Text Formatting
* **Headings (`<h1>`, `<h2>`, `<h3>`)**: Establishes a clear hierarchical outline for the page content.
* **`<em>` (Emphasis)**: Used to semantically emphasize text (renders as italicized "love").
* **`<strong>` (Strong Importance)**: Used to semantically indicate high importance (renders as bolded "hate").

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered structure and test the interactive links.