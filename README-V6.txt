CLARION COUNTY REENTRY RESOURCE CENTER — VERSION 6

This is a COMPLETE replacement of the Version 5 site; it retains the previous pages and PDFs.

INSTALL: Extract this ZIP. Upload ALL files and folders inside the extracted clarion-reentry-v6 folder to the ROOT of your existing public GitHub repository brandygreulich2-byte/clarion-reentry. Preserve assets/, downloads/, and resources/ subfolders. Commit the changes. Do not upload only the ZIP or put everything inside an extra nested folder. GitHub web upload may need dragging folders into the upload area; if folder preservation is difficult, use GitHub Desktop.

New: about.html, calendar.html, verification.html, 20 resource profile pages in resources/, printable public event and verification templates, downloads/verification-log.csv.

Calendar starts EMPTY on purpose: assets/events.json is []. To publish a real event, edit the JSON array with a reviewed record based on assets/events-example.json; set approved:true only after checking the official event source. Dates must use YYYY-MM-DD; past dates are hidden. The example file is never loaded on the public calendar.

Resource profiles are generated from Version 5 assets/resources.json. Published-source checks do not mean providers have directly confirmed details. The CSV log is a starter PUBLIC-ONLY editor worksheet, not a place for client records.

Test after upload: /, /resource-directory.html, /resources/resource-01.html, /calendar.html, /verification.html, /about.html, /workbook.html and PDF links.

No forms collect submissions. Never put private client data, credentials, or treatment/correctional records in this public repository.
