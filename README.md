# priyanshu-pdf-creator

A Node.js package to generate PDFs of web pages using Puppeteer.

## Installation

You can install the package via npm:

```bash
npm install priyanshu-pdf-creator
```

## Usage

Here's how you can use this package in your Node.js code:

```javascript
const generatePDF = require('priyanshu-pdf-creator');

// Example usage:
const url = 'https://example.com';
const outputPath = './example.pdf';

generatePDF(url, outputPath)
  .then(() => console.log('PDF generation complete.'))
  .catch((error) => console.error('Error generating PDF:', error));
```

## License

This project is licensed under the Apache License 2.0
