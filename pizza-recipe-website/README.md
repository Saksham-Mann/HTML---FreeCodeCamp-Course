# Pizza Recipe - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage that displays a simple, appetizing recipe for making pizza. It serves as a practical exercise in structuring a classic recipe layout, utilizing semantic HTML5 landmarks, embedding external imagery with specific sizing, and combining text formatting with ordered and unordered lists.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates several core HTML concepts:

### 1. Document Structure & Boilerplate
* **`<!DOCTYPE html>`**: Declares the document type as HTML5, ensuring modern browser rendering.
* **`<html>`**: The root element that wraps all the content, utilizing the `lang="en"` attribute.
* **`<head>`**: Contains the document's meta-information (`<meta charset="UTF-8">`) and the page title (`<title>How to make Pizza!</title>`).
* **`<body>`**: Contains all the visible content of the recipe page.

### 2. Semantic HTML5 Landmarks
* **`<main>`**: Wraps the dominant content of the document (the recipe itself), signaling to screen readers and search engines where the primary information lives.
* **`<section>`**: Used to logically group the "Ingredients" and "Instructions" into distinct thematic blocks.
* **`<footer>`**: Represents the footer of the document, containing a sign-off message.

### 3. Media Elements & Attributes
* **`<img>` (Image Tag)**: Embeds a photo of the pizza using a URL in the `src` attribute.
* **`alt` Attribute**: Provides alternative text ("Authentic Italian cheese pizza") for screen readers and acts as a fallback if the image link breaks.
* **`width` Attribute**: Demonstrates inline sizing (`width="300"`) directly within the HTML to scale the image proportionally.

### 4. Structuring Data with Lists
* **`<ul>` (Unordered List)**: Used for the "Ingredients" section, as the order in which ingredients are gathered does not strictly matter. Renders with bullet points.
* **`<ol>` (Ordered List)**: Used for the "Instructions" section, as the steps must be followed in a specific, sequential order. Renders with numbers.
* **`<li>` (List Item)**: Defines each individual ingredient and step within the lists.

### 5. Semantic Text Formatting & Entities
* **Headings (`<h1>`, `<h2>`)**: Establishes the visual and structural hierarchy of the page.
* **`<strong>` (Strong Importance)**: Used to bold and semantically highlight the key components of each list item (e.g., **Dough**, **Preheat**).
* **`<em>` (Emphasis)**: Used to emphasize text in the footer (renders as italicized *LOVE*).
* **HTML Entities (`&lt;`)**: Demonstrates how to display special characters on a webpage. `&lt;` is used to safely display the less-than sign (`<`) to make a text heart (`<3`) without the browser confusing it for the start of an HTML tag.

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered recipe layout.