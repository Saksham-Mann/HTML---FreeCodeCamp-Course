# Accessible Audio Controls - ARIA Implementation Practice

## Overview
This project is a minimal static HTML webpage demonstrating basic audio interface controls (Play, Volume, Mute). Its primary focus and standout feature is the implementation of **Accessible Rich Internet Applications (ARIA)** attributes—specifically `aria-labelledby`—to ensure complex input relationships are perfectly readable by screen readers and assistive technologies.

## HTML & Accessibility Fundamentals Practiced

This code snippet serves as a focused example of how to make custom or non-standard form controls accessible without relying on traditional `<label>` elements:

### 1. The Main Feature: Advanced ARIA Implementation
* **`aria-labelledby`**: This is the core focus of the snippet. Standard HTML `<label>` elements are great for a 1-to-1 relationship, but this input requires more context. By using `aria-labelledby="volume-label volume-description"`, the code instructs screen readers to string together the text from *both* `<span>` elements (via their IDs). 
* **The Result**: When a user focuses on the slider, the screen reader will announce: "Volume, Adjust the sound level, slider, 50." This provides a much richer and more contextual experience for visually impaired users.

### 2. Native HTML Controls
* **`<button type="button">`**: Used for the "Play" and "Mute" actions. Explicitly declaring `type="button"` is a crucial best practice; it prevents the buttons from accidentally submitting data or refreshing the page if this code were later wrapped inside a `<form>`.

### 3. The Range Slider Input
* **`<input type="range">`**: Renders a native, draggable slider control, perfect for volume, brightness, or any variable scale.
* **Range Attributes (`min`, `max`, `value`)**: These set the boundaries of the slider (0 to 100) and establish the default starting position (50, or half-volume) when the page loads.

### 4. Inline Text Elements
* **`<span>`**: Used to hold the text strings ("Volume" and "Adjust the sound level"). Because `<span>` elements are inline and have no inherent semantic meaning, they are perfect targets for the `aria-labelledby` attribute to reference without disrupting the page layout.

## How to Run & Test
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge) to view the UI.
3. **Accessibility Test:** Turn on a screen reader (like NVDA, JAWS, or VoiceOver), use the `Tab` key to navigate to the range slider, and listen to how seamlessly the ARIA attribute combines the two text spans to explain the control's purpose!