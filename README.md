# CodeScan Advance
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/DragAditya/CodeScan_Advance/tree/main)

CodeScan is a powerful, client-side tool that leverages the Google Gemini AI engine to find bugs, security vulnerabilities, and performance issues in your code before they find you. Paste a code snippet, upload a single file, or drop an entire project folder to receive an instant, in-depth analysis and ready-to-use, corrected code.

**[➤ View the Live Demo](https://dragaditya.github.io/codescan_advance/)**

## Features

- **Multi-Mode Analysis:** Choose between pasting raw code, uploading a single file, or analyzing an entire project folder.
- **AI-Powered Debugging:** Utilizes the Gemini Flash model to perform deep code analysis, detecting a wide range of issues from logical errors to complex security threats.
- **Comprehensive Security Audits:** Identifies common vulnerabilities like SQL injection, Cross-Site Scripting (XSS), buffer overflows, and other OWASP-class threats.
- **Performance Optimization:** Flags memory leaks, inefficient O(n²) loops, and other performance bottlenecks, providing optimization recommendations.
- **Automated Code Fixing:** Delivers ready-to-use, corrected code for every issue found, along with plain-English explanations.
- **Cross-File Integrity Checks:** When analyzing a project folder, CodeScan validates imports, function calls, and dependencies across all files.
- **Downloadable Solutions:** Download a single fixed file or a complete, corrected project packaged in a convenient `.zip` file.
- **Beginner-Friendly Setup Guides:** Automatically detects project dependencies and generates simple, step-by-step installation instructions.
- **Missing Asset Detection:** Scans your code for references to images, fonts, or other files and alerts you if they are missing from the project upload.

## How It Works

CodeScan runs entirely in your browser—no backend servers or data storage required. When you submit your code and a valid Gemini API key, the application:

1.  Constructs a highly-detailed prompt based on your input.
2.  Sends the prompt to the Google Gemini API.
3.  Receives and parses the structured JSON response containing the analysis.
4.  Renders the results in a clean, interactive interface, complete with issue descriptions, code fixes, installation guides, and download options.

## Tech Stack

-   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES2024)
-   **AI Engine:** Google Gemini Flash API
-   **Utilities:** JSZip.js (for creating `.zip` files)
-   **Deployment:** GitHub Pages

## Usage

1.  **Get a Gemini API Key:** Obtain a free API key from [Google AI Studio](https://aistudio.google.com/).
2.  **Visit the Live Demo:** Open the [CodeScan application](https://dragaditya.github.io/codescan_advance/).
3.  **Enter Your Key:** Paste your Gemini API key into the designated input field. The key is stored locally in your browser for the session.
4.  **Provide Your Code:**
    -   **Paste Code:** Paste your code directly into the text area.
    -   **Single File:** Drag and drop a single code file.
    -   **Project Folder:** Drag and drop an entire project folder.
5.  **Scan & Review:** Click the "Scan & Fix" button and wait for the analysis. Review the detailed report, browse the identified issues, and examine the proposed fixes.
6.  **Download:** Download the corrected code, the full project `.zip`, or a text-based scan report.

## Authors

This project was created by:
-   Akshay Borase
-   Aditya Wagh
