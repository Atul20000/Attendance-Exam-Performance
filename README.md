Attendance & Exam Performance 

📌 Project Overview :-

This is an interactive Attendance & Exam Performance Dashboard developed using Power BI, SQL Server, Python (pandas), and Excel for backend data processing. 
It provides complete insights into student attendance, exam results, professor performance, and growth metrics. 
The data was cleaned and transformed in SQL Server and Python (pandas) before being loaded into Power BI for advanced visualization with complex DAX measures.


📊 Key Insights :-

Data Processing (SQL Server + Python + Excel):

Data cleaning and preprocessing (removing duplicates, handling nulls).

Joining multiple tables (Students, Attendance, Exams, Professors, Courses).

Aggregating attendance % and exam scores.

Creating calculated fields for pass %, average exam score, assignment tracking.


Power BI Visualization:

KPI Cards :-Total Students, Overall Present Status, Overall Absent Status.
Pass % & Avg Exam Scores by course.

Attendance Analysis:-Daily & Monthly Attendance Trends with line charts.
Present vs. Absent by Course – bar chart comparison.
Course vs. Weekly Attendance % – detailed matrix view.
At-Risk Students (low attendance flagged dynamically).

Exam Performance Analysis:-Hardest & Easiest Courses by average scores.
Top 10 Students by Exam Score.
Course–Professor Performance Overview (pass %, avg. score, total exams).
Pass % vs. Avg Score by Course.

Integrated Insights (Attendance + Exams):-High Attendance but Low Exam Score Students (consistency issue).
Low Attendance but High Exam Score Students (potential fast learners).
Students Submitting Assignments but Failing Exams (need intervention).

Growth & Quality Analysis:-Dropouts per Month vs. Admissions per Month.
Professor Success Rate – teaching impact comparison.
Online vs. Offline Exam Performance.
Average Score & Attendance % by City.
Pass % by Attempt Group (1st vs. 2nd/3rd attempts).


Complex DAX Functions Used:- CALCULATE() with FILTER() for dynamic conditional aggregations.

SWITCH() for course difficulty classification (Hardest/Easiest).

RANKX() to identify Top 10 Students by Score.

DIVIDE() with error handling for pass % and averages.


🛠 Tools & Technologies Used :-

SQL Server – Data storage, joins, preprocessing, and aggregation.

Power BI Desktop – DAX modeling, KPIs, interactive dashboards.

Python (pandas) – Advanced data cleaning, reshaping, and validation.

Excel (CSV) – Base data input and initial formatting.


🎯 Objectives :-

Track attendance % trends at student, course, and professor levels.

Identify at-risk students with low attendance or exam performance.

Compare attendance vs. exam scores for performance improvement.

Evaluate professor effectiveness using pass % and average scores.

Monitor institution growth via admissions, dropouts, and feedback.


📸 Dashboard Screenshots :-

Attendance Tracker – Daily & Course Attendance.:-https://github.com/Atul20000/Attendance-Exam-Performance/blob/main/Attendance%20Tracker.png

Attendance Insights – Monthly, Weekly, and At-Risk Students:- https://github.com/Atul20000/Attendance-Exam-Performance/blob/main/Attendance%20Insights.png

Exam Performance – Hardest/Easiest Courses, Top Students, Professor Overview.:-https://github.com/Atul20000/Attendance-Exam-Performance/blob/main/Exam%20Performance.png

Attendance & Exam – Assignment vs. Exam Failures, High/Low Patterns.:-https://github.com/Atul20000/Attendance-Exam-Performance/blob/main/Attendance%20%26%20Exam.png

Growth & Quality – Admissions, Dropouts, City & Mode-wise Analysis.:-https://github.com/Atul20000/Attendance-Exam-Performance/blob/main/Growth%20%26%20Quality.png


📌 Future Improvements :-

Build Predictive Models (ML) using historical attendance & scores to predict failures.

Integrate Student Feedback NLP Analysis for course/professor insights.

Add Automated Alerts for at-risk students via email/SMS.

Develop a Mobile Version of Dashboard for real-time tracking by professors & students.

