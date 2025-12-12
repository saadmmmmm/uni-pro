# 🎓 Student Management System

## 📁 Project Files
| File | Description |
|------|-------------|
| `saad.html` | Login page for the system |
| `home.html` | Main dashboard / home page |
| `database.sql` | MySQL database schema |

## 🗄️ Database Structure
The system uses 3 main tables:

### 1. Students Table
- `student_id` (Primary Key)
- `first_name`
- `last_name`
- `email`
- `enrollment_date`

### 2. Courses Table  
- `course_id` (Primary Key)
- `course_name`
- `course_code`
- `credits`

### 3. Enrollments Table
- `enrollment_id` (Primary Key)
- `student_id` (Foreign Key)
- `course_id` (Foreign Key)
- `semester`
- `grade`

## 🚀 How to View
1. Open `saad.html` in any web browser
2. Or visit: https://saadmmmmm.github.io/uni-pro/saad.html

## 👨‍💻 Developer
**Saad** - Student Project



## Setup Instructions

1. Import `database.sql` into MySQL.
2. Configure database connection in your PHP/backend files.
3. Open `saad.html` in a web browser.
