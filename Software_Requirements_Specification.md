# Software Requirements Specification (SRS)

| Field | Value |
|-------|-------|
| **Project Name** | Astro Code |
| **Author** | Jesse Sher |
| **Class** | 10CTC |
| **Date** | Fri Jul 3, 2026 |
| **Version** | 1.0 |
| **GitHub Repository** | [https://github.com/astrogames06/astro-code-app](https://github.com/astrogames06/astro-code-app) |

---

# 1. Introduction

## 1.1 Purpose

This document is the software requirements specification for the Astro Code app. It outlines the functional and non-functional requirements and the system design.

The purpose of this document is to clearly define what the system will do, how it will behave and how the user interacts with it. It is intended to developers and testers involved in the design of the system.

This SRS describes the requirements for the application so that it can be implemented, tested, and maintained in a structured and consistent way.

---

## 1.2 Product Overview

Astro Code is an app that teaches people to create games in Python. The app is made for students and teachers with an in built classroom system to make teaching and learning an ease. It solves the problem for students since it allows them to have a simple application to build, run, test and share games, and for teachers who are then able to assign work and set up classrooms easily.

---

## 1.3 Scope

### In Scope

- User login and signup
- Classroom teacher/student system
- AI chat helper
- Saving user data to database

### Out of Scope

- Online chat
- Live sharing of code
- Payment systems
- Mobile app version

---

## 1.4 Definitions, Acronyms and Glossary

| Term | Definition |
|------|------------|
| SRS | Software Requirements Specification |
| MVP | Minimum Viable Product |
| CRUD | Create, Read, Update, Delete |
| Database | Organised storage of application data |
| Primary Key (PK) | Unique identifier for a record |
| Foreign Key (FK) | Links one table to another |

---

## 1.5 Technology Stack and Platform

- Frontend: React
- Backend: Bun
- Python Execution: Pyodide
- Database: Supabase
- Hosting: Vercel
- Version Control: GitHub
- AI Assistance: Lovable, GitHub Copilot, Cursor, ChatGPT

---

# 2. Overall Description

## 2.1 Product Perspective

Astro Code is a web-based programming platform. It depends on Supabase for storing user data and Vercel for web hosting. It also uses Pyodide to execute the python code.

## 2.2 User Characteristics

### User Type 1

- Description: Teachers wanting to set up an online Python classroom for students.
- Technical Skill: Intermediate.
- Needs: The app provides a classroom system where the teacher can create classrooms for each class and year and assign custom tasks.

### User Type 2

- Description: A student connecting to their teachers classroom.
- Technical Skill: Beginner
- Needs: The app provides a way for the student to connect to teachers classroom and start working on assigned tasks and share them with their teacher and fellow students.

---

## 2.3 Operating Environment

- Browser: Chrome, Edge, Safari, Firefox
- Devices: Laptop, Desktop
- Hosting: Vercel
- Database: Supabase
- Internet Required: Yes

---

## 2.4 Design and Implementation Constraints

- Time: Limited time to design and build the project.
- Budget: No budget available, so only free tools and services were used.
- Free tier limits: The system relies on free-tier services such as Supabase and Vercel, which impose usage and storage limits.
- Other constraints: The application uses specific technologies such as React, Bun, Supabase, and Vercel, which restrict certain implementation options.

---

## 2.5 Assumptions and Dependencies

- Users have a internet connection
- Users have a modern browser
- Users have basic computer skills
- Supabase & Vercel services are still available

---

# 3. Functional Requirements

## 3.1 Functional Requirements List

| ID | Requirement |
|----|-------------|
| FR-1 | The system shall allow users to create an account. |
| FR-2 | The system shall allow users to sign in to their account. |
| FR-3 | The system shall allow teachers to create a classroom. |
| FR-4 | The system shall allow students to join the teachers classroom via a classroom code. |
| FR-5 | The system shall allow teachers to create a new task. |
| FR-6 | The system shall allow teachers to assign a custom task to a specific class. |
| FR-7 | The system shall allow students to view their assigned tasks. |
| FR-8 | The system shall allow students to open the task and complete it. |
| FR-9 | The system shall allow teachers to view the students progress on the task. |
| FR-10 | The system shall allow students to share their project with fellow students. |

---

## 3.2 User Stories

- As a student, I want to join a classroom so that I can access my assigned tasks.
- As a student, I want to view my assigned tasks so that I am able to complete them.
- As a student, I want to create a new game so that I am able to share it with my teacher and fellow students.
- As a teacher, I want to create a new classroom so that I am able to add all my students to it.
- As a teacher, I want to create a new task so that I can assign it to the students to complete.

---

## 3.3 Context / Use Case Summary

1. Teacher creates a new task and assigns it to the class.
2. Student views the assigned task and begins working on it.
3. Student completes the task and submits/shares it with the teacher.
4. Teacher views the student’s progress on the task.
5. Teacher accesses the submitted project via a shared link and tests the game.

# 4. Non-Functional Requirements

| Quality | Requirement |
|---------|-------------|
| Performance | Pages load quickly, python code executes fast. |
| Usability & Accessibility | Simple interface for students and teachers. |
| Security & Privacy | Secure login and secure database. |
| Reliability | Data is saved consistently and retrieved correctly. |
| Maintainability | Clean code structure for easy updates. |

---

# 5. System Design

## 5.1 Data Dictionary

### Table: __________________

| Field | Type | Key | Rules / Notes |
|------|------|-----|---------------|
| | | | |
| | | | |
| | | | |

---

### Table: __________________

| Field | Type | Key | Rules / Notes |
|------|------|-----|---------------|
| | | | |
| | | | |
| | | | |

---

## 5.2 Entity Relationship Diagram (ERD)

Insert your ERD image.

```md
![ERD](images/erd.png)
```

---

## 5.3 Data Flow Diagram (DFD)

### Context Diagram

```md
![Context Diagram](images/context-diagram.png)
```

### Level 1 Diagram

```md
![Level 1 DFD](images/level1-dfd.png)
```

---

## 5.5 User Interface Design

### Home Page

```md
![Home](images/home.png)
```

Purpose:

- 

Key Elements:

- 
- 
- 

---

### Second Page

```md
![Second Page](images/page2.png)
```

Purpose:

- 

Key Elements:

- 
- 
- 

---

### Third Page

```md
![Third Page](images/page3.png)
```

Purpose:

- 

Key Elements:

- 
- 
- 

---

# 6. Quality and Evaluation

## 6.1 Acceptance Criteria

- [ ] FR-1 completed
- [ ] FR-2 completed
- [ ] FR-3 completed
- [ ] FR-4 completed
- [ ] FR-5 completed
- [ ] FR-6 completed

---

## 6.2 Testing Approach

| Test Case | Expected Result | Actual Result | Pass |
|-----------|-----------------|---------------|------|
| | | | ✅ / ❌ |
| | | | ✅ / ❌ |
| | | | ✅ / ❌ |

---

## 6.3 Known Limitations and Future Work

### Known Limitations

- 
- 
- 

### Future Improvements

- 
- 
- 

---

# Appendix (Optional)

## Additional Screenshots

```md
![Screenshot](images/screenshot.png)
```

## References

- GitHub Repository:
- Other References: