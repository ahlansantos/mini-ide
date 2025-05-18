Multi-Language Code Executor
This project provides a simple, web-based code executor that allows users to write and run code snippets directly in their web browser using client-side interpreters. Currently, it supports Python via Skulpt and Lua via Lua.js.
Features
 * Multi-Language Support: Execute code in different programming languages.
 * Web-Based: Runs entirely in the browser using JavaScript libraries.
 * Live Output: Displays the standard output (print statements) and errors in a dedicated area.
 * Simple Interface: Clean and intuitive layout with a code editor and an output console.
 * Responsive Design: Works on different screen sizes thanks to Tailwind CSS.
Supported Languages
 * Python: Executed using the Skulpt library.
 * Lua: Executed using the Lua.js library.
Note: The support for each language is limited by the capabilities and implemented features of the respective JavaScript libraries (Skulpt and Lua.js). Not all built-in functions or standard library modules may be available.
How to Use
 * Save the provided HTML code as an .html file (e.g., executor.html).
 * Open the executor.html file in a modern web browser (like Chrome, Firefox, Edge, Safari).
   * Alternatively, you can open the file using a code editor on your Android device that supports HTML preview, such as Acode.
 * Select the desired language from the dropdown menu.
 * Write or paste your code into the "Code Editor" area. Example code for the selected language will load automatically when you switch.
 * Click the "Run Code" button to execute your code.
 * View the output and any errors in the "Output" area.
 * Click the "Clear Output" button to clear the output area.
Limitations
 * Browser Environment: Code runs within the browser's JavaScript environment, meaning it cannot access local files (except through browser APIs like file input, if implemented), network resources (unless allowed by browser security policies), or native system functionalities.
 * Library Support: Only the standard library features implemented by Skulpt and Lua.js are available. Third-party libraries cannot be easily imported or used.
 * Performance: Execution speed is limited by the JavaScript interpreter's performance, which is generally slower than native execution.
 * No Native Compilation/Export: This tool is for executing code in the browser. It does not compile your code into native applications (like Android APKs) or other executable formats. To create native applications, you would need to use dedicated development environments and tools (e.g., Android Studio for Kotlin/Java, Kivy for Python mobile apps, etc.).
Technologies Used
 * HTML5: Structure of the web page.
 * CSS3: Styling, including custom styles and scrollbar customization.
 * Tailwind CSS: Utility-first CSS framework for rapid styling and responsive design.
 * JavaScript: Core logic for interacting with the DOM, handling events, and integrating the interpreters.
 * Skulpt: JavaScript interpreter for Python.
 * Lua.js: JavaScript interpreter for Lua.
Feel free to modify and extend this project!
