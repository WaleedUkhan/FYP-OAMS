# Online Attendance Managment App

Online Attendance Managment App is a web application designed to manage attendance for students. It provides features to mark attendance, view attendance history, and manage user records.

## Features

- **User Authentication**: Secure login and registration for users.
- **Attendance Marking**: Admin/users can mark attendance for a students for each day.
- **View Attendance**: Users can view their own attendance records, including present, absent, and leave statuses.
- **Data Export**: Export attendance records in excel format i.e: CSV.
- **Search and Filter**: Search attendance by user name, date.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript (React.js, NEXT.js, plain JS)
- **Backend**: Node.js, Express.
- **Database**:  MySQL
- **Authentication**: JWT (JSON Web Tokens), bcrypt, js-cookie
- **Other Libraries**: xlsx, mysql2


## Usage

### Admin Features

- **Approve or Reject**: Admin can log into the application and approve/reject attendance marked/requested.
- **View Reports**: Admin can view attendance reports for the specific user and can export them to CSV or xlsx.
- **Mark working days**: Admin can mark a date as working day so that user, students, can mark their attendance.



### Regular User Features

- **Mark Attendance**: Users can log in and mark their individual attendance.
- **View Attendance**: Users check their individual attendance records, including history.
- **Leave Requests**: users can request for leave for specific dates.
- **Profile Picture**: users can add their profile picture.

## API Documentation

The backend exposes a REST API to handle various requests. Here are some of the key endpoints:

- `POST /api/auth/signIn(or signup)` – Login/signup to the system.For Login use:  http://localhost:3000/auth/signIn ,
 for Register use: http://localhost:3000/auth/signUp 
- `GET /api/viewRecords` – Get attendance data for a specific user.
- `POST /api/markAttendance` – Mark attendance for a specific user. 

<!-- Remaining Works -->

-Deployment
-check working by real users
-Take Help/discuss with teacher. 

