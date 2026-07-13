Markdown
# HTML Data Tables - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage designed to demonstrate how to correctly construct and format tabular data. It serves as a practical exercise for understanding semantic table structures, grouping data logically, and utilizing attributes to span cells across columns.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates the core HTML elements required to build accessible and well-structured data tables:

### 1. The `<table>` & `<caption>` Elements
* **`<table>`**: The foundational container used to display data in a two-dimensional grid consisting of rows and columns.
* **`<caption>`**: Provides a title or explanatory heading for the table ("Calculus Final Exam Grades"). This improves accessibility by giving screen reader users immediate context about the table's contents before they navigate through the data.

---

### 2. Semantic Table Structuring
Dividing the table into distinct sections helps both the browser and assistive technologies understand the layout of the data:
* **`<thead>`**: Groups the header content. This defines the column titles (Last Name, First Name, Grade). 
* **`<tbody>`**: Contains the primary data block of the table (the actual list of students and their scores).
* **`<tfoot>`**: Groups the footer content, typically used for summaries, totals, or averages (in this case, the Average Grade). 

---

### 3. Rows and Cells
* **`<tr>` (Table Row)**: Defines a single horizontal row within the table. Everything inside this tag will be placed on the same line.
* **`<th>` (Table Header Cell)**: Defines a header cell. Browsers typically render the text inside `<th>` as bold and centered by default. It indicates what kind of data is in that specific column or row.
* **`<td>` (Table Data Cell)**: Defines a standard cell containing the actual data (e.g., "Davis", "54").

---

### 4. Spanning Columns
* **`colspan="2"` Attribute**: Applied to a `<td>` in the footer. This powerful attribute tells the browser to stretch that single cell across two columns (taking up the space of both the "Last Name" and "First Name" columns). This aligns the "Average Grade" label neatly to the left of the actual numerical average.

---

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered page.
3. Observe how the browser automatically structures the grid, bolds the `<th>` elements, and merges the footer cells using the `colspan` attribute!