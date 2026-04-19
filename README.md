# School Task Management System

A secure, role-based web application for managing academic tasks, assignments, and student progress. Built with HTML, CSS & JS, this system enables teachers to create and distribute assignments while allowing students to submit work, track attendance, and monitor performance metrics.

## Overview

This project addresses the need for a centralized digital platform to streamline task management in educational settings. It implements secure authentication, role-based access control, and file handling workflows while applying web security best practices to protect sensitive academic data.

## Features

### User Roles and Access Control
- Teacher accounts: Create assignments, manage lectures, review submissions, track student progress
- Student accounts: View assigned tasks, submit files, monitor attendance and performance
- Secure authentication with password hashing and session management
- Role-based authorization to enforce permission boundaries

### Task and Assignment Management
- Assignment creation with descriptions, deadlines, and attached resources
- File upload functionality with validation and controlled access
- Task submission workflows with status tracking (pending, submitted, graded)
- Comment and feedback system for teacher-student communication

### Student Progress Tracking
- Attendance recording and visualization
- Task completion metrics and performance analytics
- Grade management and report generation
- Dashboard views for both teachers and students

### Security Implementation
- Input validation and sanitization to prevent injection attacks
- CSRF protection using Django's built-in middleware
- Secure file upload handling with type and size restrictions
- HTTPS-ready configuration and secure cookie settings
- Protection against common OWASP Top 10 vulnerabilities

## Technologies Used

- SQLite (development) / PostgreSQL (production-ready)
- HTML5, CSS3, JavaScript for frontend

## Prerequisites

- SQLite (included) or PostgreSQL for production

## Usage Examples

- Teacher Workflow
  1. Log in with teacher credentials
  2. Navigate to "My Assignments" to create a new task
  3. Set title, description, deadline, and attach resources
  4. View student submissions and provide feedback
  5. Export progress reports for class performance analysis
- Student Workflow
  1. Log in with student credentials
  2. View assigned tasks on the dashboard with deadline indicators
  3. Submit files through the validated upload form
  4. Track attendance records and completion status
  5. Review graded assignments and teacher feedback

## License

- This project is provided for educational purposes. Feel free to use, modify, and distribute with attribution.

## Authors

- Youssef Mohamed Abdelsamea (@z00xINe)
