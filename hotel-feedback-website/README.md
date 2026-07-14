# Hotel Feedback Form - HTML Fundamentals Practice

## Overview
This project is a static HTML webpage featuring a comprehensive "Hotel Feedback Form." It serves as an in-depth practice exercise for building user input interfaces, focusing heavily on form structure, various input types, semantic element grouping, and basic HTML5 validation attributes.

## HTML Fundamentals Practiced

This code snippet effectively demonstrates several core HTML concepts, specifically tailored to data collection:

### 1. The `<form>` Element
* **`<form>`**: The foundational container for all user input.
* **`action` Attribute**: Specifies the URL (`https://hotel-feedback.freecodecamp.org`) where the collected data should be sent upon submission.
* **`method="POST"`**: Indicates that the form data will be sent securely in the HTTP request body (ideal for sensitive or large amounts of data), rather than appended to the URL.

### 2. Grouping & Structuring Form Data
* **`<fieldset>`**: Used to logically group related form elements together (e.g., Personal Information, Ratings). This creates a distinct visual box around the items by default and significantly improves accessibility.
* **`<legend>`**: Defines a caption for the `<fieldset>`, acting as the title for that specific group of inputs.

### 3. Accessibility & Labels
* **`<label>`**: Crucial for user experience and accessibility. 
* **The `for` / `id` Relationship**: The code perfectly maps the `for` attribute of the `<label>` to the `id` attribute of the corresponding `<input>`. This ensures screen readers can read the label, and it allows users to click the text label itself to select the input field (especially useful for tiny checkboxes and radio buttons).

### 4. Diverse Input Types
The `<input>` tag is used extensively with various `type` attributes to control the kind of data accepted:
* **`type="text"` & `type="email"`**: For standard text entry. The `email` type automatically enforces basic email formatting validation.
* **`type="number"`**: Restricts input to numeric values, utilizing `min="3"` and `max="100"` to define an acceptable range.
* **`type="radio"`**: Used for mutually exclusive choices (Was this your first time?). They share the same `name` attribute (`hotel-stay`) so only one can be selected at a time.
* **`type="checkbox"`**: Used for multiple-choice selections where the user can check all that apply.
* **`checked` Attribute**: Pre-selects a specific option by default (e.g., Reputation).

### 5. Dropdown Menus & Multi-line Text
* **`<select>` and `<option>`**: Creates a dropdown menu for the "Ratings" section.
* **`selected` Attribute**: Sets the default visible choice (e.g., "Excellent") when the page loads.
* **`<textarea>`**: Provides a large, multi-line text box for free-form comments, sized using `cols="30"` and `rows="10"`.

### 6. HTML5 Validation & UX Attributes
* **`required`**: A boolean attribute that prevents the form from being submitted if the field is left empty (applied to Name and Email).
* **`placeholder`**: Provides a short hint (e.g., "e.g., John Doe") inside the input field before the user types anything.
* **`<button type="submit">`**: Triggers the form submission process.

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the rendered form.
3. Try filling out the form and clicking "Submit" to see how the browser enforces the `required` fields and `email` formatting!