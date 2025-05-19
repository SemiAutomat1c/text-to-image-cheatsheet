# Text-to-Image Converter

A web-based tool that converts text or code into properly formatted images, specifically designed for creating cheat sheets and answer keys. The tool automatically arranges the content on A4 pages for easy printing and cutting.

## Features

- Convert text or code into 8.5x5.5cm images
- Two modes: Code Mode and Text Mode
- Automatic A4 page layout with cutting guides
- Multiple compression options:
  - Normal Mode
  - Compact Mode
  - Ultra Compact Mode
- Customizable settings:
  - Font size (8px-16px)
  - Scale factor (1x-4x)
  - Anti-aliasing
  - High contrast mode
- Export options:
  - Download individual PNG images
  - Download as PDF
  - Preview before download
- Visual aids for cutting:
  - Page numbers
  - Image numbers
  - Cutting guidelines
  - Corner marks

## Usage

1. Select mode (Code or Text)
2. Choose compression settings
3. Adjust quality settings if needed
4. Enter or paste your text/code
5. Click "Preview" to see the result
6. Download as PNG or PDF

## Setup

1. Clone the repository
2. Open `index.html` in a web browser
3. Start converting your text to images!

## File Structure

- `index.html` - Main HTML file
- `styles.css` - CSS styles
- `script.js` - JavaScript functionality

## Dependencies

- jsPDF (2.5.1) - For PDF generation

## Browser Support

Works in all modern browsers that support:
- Canvas API
- ES6+ JavaScript
- CSS Grid/Flexbox 