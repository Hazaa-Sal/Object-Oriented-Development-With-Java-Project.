# Course Recovery System

This Java desktop application supports academic staff in reviewing student progress and managing course recovery. Its Swing interface includes user login and role-based navigation for course administrators and academic officers, academic reports, eligibility checks, and course recovery plans.

## Features

- Role-aware access to course administration and academic officer workflows.
- Student, course, grade, and recovery data loaded from local text and CSV files.
- Eligibility evaluation and course recovery planning with milestones and recommendations.
- Academic reporting with console, text, and PDF export options.
- Optional email notifications and report delivery.
- Maven-based build with Jakarta Mail, Jakarta Activation, and iText dependencies.

## Repository contents

The Java project is packaged in `Object-Oriented-Development-With-Java.zip`. Extract it to access the Maven project directory `OODJ_Group8_Implementation/`, which contains `pom.xml`, application source, and sample data files. The repository also includes the assignment brief as `Object-Oriented-Development-With-Java.docx`.

## Requirements

- JDK 24, as specified by the Maven compiler configuration.
- Apache Maven.
- A graphical desktop environment for the Swing application.

## Build and run

1. Clone or download the repository and extract `Object-Oriented-Development-With-Java.zip`.
2. Open a terminal in `OODJ_Group8_Implementation/`.
3. Build the application and download its declared dependencies:

   ```bash
   mvn clean package
   ```

4. Launch the Swing application with Maven:

   ```bash
   mvn exec:java
   ```

The Maven configuration sets `crs.MainGUI` as the entry point. The application reads and updates local data files, so run it from the extracted project directory. Email delivery depends on mail settings configured in the application; no credentials are supplied in this README.

## License

No license is included in the repository, so reuse is subject to the copyright holder's permission.
