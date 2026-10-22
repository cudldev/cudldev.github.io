# Antto Väätäinen Resume

The live resume is published at https://cudldev.github.io.

## Edit the resume on GitHub

1. Open `resume.json` in this repository.
2. Click the pencil button to edit the file.
3. Update the text inside the JSON values. Keep the quotation marks and commas in place.
4. Commit the change to the `main` branch. GitHub Pages will publish the update automatically.

The page layout and styling are in `index.html`. The page loads its content from `resume.json`. Experience items can include an optional `url` field for the company website. Entries without a URL have no company link icon.

Project drafts are in the `projects` array in `resume.json`. Each project can include a name, optional dates, a description, and optional highlights. The Projects section appears on the web page and is hidden in the PDF.

The **Save as PDF** button opens the browser print dialog; choose Save as PDF. **Share CV** opens the QR code, which links to the live page. You can download the QR as an SVG image.
