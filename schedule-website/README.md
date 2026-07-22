# Tech Conference Schedule - HTML Accessibility & TTS Practice

## Overview
This project is a static HTML webpage featuring a "Tech Conference 2025 Schedule." It serves as a focused practice exercise for building highly accessible tabular data, specifically optimized for Text-to-Speech (TTS) software and screen readers. It emphasizes semantic table architecture and crucial accessibility attributes over visual styling.

## HTML Fundamentals Practiced

This code snippet demonstrates several core HTML concepts tailored to making complex grid data understandable for assistive technologies:

### 1. The `<table>` Element & Caption
* **`<table>`**: The foundational container used to display data in a two-dimensional grid of rows and columns.
* **`<caption>`**: Provides a descriptive title ("Schedule by Track and Time") attached directly to the table. This is highly beneficial for TTS software, as it announces the context immediately, allowing users to understand what the data represents before navigating the grid.

### 2. Semantic Table Structure
* **`<thead>`**: Logically groups the header content (the time and track names) at the top of the table. This helps browsers and assistive technologies separate the structural headers from the actual schedule data.
* **`<tbody>`**: Encloses the primary content of the table (the actual session blocks and breaks). 

### 3. Rows, Headers, and Data Cells
* **`<tr>` (Table Row)**: Defines a single horizontal slice of the table.
* **`<th>` (Table Header)**: Indicates that a cell acts as a header for a group of other cells. 
* **`<td>` (Table Data)**: Defines a standard cell containing the actual content (e.g., "UX for All").

### 4. Screen Reader Mapping with the `scope` Attribute
This is the most critical feature for TTS optimization in this project:
* **`scope`**: Used within `<th>` tags to explicitly define the relationship between headers and data cells. Without this, a screen reader might read the schedule left-to-right as a confusing "word salad."
* **`scope="col"`**: Applied to the top headers (Time, Track A, Track B) to explicitly tell the software that these headers apply to the data in the columns directly below them.
* **`scope="row"`**: Applied to the time slots on the left (e.g., 9:00 AM) to associate that specific time with all the events in that horizontal row.

### 5. Spanning Columns
* **`colspan` Attribute**: Allows a single cell to stretch across multiple columns. `colspan="3"` is applied to the "Break" and "Lunch Break" `<td>` elements to structurally indicate that these events apply universally to all three tracks simultaneously, preventing repetitive blank cells that might confuse a screen reader.

## How to Run & Test
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered schedule.
3. **Accessibility Test:** Turn on a screen reader (like NVDA for Windows or VoiceOver for Mac) and navigate through the table to hear how the `scope` and `<caption>` attributes successfully map the complex schedule into understandable audio!