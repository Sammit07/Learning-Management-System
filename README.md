# Learning Management System Using Django

## Project Overview

The Learning Management System (LMS) is a Django-based web application designed to streamline educational processes by providing interactive dashboards for students, tutors, and administrators. This system includes features like attendance tracking, timetable management, a question board, and analytics, which help educational institutions manage student and faculty interactions efficiently.

## Features

- **Admin Dashboard**: Allows administrators to manage users, schedules, and system configurations.
- **Student Dashboard**: Provides students access to course materials, attendance records, schedules, and a question board.
- **Tutor Dashboard**: Enables tutors to manage class materials, attendance, and respond to student questions.
- **Timetable Management**: Displays schedules for students and teachers; administrators can update timetables.
- **Attendance Tracking**: Tutors can mark attendance, and students can view their attendance history.
- **Question Board**: Students can post questions, and tutors can respond, fostering an interactive learning environment.
- **Analytics**: Generates summaries such as attendance reports and other statistics for analysis.

## Technologies Used

- **Backend Framework**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL 

## Project Structure

- **admindashboard/** - Contains files and views for the administrator interface.
- **app/** - Core application logic for the LMS.
- **assets/** - Contains additional assets such as images, custom JavaScript, or CSS files.
- **learning management system using django/** - Root directory with Django project settings and configurations.
- **static/** - Static files (CSS, JavaScript) accessible by the application.
- **studentdashboard/** - Handles the student interface and associated views.
- **templates/** - HTML templates for rendering different views and pages in the application.
- **tutordashboard/** - Manages tutor-specific functionality and views.
- **manage.py** - Django’s command-line utility for managing and running the project.

## Getting Started

### Prerequisites

To run this project, ensure you have:
- **Python** 3.8 or higher
- **Node.js** and **npm** (optional, if additional frontend packages are used)
- **MySQL** (or your choice of relational database, if different)

### Installation and Setup

# 1. Navigate to the Project Directory
cd Learning-Management-System

# 2. Set Up Python Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# 4. Install Dependencies
pip install -r requirements.txt

# 5. Configure Environment Variables
# SECRET_KEY=your_secret_key
# DEBUG=True
# DB_NAME=your_database_name
# DB_USER=your_database_user
# DB_PASSWORD=your_database_password

# 6. Apply Migrations
python manage.py migrate

# 7. Run the Development Server
python manage.py runserver
