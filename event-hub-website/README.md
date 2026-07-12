# Event Hub - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage built for a fictional event management organization, "Event Hub." It serves as a practical exercise in advanced document structuring, focusing specifically on semantic HTML5 layout elements and building in-page navigation using anchor links.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates several core HTML concepts:

### 1. Document Structure & Boilerplate
* **`<!DOCTYPE html>`**: Declares the document type as HTML5.
* **`<html>`**: The root element, utilizing the `lang="en"` attribute.
* **`<head>`**: Contains the document's meta-information (`<meta charset="utf-8">`) and the page title (`<title>Event Hub</title>`).
* **`<body>`**: Contains all the visible content of the webpage.

### 2. Advanced Semantic HTML5 Landmarks
This code heavily utilizes semantic tags to clearly define the purpose of different sections of the page, which is excellent for SEO and screen readers:
* **`<header>`**: Represents introductory content at the top of the page (the main title and navigation menu).
* **`<nav>`**: Specifically wraps the main navigational links, signaling to browsers that this is the primary menu.
* **`<main>`**: Wraps the dominant content of the page.
* **`<section>`**: Used to logically divide the main content into overarching themes ("Upcoming Events" and "Past Events").
* **`<article>`**: Represents a self-contained composition in the document. Used here perfectly to wrap individual events (e.g., "Rap Battle: 2026"), indicating that each event could logically stand on its own.

### 3. In-Page Navigation (Anchor Links)
* **`id` Attributes**: Unique identifiers are given to the sections (`id="upcoming-events"` and `id="past-events"`).
* **Internal Anchor Links**: The navigation menu uses `<a>` tags where the `href` attribute points to the specific IDs (e.g., `href="#upcoming-events"`). Clicking these links will smoothly jump the user to that specific section of the same page, rather than loading a new website.

### 4. Structuring Content
* **Lists for Navigation**: Uses an unordered list (`<ul>`) and list items (`<li>`) to structure the navigation menu, a standard web development best practice.
* **Heading Hierarchy**: Uses `<h1>` for the site title, `<h2>` for section titles, and `<h3>` for individual event titles, creating a clean, readable outline.

### 5. Media Elements
* **`<img>` (Image Tag)**: Embeds photos for the past events using the `src` attribute.
* **`alt` Attribute**: Provides alternative text for accessibility (e.g., "A stand up comedy show image").
* **`width` Attribute**: Constrains the image sizes directly within the HTML markup.

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered layout.
3. Click the "Upcoming Events" and "Past Events" links at the top to see how the in-page navigation works!