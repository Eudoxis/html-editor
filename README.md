# HTML Editor Web App

A modern, lightweight HTML editor implemented entirely as a web page, designed to offer a seamless editing experience directly in your browser.  
It provides a clean, responsive interface with multiple tabs, live preview, and useful editing tools — all without the need for any server or installation.

---

## Features

- **Real-time HTML Editing:**  
  Write or paste your HTML code with instant rendering in the live preview pane.  
- **Multiple Tabs:**  
  Manage multiple HTML files simultaneously with the ability to create, rename, switch, and close tabs.  
- **File Upload and Download:**  
  Easily load `.html` files into new tabs or save your edits back to your device.  
- **Clipboard Integration:**  
  Quickly paste HTML code from your clipboard directly into the editor.  
- **Clear Editor Content:**  
  Clear your current tab’s content with a single click.  
- **Dark Mode & Light Mode:**  
  Toggle between light and dark themes for comfortable editing in any environment.  
- **Resizable Split View:**  
  Adjust the width between the editor and preview panes with a draggable splitter.  
- **Syntax Highlighting & Auto-Completion:**  
  Powered by CodeMirror for a smooth coding experience with line numbers, tag auto-closing, and color-coded syntax.  

---

## Technology Stack

- **Frontend:** Pure HTML, CSS, and JavaScript — no backend required.  
- **Code Editing:** [CodeMirror](https://codemirror.net/) (v5.65.2) provides robust code editing features including syntax highlighting and auto-closing tags.  
- **Layout Management:** [Split.js](https://split.js.org/) enables draggable resizable panes between editor and preview.  
- **Browser APIs:** FileReader for file uploads, Blob for downloads, and Clipboard API for paste support.  

---

## Usage Instructions

1. **Open the `index.html` in any modern web browser** (Chrome, Firefox, Edge, Safari).  
2. Use the **toolbar buttons** to:  
   - **Paste** HTML code from clipboard into the editor.  
   - **Clear** the current editor content.  
   - **Upload** `.html` files to open in new tabs.  
   - **Download** the current tab content as an `.html` file.  
3. Create and manage multiple tabs with the tab bar above the editor. Rename tabs by editing their names directly.  
4. Toggle **dark mode** using the switch on the toolbar for better visibility in low-light environments.  
5. Adjust the width of the editor and preview panes by dragging the splitter between them.  
6. The preview pane updates live as you edit your code.  

---

## Licensing and Usage

This project is **licensed under the [GNU General Public License v3.0 (GPL-3.0)](https://www.gnu.org/licenses/gpl-3.0.en.html)**.  

This means:  
- You are free to use, modify, and distribute this software, but **any derivative work must also be licensed under GPL-3.0**.  
- You must make the source code available when distributing your version.  
- The project comes with **no warranty**; use it at your own risk.  

---

## Acknowledgments

- This project was created **with the assistance of AI (Gemini 2.5 Pro)**, which helped generate, review, and refine the code and documentation.  
- Special thanks to the open-source projects that made this possible:  
  - [CodeMirror](https://codemirror.net/) — powerful code editor component under MIT License.  
  - [Split.js](https://split.js.org/) — for resizable split views, also MIT Licensed.  

Please respect their licenses when redistributing or integrating their code.

---

## Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repository and submit pull requests.

---

## Contact

For questions or feedback, please open an issue in this repository or contact the maintainer directly.

---

## Disclaimer

This software is provided "as is" without any express or implied warranties. Use at your own risk.

---

*Enjoy coding and happy editing!*  
