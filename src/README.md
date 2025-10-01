# Mergington High School Activities

A comprehensive web application that allows teachers to manage student registration for extracurricular activities at Mergington High School.

## Features

### For Students & Teachers
- **View Activities**: Browse all available extracurricular activities with detailed information including schedules, descriptions, and current enrollment
- **Advanced Filtering**: Filter activities by multiple criteria:
  - **Category**: Sports, Arts, Academic, Community, Technology
  - **Day of Week**: Monday through Sunday, including weekend activities
  - **Time of Day**: Before school (morning), after school (afternoon), weekend sessions
- **Search**: Real-time search through activity names and descriptions
- **Activity Details**: View participant limits, current enrollment, and detailed schedules

### For Teachers (Authentication Required)
- **Secure Login**: Teacher authentication system with role-based access
- **Student Registration**: Register students for activities using their school email
- **Student Management**: Remove students from activities when needed
- **Registration Validation**: Prevent duplicate registrations and enforce participant limits

### Activity Categories
The system supports diverse extracurricular activities including:
- **Sports**: Soccer Team, Basketball Team, Morning Fitness
- **Arts**: Art Club, Drama Club
- **Academic**: Math Club, Debate Team, Science Olympiad
- **Technology**: Programming Class, Weekend Robotics Workshop
- **Community**: Chess Club, Manga Maniacs
- **Competition**: Sunday Chess Tournament

## Technology Stack

- **Backend**: Python with FastAPI framework
- **Database**: MongoDB with in-memory collections
- **Frontend**: HTML, CSS, JavaScript (vanilla)
- **Authentication**: Secure password hashing with Argon2
- **API**: RESTful endpoints with automatic documentation

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
