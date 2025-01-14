# Google_spreadsheet_clone_assingment1
Overview
This project is a browser-based spreadsheet application that emulates the core functionalities and user interface of Google Sheets. The application allows users to input, format, and manipulate data in a tabular format with support for basic mathematical and data quality functions.

Features
Core Functionalities
Spreadsheet Interface:

UI: Mimics Google Sheets, including a toolbar, formula bar, and grid-based layout.
Drag and Selection: Supports cell selection and interaction.
Formatting: Basic formatting options like bold, italics, and font size changes.
Row/Column Operations: Add, delete, and resize rows and columns.
Mathematical Functions:

SUM: Calculates the sum of a range of cells.
AVERAGE: Calculates the average of a range.
MIN: Finds the minimum value in a range.
MAX: Finds the maximum value in a range.
COUNT: Counts numerical entries in a range.
Data Quality Functions:

TRIM: Removes leading and trailing whitespace.
UPPER: Converts text to uppercase.
LOWER: Converts text to lowercase.
REMOVE_DUPLICATES: Removes duplicate rows.
FIND_AND_REPLACE: Searches and replaces specific text in a range.
Dynamic Updates:

Cell Dependencies: Automatically updates dependent cells when referenced values change.
Formulas: Supports custom formulas with relative and absolute references.
Testing and Feedback:

Users can enter test data and validate function outputs in real-time.
Bonus Features
Save and load spreadsheet data.
Data visualization with basic charts and graphs (planned).
Support for additional mathematical and logical functions.
Installation and Usage
Prerequisites
A modern web browser (Chrome, Firefox, Edge, etc.).
No additional dependencies beyond standard JavaScript and Math.js.
Setup
Download the project files.
Open index.html in your browser.
Usage
Use the toolbar to select formatting options.
Enter data directly into cells or use the formula bar for calculations.
Apply functions using standard syntax, e.g., =SUM(A1:A3).
Validate results by observing automatic cell updates.
Data Structures
2D Array:

Used to store cell data and properties (e.g., alignment, formatting).
Example: spreadsheetData and cellProperties.
Dependency Graph:

Manages cell dependencies to ensure formula accuracy.
Example: executionsDependentOnCell.
Functions Map:

Maps function names (e.g., SUM, UPPER) to corresponding implementation logic.
Key Technologies
Frontend
HTML5: Structure of the application.
CSS3: Styling, including grid layout and toolbar design.
JavaScript: Core application logic.
Libraries
Math.js: Handles mathematical expression parsing and evaluation.
Function Implementation
Example: SUM Function
Parses the range of cells (e.g., A1:B2).
Accumulates numerical values within the range.
Updates dependent cells dynamically.
javascript

Evaluation Criteria
UI Fidelity: Resemblance to Google Sheets, including smooth drag-and-drop and formula behavior.
Functionality: Completeness and accuracy of implemented features.
User Experience: Intuitiveness of interactions.
Code Quality: Clean, modular, and maintainable codebase.
Documentation: Clarity of setup instructions and code structure.
Future Enhancements
Implement advanced formulas and conditional formatting.
Add persistent storage for spreadsheets (e.g., localStorage or a backend API).
Introduce data visualization tools like charts and pivot tables.
Authors
Your Name
Contact: [Your Email]
