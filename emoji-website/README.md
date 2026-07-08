# SVG Heart Icon - HTML Fundamentals Practice

## Overview
This project is a minimal static HTML webpage demonstrating how to embed inline Scalable Vector Graphics (SVG). It serves as a practical introduction to creating resolution-independent graphics, specifically focusing on the SVG canvas coordinate system and basic path drawing.

## HTML Fundamentals Practiced

This code snippet highlights the core concepts of embedding and structuring vector graphics directly within HTML:

### 1. HTML5 Document Structure
* **`<!doctype html>`**: Declares the document as HTML5, ensuring modern browsers render it correctly.
* **`<meta charset="UTF-8" />`**: Sets the character encoding to UTF-8, a crucial best practice that covers almost all characters and symbols in the world.

---

### 2. The `<svg>` Element
* **`<svg>`**: The container used to define vector-based graphics for the web. Unlike raster images (JPEG, PNG), SVGs are drawn using math, meaning they can scale to any size without losing quality or becoming pixelated.
* **`width="24"` & `height="24"`**: Defines the intrinsic dimensions of the SVG element on the webpage (24x24 pixels).
* **`viewBox="0 0 24 24"`**: The most important attribute for responsive SVGs. It defines the internal coordinate system of the graphic. Here, it establishes a grid starting at X:0, Y:0 that is 24 units wide and 24 units high. If the `width` and `height` are changed later via CSS, the graphic will scale perfectly within this proportional box.
* **`fill="red"`**: An attribute that applies a default fill color to all shapes nested within the SVG container.

---

### 3. The `<path>` Element
* **`<path>`**: The most powerful and versatile SVG shape element. It acts like a pen drawing on the screen.
* **`d` Attribute**: Stands for "data." It contains a string of commands that dictate exactly how the path is drawn:
  * **`M12 21`**: "Move To" coordinates (12, 21) without drawing a line. This is where the pen starts.
  * **`s` and `c/C`**: Commands for drawing smooth and cubic Bezier curves, which create the rounded bumps of the heart.
  * **`z`**: The "Close Path" command, which draws a straight line back to the original starting point to finish the shape.

---

## How to Run
1. Save the code in a file named `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. You will see a crisp, red heart icon rendered on the screen. Try changing the `width` and `height` attributes to `240` to see how the SVG scales perfectly without blurring!