# 💻👨🏻‍💻📝 Online Judge Platform

Welcome to the Online Judge Platform, an advanced system where users can solve coding problems and improve their programming skills. The project is structured into three main components:

**1] Primary Backend**: Manages user authentication, problem listings, and solution submissions.

**2] Judge Server**: Handles asynchronous execution of user code submissions.

**3] Judger**: Executes code submissions inside Docker containers, ensuring programs stay within specified time and memory limits.

## Table of Contents
- [System Diagram](#SystemDiagram)
- [Features](#Features)
- [Repositories](#Repositories)

# System Diagram
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

![System Diagram](https://github.com/user-attachments/assets/be79d301-a9cf-4dd7-aadf-68ed4ab5f17c)

## Features

- **User Authentication**: Secure login and registration functionalities.

- **Problem Listings**: A comprehensive list of coding problems for users to solve.

- **Solution Submissions**: Users can submit their solutions to the problems.

- **Asynchronous Execution**: Solutions are executed asynchronously to ensure scalability.

- **Dockerized Judging**: Code submissions are run in isolated Docker containers to ensure security and resource management.

- **Verdict Generation**: The system provides detailed feedback on submissions, including pass/fail status, time, and memory usage.

## Repositories
The project is divided into three separate repositories for better modularity and maintenance. Follow the installation instructions in each repository to set up the components.:

### 1] Primary Backend
- **Repository** : [Primary Backend Repo](https://github.com/AbhishekBhosale46/OnlineJudge-PrimaryBackend)
- **Description**: This repository contains the core backend of the platform. It manages user authentication, problem listings, and solution submissions. It uses Django Rest Framework to create secure and scalable RESTful APIs.

### 2] Judge Server
- **Repository** : [Judge Server Repo](https://github.com/AbhishekBhosale46/OnlineJudge-JudgeServer)
- **Description**: This repository contains the server responsible for the asynchronous execution of user code submissions. It is built using FastAPI and utilizes RabbitMQ for task assignment and horizontal scalability of workers.

### 3] Judger
- **Repository** : [Judger Repo](https://github.com/AbhishekBhosale46/OnlineJudge-Judger)
- **Description**: This repository contains the judger system designed to compile and run C++, Java, and Python programs inside Docker containers. It ensures programs stay within specified time and memory limits, handles cleanup of generated files and artifacts, and compares input files with expected and actual output to provide appropriate verdicts.


## Contributing

Contributions are welcome! Please follow the guidelines in the respective repositories.
