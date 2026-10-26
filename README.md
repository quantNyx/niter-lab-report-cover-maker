# NITER Lab Report Cover Maker

A browser-based tool for creating a print-ready NITER lab report cover page. Fill in course, experiment, student, and teacher details and see the cover update as you type.

## Features

- NITER-branded cover layout with department selection for TE, CSE, EEE, IPE, and FDAE
- Decorative page border and subtle centered NITER watermark
- Live preview formatted for A4 paper with 1-inch margins
- Export as PDF, a Word-compatible `.doc` file, PNG, or JPG
- Responsive editor layout for desktop and mobile screens
- Runs locally in your browser; the project does not send form data to a server

## Getting started

No installation, build step, or dependencies are required.

1. Download or clone this repository.
2. Keep `index.html` and `niter-logo.png` together in the same folder.
3. Open `index.html` in a modern browser.

## Using the cover maker

1. Select the department and enter the course and experiment information.
2. Fill in the student and teacher details.
3. Review the live cover preview.
4. Choose an export format:
   - **PDF:** In the browser print dialog, select **Save as PDF**. Under **More settings**, turn off **Headers and footers** to remove the browser date, page title, URL, and page number.
   - **Word (.doc):** Download a Word-compatible document.
   - **PNG image** or **JPG image:** Download a high-resolution image of the cover.

The browser may ask for permission to download files or open the print dialog. Entered details are not saved by the app, so they will be cleared when the page is refreshed or closed.

## Project files

- `index.html` — app layout, styling, live preview, and export functionality
- `niter-logo.png` — NITER emblem used on the cover
