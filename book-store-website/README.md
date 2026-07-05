# XYZ Bookstore - HTML Fundamentals Practice

## Overview
This project is a simple, static HTML webpage that simulates a basic storefront for "XYZ Bookstore." It serves as a foundational exercise in structuring web content using standard HTML5 tags, grouping elements, and utilizing global attributes for future CSS styling and JavaScript interactivity.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates several core HTML concepts:

### 1. Document Structure & Boilerplate
* **`<!DOCTYPE html>`**: Declares the document type as HTML5, ensuring the browser renders the page in standards mode.
* **`<html>`**: The root element that wraps all the content on the entire page. The `lang="en"` attribute specifies the language of the document for accessibility and search engines.
* **`<head>`**: Contains meta-information about the document that isn't displayed directly on the webpage.
* **`<body>`**: Contains all the visible content of the webpage (headings, paragraphs, buttons, etc.).

### 2. Meta Tags & Configuration
* **`<meta charset="UTF-8" />`**: Sets the character encoding to UTF-8, ensuring that almost all characters and symbols display correctly.
* **`<title>`**: Defines the title of the document ("XYZ Bookstore Page"), which appears in the browser tab.

### 3. Semantic Text Elements
* **Headings (`<h1>`, `<h2>`)**: Used to create a hierarchical structure. `<h1>` is used for the main page title, while `<h2>` is used for individual book titles.
* **Paragraphs (`<p>`)**: Used for blocks of text, such as descriptions of the books and general store messaging.

### 4. Element Grouping & Layout
* **`<div>` (Division)**: Acts as a generic container for flow content. The code uses `<div>` tags to group related elements together logically:
  * Wrapping all book cards (`<div class="card-container">`).
  * Wrapping individual book details (`<div class="card">`).
  * Grouping the checkout buttons (`<div class="btn-container">`).

### 5. Interactive Elements
* **`<button>`**: Represents a clickable button, used here for "Buy Now", "View Cart", and "Checkout" actions.

### 6. Global Attributes (Identifiers)
* **`class` Attribute**: Used to assign a non-unique identifier to elements (e.g., `card-container`, `card`, `btn`). This is foundational for applying reusable CSS styles to multiple elements at once.
* **`id` Attribute**: Used to assign a unique identifier to an element (e.g., `sally-adventure-book`, `view-cart-btn`). This is crucial for targeting a specific element with CSS or manipulating it with JavaScript.

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered structure.