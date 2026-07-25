# CodeArena

> A full-stack online coding platform built with Java, Spring Boot, React, Docker, and MySQL, designed to provide a secure and scalable environment for solving programming problems and evaluating code submissions.

---

## Overview

CodeArena is an online coding platform inspired by modern programming practice websites such as LeetCode and HackerRank. The project is focused on building a production-oriented online judge that enables users to solve programming challenges, submit code, monitor their progress, and participate in coding contests.

Rather than being a direct clone of an existing platform, CodeArena is intended to explore real-world software engineering concepts including backend architecture, secure code execution, authentication, database design, and scalable application development.

---

## Objectives

* Design a scalable backend using Spring Boot.
* Build a secure authentication and authorization system.
* Develop a responsive client application.
* Implement a Docker-based online judge.
* Provide problem management and submission tracking.
* Explore software engineering best practices and system design principles.

---

## Planned Features

### User Management

* User registration
* User authentication
* JWT-based authorization
* Profile management
* Role-based access control

### Problem Management

* Problem catalog
* Difficulty classification
* Topic categorization
* Company-specific problem lists
* Search and filtering
* Sample test cases
* Hidden evaluation test cases

### Online Judge

* Secure code execution
* Source code compilation
* Automated test case evaluation
* Execution time measurement
* Memory usage monitoring
* Verdict generation

Supported verdicts include:

* Accepted
* Wrong Answer
* Runtime Error
* Compilation Error
* Time Limit Exceeded
* Memory Limit Exceeded

### Submission System

* Submission history
* Execution reports
* Language-wise submissions
* Performance statistics

### Coding Experience

* Integrated code editor
* Custom input execution
* Boilerplate code generation
* Multi-language support *(planned)*

### Competitive Programming

* Coding contests
* Leaderboards
* Daily challenges
* User rankings

### Community

* Discussion forum
* Editorials
* Bookmarks
* Comments and reactions

---

## Technology Stack

| Layer           | Technologies                                          |
| --------------- | ----------------------------------------------------- |
| Backend         | Java, Spring Boot, Spring MVC, Spring Security        |
| Frontend        | React, JavaScript, HTML, CSS, Tailwind CSS            |
| Database        | MySQL, Hibernate (JPA)                                |
| Authentication  | JWT, BCrypt                                           |
| Code Execution  | Docker                                                |
| Build Tools     | Maven                                                 |
| Version Control | Git, GitHub                                           |
| Deployment      | Docker, Nginx, GitHub Actions, AWS/Render *(planned)* |

---

## Project Architecture

```text
CodeArena/
│
├── backend/
│   ├── authentication/
│   ├── users/
│   ├── problems/
│   ├── submissions/
│   ├── judge/
│   └── configuration/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── assets/
│
├── docker/
├── documentation/
└── README.md
```

---

## Development Roadmap

### Phase 1 — Backend Foundation

* Spring Boot project setup
* REST API development
* User management
* Problem management

### Phase 2 — Data Layer

* Database integration
* Entity relationships
* Persistence using JPA

### Phase 3 — Authentication

* Spring Security
* JWT authentication
* Role-based authorization

### Phase 4 — Frontend

* React application
* API integration
* Responsive user interface

### Phase 5 — Online Judge

* Docker integration
* Secure code execution
* Test case evaluation engine

### Phase 6 — Platform Features

* Leaderboards
* Contests
* User analytics
* Discussion forum
* Advanced search

### Phase 7 — Deployment

* Containerization
* Continuous Integration
* Cloud deployment
* Performance optimization

---

## Learning Objectives

The purpose of this project is to gain practical experience in building large-scale backend applications while strengthening knowledge in:

* Object-Oriented Programming
* RESTful API Design
* Spring Boot
* Spring Security
* Database Design
* Docker
* Software Architecture
* System Design
* Full-Stack Development

---

## Current Status

The project is currently under active development. Features will be implemented incrementally following the roadmap described above.

---

## Future Enhancements

* AI-assisted coding hints
* Contest scheduling
* Real-time code collaboration
* Interview preparation mode
* Plagiarism detection
* Distributed judge workers
* Microservices architecture

---

## License

This project is intended for educational and learning purposes.
