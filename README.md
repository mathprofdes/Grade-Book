# Grade Book

**Download the Current Version (1.2.1)**

**Prerequisite:** If the Java JRE is not installed on your computer download and install the current version of the Java JRE (Version 8 or later).

The software is being distributed as an executable jar file. 

- Download the **[Gradebook.jar](https://github.com/mathprofdes/Grade-Book/releases/download/v1.2.1/Gradebook.jar)** file.
- In most cases you can simply double-click it from your system's file browser. You can also run it from the command-line with
`java -jar Gradebook.jar`

---

**Program Description**

The Grade Book program is simply another electronic grade book for storing and reporting student grades.  With the multitude of grade book programs incorporated into content management systems as well as stand-alone packages the world hardly needs another.  Nonetheless, this is a program I developed a while back and still find useful alongside the other systems. The software was created using the older Java Swing API, so the appearance is a little retro. This software has been tested on Windows 10 and 11, Linux Mint 21, and MacOS Mojave.

**Program Features**

- Point based and percentage grading modes.
- Assignment categories allowing inclusion in average calculations, extra credit, or just tracking without the inclusion in averages.
- Automatic curving from removal of lowers category scores. 
- Mass input of student enrollment from a spreadsheet. 
- Spreadsheet interface for grade input.
- Class grade viewer for all category, assignment, and final averages, including chart displays of raw data and frequency diagrams. 
- An average adjuster to calculate a global curved average based on different target scores. 
- Individual student viewer allowing the view of scores from a single student.  This feature also allows the user to eliminate or change a score (without changing the actual input score) to see a real-time change in the student's final average.  Helps visualize a what-if scenario.  This mode also shields the viewer from all other student scores.
- Note editor for special notes in relation to the course and stored within the grade book file. 
- Copy, saving, and printing options on all chart windows and data sheets.
- Printing and LaTeX export options for class and student reports. 
- Projection calculations for student averages. 

---

**Screenshot**

![Screenshot of program.](/Version_1_2_1/MainWindow.png)

--- 

**Third-Party Software Used**

- Oracle Help for Java: (Oracle): The help system.
- JFreeChart: (by David Gilbert): Renders all of the bar charts in the program.
