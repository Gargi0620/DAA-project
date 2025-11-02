Employee Shift Management System

The Employee Shift Management System is a web application designed to help managers upload employee data, generate work shift schedules, and export them as PDF reports, all directly in the browser.
Built using HTML, Tailwind CSS, and JavaScript, this system demonstrates CSV file handling, client-side data processing, and PDF generation without the need for a backend server.

Features:
CSV Upload: Import employee lists easily using drag-and-drop or file selection.
Employee Preview: View uploaded employee data before generating schedules.
Automatic Shift Generation: Simulated assignment of Morning, Evening, and Night shifts.
Shift Visualization: Each shift type is color-coded for quick identification.
PDF Export: Download generated schedules as professional-looking PDF reports.
Reset & Reuse: Restart anytime to upload a new employee list.


How It Works:

Upload a CSV file containing two columns:
Name and Gender

Preview the uploaded data in a responsive table.

Generate shift assignments using any scheduling method.

View and Download the generated schedule as a formatted PDF.

Reset to start over or upload a new dataset.

Note: The current version simulates algorithmic scheduling for demonstration purposes.
Future enhancements may include true greedy and backtracking optimization algorithms for realistic shift planning.

Technologies Used:

Frontend: HTML5, Tailwind CSS

Icons: Font Awesome

CSV Parsing: PapaParse

PDF Generation: jsPDF
 + jsPDF-AutoTable

Animations: Tailwind transitions and custom CSS keyframes

Example CSV Format:
Name,Gender
Alice,Female
Bob,Male
Carol,Female
David,Male

Output Example:
Name  Gender	Assigned Shift	   Hours
Alice Female	Morning (8am–4pm) 	8
Bob  	Male	  Night (12am–8am)	  8
Carol	Female	Evening (4pm–12am)	9
