# Reference Tracker

A browser-based application for organizing documentation,
requirements, solutions, and configuration references.

Build a searchable knowledge base of reusable information
across projects, systems, and business processes.

## Features

- Create, edit, and organize reference records.
- Categorize references by scope, object, and configuration.
- Document requirements and their corresponding solutions.
- Search across record fields and apply filters.
- Mark frequently used references as favourites.
- Save views for recurring searches and layouts.
- Customize column visibility and configuration.
- Add custom fields and manage dropdown values.
- Review dashboard summaries and quality indicators.
- Track application changes through an audit history.
- Undo supported changes.

## Import and Export

- Import reference records from CSV or Excel.
- Export records to styled Excel or CSV files.
- Export all records as JSON.
- Export audit history as CSV.
- Download and restore a full JSON backup.

Excel import reads the first worksheet.
Use column headings that match the application's field
labels or keys.

## Getting Started

1. Select Code → Download ZIP.
2. Extract the downloaded ZIP file.
3. Open index.html in a modern browser.
4. Click New Record to add a reference.
5. Configure columns and dropdown values as needed.

No application server is required.

## Example Use Cases

- Maintain a library of requirements and solutions.
- Record system configuration steps.
- Organize troubleshooting knowledge.
- Capture reusable project lessons.
- Find previous solutions using categories and keywords.

## Data Storage and Backup

Records and settings are saved in browser local storage.

Data does not automatically synchronize between browsers,
profiles, or devices. Clearing browser data can remove it.

Export full backups regularly and before moving or updating
the application.

Restoring a backup can overwrite current records and settings.
Export the current dataset before restoring another backup.

GitHub stores the application code, not the records saved
in your browser.

## Internet Requirements

Core record management uses browser-based functionality.

Excel import and export depend on xlsx-js-style, loaded from
jsDelivr. These features require the library to load successfully.

If the Excel library is unavailable, use CSV import and export.
Excel export automatically falls back to CSV.

## Privacy

Records are processed and stored locally in your browser.
The application does not include a backend for synchronizing
or sharing records.

Loading the Excel dependency makes a request to jsDelivr.

## Technology

- HTML
- CSS
- JavaScript
- Browser local storage
- xlsx-js-style for Excel import and export

## Updates

Export a full backup before updating.

Replace index.html with the latest version and use a
descriptive commit message to record the change.
