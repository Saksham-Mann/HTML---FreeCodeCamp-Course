# Roaming Rucksack - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage designed for a fictional travel agency, "Roaming Rucksack," specializing in Indian tourism. It serves as an excellent practice exercise for structuring a landing page with SEO-friendly meta tags, semantic HTML5 structure, linked media, and grouped figure elements.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates several core HTML concepts:

### 1. Document Structure & SEO Basics
* **`<!DOCTYPE html>`**: Declares the document type as HTML5.
* **`<html>`**: The root element, utilizing the `lang="en"` attribute.
* **`<meta name="description" content="...">`**: A crucial new addition for Search Engine Optimization (SEO). This tag provides a brief summary of the page to search engines, which is often displayed in search results.
* **`<meta charset="UTF-8">` & `<title>`**: Standard boilerplate for character encoding and defining the browser tab title.

### 2. Semantic HTML5 Landmarks
* **`<main>`**: Wraps the core content of the page, separating it from the boilerplate `<head>` and establishing the primary focus area.
* **`<section>`**: Used to logically divide the page into two distinct parts: the introductory hero section ("Namaste India!") and the offerings/itineraries section.

### 3. Navigation & Lists
* **`<ul>` and `<li>`**: Creates an unordered, bulleted list for the travel packages.
* **`<a>` (Anchor Tag)**: Used to create hyperlinks. 
* **`target="_blank"`**: Applied to all links so that they open in a new browser tab, preventing the user from navigating away from the main landing page.

### 4. Interactive Media & Accessibility
* **Linked Images**: Demonstrates how to make an image act as a button by nesting the `<img>` tag directly inside an `<a>` tag.
* **`<img>` Attributes**: Uses `src` to pull images from external URLs, `width="300"` to uniformly constrain the image sizes inline, and `alt` to provide descriptive text for screen readers (e.g., "Havelock Island").

### 5. Grouping Elements with Figures
* **`<figure>` and `<figcaption>`**: Used extensively to semantically pair each location image with its corresponding title text. This ensures the browser, screen readers, and search engines understand that the text (e.g., "Mehrangarh Fort") directly describes the image directly above it, rather than just being a random paragraph.

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered structure and interact with the image links.