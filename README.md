# Curriculum Automation

## Project Overview

Curriculum Automation streamlines key academic tasks such as course code allocation, LTPC validation, duplicate prevention, exam pattern assignment, and syllabus entry. The system automates the process, improving efficiency, reducing manual errors, and saving time in curriculum management and planning.

## Project Information

- **Student Name**: PRIYADHARSHINI S
- **Roll No**: 7376221SE139
- **Seat No**: 171
- **Project ID**: 30
- **Project Title**: Curriculum Automation

## Technical Components

**Component Tech Stack (LAMP):**
- **Linux**: The operating system hosting the server environment.
- **Apache**: The web server that handles HTTP requests and serves web content.
- **MySQL**: The relational database system storing curriculum data like courses, syllabi, and exam patterns.
- **PHP**: The server-side scripting language for backend logic, interacting with the database, and generating dynamic web pages.

## Workflow Timeline

| Phase   | Deadline   | Status       | Stage                               |
| ------- | ---------- | ------------ | ----------------------------------- |
| Stage 1 | 24/07/2024 | In Review    | Planning & Requirement Gathering    |
| Stage 2 | Ongoing    | In Progress  | Design & Prototyping                |
| Stage 3 | Ongoing    | In Progress  | Backend Development                 |
| Stage 4 | Ongoing    | In Progress  | DB Design & Implementation          |
| Stage 5 | Not Started| Not Started  | Integration & Testing               |
| Stage 6 | Not Started| Not Started  | Deployment                          |

## Problem Statement

Curriculum Automation includes the following modules:
1. **Course Code Allocation**: Assigns unique identifiers to each course, ensuring clear tracking and management.
2. **Checking LTPC**: Verifies the distribution of Lecture, Tutorial, Practical hours, and Credits for each course to meet academic standards.
3. **Avoiding Duplicates**: Prevents multiple courses from having the same code, ensuring data integrity.
4. **Exam Pattern Assignment**: Defines the structure and format of assessments, ensuring consistent and fair evaluations.
5. **Syllabus Entry**: Inputs detailed course information, including curriculum content, learning objectives, and weekly topics, into the academic system.

## Features

- **Course Code Allocation**: Assign unique course codes to ensure no duplication.
- **LTPC Checking**: Verify correct distribution of Lecture, Tutorial, Practical, and Credit hours.
- **Duplicate Prevention**: Avoid courses sharing the same code.
- **Exam Pattern Assignment**: Define exam types, grading criteria, and assessment weightage.
- **Syllabus Entry**: Input and manage detailed curriculum information.

## Implementation Strategy

1. **Requirement Analysis**: Gather and analyze requirements for code allocation, LTPC verification, duplicate avoidance, exam pattern assignment, and syllabus entry.
2. **System Design**: Develop system architecture, user interfaces, and database schema. Create flowcharts and wireframes.
3. **Development**: Build features for all modules, including code allocation, LTPC checking, and more.
4. **Testing**: Conduct unit, integration, and user acceptance testing.
5. **Deployment**: Deploy the system, migrate data, and train users.
6. **Maintenance and Support**: Monitor system performance, address issues, and provide updates.
7. **Documentation**: Prepare user manuals and technical guides.

## Use Cases

- **Course Code Generation**: An academic administrator inputs a new course, and the system generates a unique code automatically.
- **LTPC Validation**: The system checks LTPC values against predefined standards to ensure compliance with academic requirements.
- **Duplicate Detection**: The system checks for existing courses with the same code or title to prevent duplicates.
- **Exam Pattern Assignment**: Instructors define assessments, weightage, and grading rubrics, which integrate with the course management system.
- **Syllabus Entry**: Course coordinators input syllabus details into a centralized database for easy access and updates.

## LTPC Calculation

LTPC stands for Lecture (L), Tutorial (T), Practical (P), and Credit (C), representing the workload and credit value of a course. The credit calculation typically follows this formula:

**Total Credits (C) = L + (T / 2) + (P / 2)**

- **Lecture (L)**: Number of lecture hours per week (1 hour per week = 1 credit).
- **Tutorial (T)**: Number of tutorial hours per week.
- **Practical (P)**: Number of practical or lab hours per week.

## Flowcharts

- **Admin Curriculum Automation Flowchart**: [Add flowchart image or link here]
- **Student Curriculum Automation Flowchart**: [Add flowchart image or link here]

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
