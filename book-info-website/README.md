# Book Catalog - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage designed to demonstrate how to correctly construct and format tabular data for a collection of items. It serves as a practical exercise for understanding semantic table structures, grouping data logically, and using cell-spanning attributes to present a clean, organized inventory.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates the core HTML elements required to build accessible and well-structured data tables:

### 1. Document Boilerplate
* **`<!DOCTYPE html>` & `<html>`**: Sets up the modern HTML5 document structure.
* **`<meta name="viewport" ...>`**: Ensures the page scales correctly on mobile devices, a critical best practice for responsive web design.

---

### 2. The `<table>` Element
* **`<table>`**: The foundational container used to display data in a two-dimensional grid consisting of rows and columns.

---

### 3. Semantic Table Structuring
Dividing the table into distinct sections helps both the browser and assistive technologies (like screen readers) understand the layout and hierarchy of the data:
* **`<thead>`**: Groups the header content, defining the column titles (Title, Author, Genre, Publication Year).
* **`<tbody>`**: Contains the primary data block of the table (the actual list of books and their corresponding details).
* **`<tfoot>`**: Groups the footer content, typically used for summaries, totals, or metadata (in this case, the "Total Books" count).

---

### 4. Rows and Cells
* **`<tr>` (Table Row)**: Defines a single horizontal row within the table. Everything nested inside this tag is placed on the same line.
* **`<th>` (Table Header Cell)**: Defines a header cell. Browsers typically render the text inside `<th>` as bold and centered by default. It provides the context for the data beneath it.
* **`<td>` (Table Data Cell)**: Defines a standard cell containing the actual data (e.g., "1984", "George Orwell").

---

### 5. Spanning Columns
* **`colspan="4"` Attribute**: Applied to the `<td>` in the footer. This powerful attribute tells the browser to stretch that single cell across four columns (taking up the entire width of the data above it). This allows the summary text to span neatly across the bottom without throwing the rest of the grid out of alignment.

---

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered page.
3. Observe how the browser automatically structures the grid, formats the `<th>` elements, and merges the footer cell beautifully using the `colspan` attribute.