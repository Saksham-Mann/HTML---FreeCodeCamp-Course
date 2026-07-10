# HTML Quotations and Citations - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage highlighting advice for aspiring developers. It serves as a targeted practice exercise for mastering HTML5's semantic elements related to text formatting, specifically focusing on how to properly markup block quotes, inline quotes, and source citations.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates how to structure and semantically cite textual references, which is highly beneficial for both accessibility and Search Engine Optimization (SEO):

### 1. Document Structure & Semantics
* **Boilerplate**: Uses standard HTML5 setup, including `<meta name="viewport">` for mobile responsiveness.
* **`<main>` and `<section>`**: The document relies on strong semantic structure, grouping distinct pieces of advice into their own logical `<section>` blocks within the primary `<main>` container.

---

### 2. Block-Level Quotations
* **`<blockquote>`**: Used to represent a section that is quoted from another source. Browsers typically render this by indenting the text to visually separate it from regular paragraphs.
* **`cite` Attribute**: Applied directly inside the opening `<blockquote>` tag. While invisible to the user, this attribute provides the exact URL (`https://www.freecodecamp.org/news/learn-to-code-book/`) where the quote originated, providing crucial context for search engines and screen readers.

---

### 3. Inline Quotations
* **`<q>`**: Used for short, inline quotations that flow within a standard paragraph. 
* **Automatic Quotation Marks**: A great feature of the `<q>` tag is that modern browsers will automatically inject the appropriate opening and closing quotation marks around the text, so you don't have to type them yourself! It also utilizes the `cite` attribute to link the source URL.

---

### 4. Citing Creative Works
* **The `<cite>` Element**: Notice the difference here! While `cite` is used as an *attribute* in the quote tags, `<cite>` is also its own distinct HTML *element*. It is used to define the title of a creative work (in this case, the book *How to Learn to Code and Get a Developer Job*). Browsers usually render text inside this tag in italics.

---

### 5. HTML Entities
* **`&mdash;`**: This is an HTML entity code used to render an "em dash" (—) right before Quincy Larson's name. Using entity codes ensures special characters render perfectly across all browsers without relying on specific keyboard layouts.

---

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered page.
3. Observe how the browser automatically indents the `<blockquote>` sections, italicizes the `<cite>` book title, and adds quotation marks around the `<q>` inline text!