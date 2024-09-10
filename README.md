# Html2JS
**Demo:** [https://tarikyalcinkaya.github.io/html2JS/html2js.html](https://tarikyalcinkaya.github.io/html2JS/html2js.html)

This project demonstrates a simple HTML to JavaScript code conversion. 

**Functionality:**

* **Live Conversion:**  The application provides a real-time preview of the generated JavaScript code based on your HTML input. 
* **Element Mapping:** The generated JavaScript code constructs DOM elements (like `<div>`, `<p>`, etc.) and their attributes, mirroring the structure of your HTML.
* **Inline Styles:** CSS styles applied within `<style>` tags or directly in HTML attributes are extracted and converted into inline styles for the corresponding elements.

**How it Works:**

The core logic relies on a JavaScript function `generateCodeRecursive` that parses the HTML document (using `Document Object Model`) and iteratively builds the JavaScript code representation:

1. **Tree Traversal:** It traverses the HTML DOM structure, starting from the root element (`<body>`).
2. **Element Mapping:**  For each element, it creates a corresponding JavaScript object representing its type, attributes, and content.
3. **Attribute Conversion:** Attribute values are directly mapped into the JavaScript representation.

**Example Usage:**

1. Paste your HTML code into the designated area.
2. Observe how the generated JavaScript code reflects the structure of your input.
3. Customize your HTML and see the corresponding updates in the JavaScript output.


**Potential Applications:**

* **Web Development Education:** Demonstrates how HTML can be represented programmatically in JavaScript.
* **Dynamic Content Generation:**  Potentially generate parts of a webpage's structure based on data or user input. 



Let me know if you have any questions or would like to explore further customizations!