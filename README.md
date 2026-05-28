<<<<<<< HEAD
# IntelliSeat - Exam Hall Seating Management System

IntelliSeat is a Java + JavaFX desktop application for automating exam hall seating management with MySQL using JDBC.

## Tech Stack
- Java
- JavaFX
- JDBC
- MySQL

## Features Implemented
- Login page with demo validation (`admin` / `admin123`)
- Dashboard with left-side navigation
- Student Management (Add, Update, Delete, Search)
- Exam Management (Add and View exam schedules)
- Shift & Timing Management
- Seating Arrangement Generation
  - Hall-wise seat allocation
  - Moves to next hall when current hall is full
  - Tries to avoid adjacent students from same department
- Input validation, alerts, confirmations
- Organized code structure (MVC + DAO)

## Project Structure
```
IntelliSeat/
src/
 ├── ui/
 │    ├── MainApp.java
 ├── controller/
 │    ├── LoginController.java
 │    ├── DashboardController.java
 │    ├── StudentController.java
 │    ├── ExamController.java
 │    ├── SeatingController.java
 │    ├── ShiftController.java
 ├── model/
 │    ├── Student.java
 │    ├── Exam.java
 │    ├── Seating.java
 │    ├── Shift.java
 ├── dao/
 │    ├── StudentDAO.java
 │    ├── ExamDAO.java
 │    ├── SeatingDAO.java
 │    ├── ShiftDAO.java
 ├── util/
 │    ├── DBConnection.java
resources/
 ├── fxml/
 │    ├── login.fxml
 │    ├── dashboard.fxml
 │    ├── students.fxml
 │    ├── exams.fxml
 │    ├── seating.fxml
 │    ├── shifts.fxml
 ├── css/
 │    └── style.css
database/
 └── schema.sql
README.md
```

## Database Setup
1. Start MySQL server.
2. Run `database/schema.sql`.
3. Update credentials in `src/util/DBConnection.java`:
   - URL
   - USERNAME
   - PASSWORD

## Run Notes
- Ensure JavaFX SDK is configured in your IDE.
- Add MySQL JDBC driver to project libraries.
- Run `ui.MainApp`.

## Theme Applied
- Background: Blue
- Main: Navy Blue
- Accent Buttons: Royal Blue
- Secondary Background: Grey
- Text: Dark Grey
- Font: Times New Roman
=======
# Exam-Hall-Seating-Management-System
IntelliSeat automates exam seating by assigning students to seats based on room capacity while separating same-branch students. It manages student and exam data, supports multiple shifts, and generates seating using arrays, structures, and 2D matrices with greedy and round-robin logic.
>>>>>>> 24e8ad9911c21d94a2e566e5e98b87a57f9ae9cd
