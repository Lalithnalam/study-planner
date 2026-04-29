#Study Planner (C++)

This project is a console-based Study Planner developed in C++ that helps students efficiently organize and manage their study schedule based on subject importance, difficulty, and available time.

The application allows users to input subjects along with parameters such as importance (weight), deadline, required study hours, and difficulty level. Based on these inputs, the system generates an optimized day-wise study plan that distributes time effectively across all subjects.

Key Features
Add multiple subjects with relevant details
Edit and delete subject information
Mark subjects as completed
Set total available days and daily study hours
Automatically generate a structured study plan
Displays a clear tabular schedule for each day
Allocates revision time if extra hours are available
Scheduling Logic

The planner follows a structured approach:

Ensures each subject gets minimum daily coverage
Distributes remaining time based on priority:
Priority = Importance / Difficulty
Allocates time across all days evenly
Fills unused time with revision

This ensures balanced preparation while giving more focus to important and difficult subjects.

Technologies Used
C++
Standard Template Library (STL)
Console-based interface
How to Run

Compile the program:

g++ study_planner.cpp -o planner

Run the executable:

./planner
Menu Options
Add subjects
Set study time
Generate study plan
Mark subjects as completed
Edit subject details
Delete subjects
View all subjects
Use Case

This tool is useful for students preparing for exams who want a simple and effective way to manage their study time without manually planning schedules.
