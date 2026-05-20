tes# PDF & Text Converter

A powerful client-side web application designed to help you split PDF files into manageable image chunks, directly inject prompts into ChatGPT, and seamlessly combine ChatGPT responses into a single, beautifully formatted layout.

## Features

- **🔒 Secure Access**: Password-protected entry to ensure only authorized users can utilize the tool.
- **🔪 PDF Splitter**: Upload a PDF and render pages into high-quality JPG chunks (e.g., 10 pages per chunk) without needing to upload the file to any external server.
- **📝 Text to PDF Converter**: Paste text or tables to convert them into neatly formatted, paginated PDF documents directly from your browser.
- **🤖 ChatGPT Integration**: Instantly send generated image chunks and predefined prompts to ChatGPT with a single click—reusing the same ChatGPT tab for a continuous workflow.
- **🔗 Smart Response Combiner**: Collect responses from multiple chunks and combine them into a single, dense, professional study notes layout with perfectly formatted line spacing (1.15) and reduced gaps.

## How to Run

Because this tool relies on local file processing and web workers, you can simply open the `index.html` file in any modern web browser (like Chrome, Edge, or Firefox).

1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. Enter the access password to unlock the tool.
4. Drag and drop a PDF file to begin!

## Technologies Used

- Vanilla HTML, CSS, JavaScript
- [pdf-lib](https://pdf-lib.js.org/) for PDF manipulation
- [PDF.js](https://mozilla.github.io/pdf.js/) for rendering PDF pages to canvases
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) for HTML to PDF conversion
- [JSZip](https://stuk.github.io/jszip/) for generating ZIP archives

## Privacy

Everything runs completely locally within your browser. No PDF files, text, or credentials are uploaded to any backend server.
