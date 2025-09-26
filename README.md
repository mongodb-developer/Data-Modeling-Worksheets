# MongoDB Data Modeling Workshop PDF Viewer

This repository hosts a PDF.js-based viewer for the **MongoDB Data Modeling Workshop** worksheet. You can edit the worksheet directly in your browser without downloading any files.

## Live worksheet

The live editable worksheet is deployed at: https://mongodb-developer.github.io/Data-Modeling-Worksheets/web/viewer.

## Files

- `worksheet.pdf` – The MongoDB Data Modeling Workshop worksheet.  
- `web/` – PDF.js viewer files (`viewer.html`, `viewer.js`, `viewer.css`, etc.).  
- `build/` – PDF.js library files (`pdf.js`, `pdf.worker.js`).

## Usage

1. Clone this repository.  

2. Serve with the `http-serve` or another HTTP server:
    ```
    npx http-serve .
    ```

3. Open http://127.0.0.1:8080/web/viewer.

4. The editable worksheet will load in the viewer.

## License

- **PDF.js** is licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).
- **This repository** (HTML, CSS, custom files, and the worksheet) is also licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Disclaimer

Use at your own risk; not a supported MongoDB product
