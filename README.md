Overview:

This project is a C# Windows Forms application designed to make it easier for residents to report municipal issues, upload supporting files, and share feedback on their overall experience.
The application stores reports and ratings in memory using the AppState class, making it simple and lightweight while still providing all the core functionality.

Requirements:

To build and run the project, you will need:
•	Windows 10/11 (or any version that supports .NET desktop applications)
•	Visual Studio 2019/2022 (Community Edition or higher)
•	.NET Framework 4.7.2 (or later)

Main Features:

•	Report issues with details like location, category, and description
•	Upload multiple attachments (images/documents)
•	A progress bar that updates as you complete the form
•	Generate a unique reference ID when submitting an issue
•	Rate your experience (Poor to Excellent) after submitting
•	Link feedback directly to reported issues

How to Compile:

1.	Clone or download the repository: git clone https://github.com/your-username/PROG3BPOEP1.git
2.	Open the solution file PROG3BPOEP1.sln in Visual Studio.
3.	Set PROG3BPOEP1 as the startup project.
4.	Build the solution by pressing Ctrl+Shift+B or going to:
Build > Build Solution.

How to Run:

•	Press F5 (Run with Debug) or Ctrl+F5 (Run without Debugging).
•	The application will open on the Main Menu (if implemented). From here, you can:
1.	Report a new issue
2.	View events announcements 
3.	Service request Status

Using the Application (Part 1):

1. Reporting an Issue
•	Enter the location of the problem.
•	Select a category (e.g., Sanitation, Roads, Utilities, Parks, Public Safety, or Other).
•	Provide a brief description.
•	(Optional) Upload images or documents to support your report.
•	Watch the progress bar as you complete each section.
•	Click Submit to send the issue.
2. Rating Your Experience
•	After submitting an issue, the Rate Your Experience form will appear.
•	Choose a rating 
•	Click Submit Feedback.
•	You’ll receive a thank you message and be taken back to the Main Menu.

// This application was developed as part of the PROG3B Portfolio of Evidence.
