# Certification Project: Developer & Creator Survey Form

## Overview
This project is a comprehensive static HTML webpage featuring the "2026 Developer & Creator Insight Poll." It serves as a capstone certification project, demonstrating a mastery of foundational HTML5 skills. The project heavily utilizes structural semantics, diverse user input controls, native browser validation, and data table layouts to create a robust and accessible form interface.

## HTML Skills Showcased

This project acts as a culmination of core HTML concepts, bringing together several distinct techniques into a single, cohesive user experience:

### 1. Semantic Document Structure
* **`<header>` and `<main>`**: The document uses semantic tags to clearly separate the introductory context (survey title and description) from the primary interactive content (the form itself).
* **Targetable Elements**: Crucial elements utilize unique `id` attributes (e.g., `id="title"`, `id="description"`), establishing best practices for future CSS styling and DOM manipulation via JavaScript.

---

### 2. Precise Table-Based Layouts
* **`<table>`, `<tr>`, `<th>`, and `<td>`**: The form inputs and their corresponding labels are structurally aligned using HTML tables. 
* **Syntax Mastery**: The project demonstrates strict adherence to HTML syntax rules, ensuring all table rows (`<tr>`) and data cells (`<td>...</td>`) are perfectly opened, nested, and closed to prevent rendering bugs and ensure cross-browser compatibility.

---

### 3. Comprehensive Input Types & HTML5 Validation
* **Data Specificity**: Utilizes `type="text"`, `type="email"`, and `type="number"` to define exact data expectations. The browser automatically enforces valid email formats (requiring the `@` symbol) and restricts the age field to digits.
* **Boundary & Requirement Attributes**: Implements the `required` boolean attribute to prevent incomplete submissions, and uses `min="15"` and `max="100"` to logically bound numerical inputs.

---

### 4. Advanced Selection Controls
* **Dropdown Menus**: Uses `<select>` and `<option>` to create space-saving dropdowns. It features an advanced UI pattern using `<option selected disabled>` to provide a helpful placeholder prompt ("Please select an option") that cannot be submitted as a valid answer.
* **Mutually Exclusive Radio Buttons**: Utilizes `<input type="radio">` grouped by a shared `name` attribute (`name="tick"`) to force a single selection for the user's interface preference.
* **Multiple Choice Checkboxes**: Deploys `<input type="checkbox">` for questions allowing multiple answers. *Best Practice Note: Each checkbox is paired with a `<label>` and utilizes unique IDs to ensure maximum accessibility and clickability.*

---

### 5. Multi-line Input & Submission Mechanics
* **`<textarea>`**: Provides a sized, multi-line text box for open-ended user feedback.
* **Form Action**: Includes a `<button type="submit">` to act as the primary trigger, wrapping up the data collection process and executing the browser's native validation checks.

---

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered form.
3. Test the form's resilience by attempting to submit without an email, entering text into the age field, or leaving required fields blank to see the native HTML5 validation in action.