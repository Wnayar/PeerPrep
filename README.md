## William Nayar — Contribution

This repository contains my implementation of the Question Service microservice, developed as part of a distributed microservices architecture.

Key contributions:

- Developed Question Service microservice exposing 15 REST API endpoints using Express.js and TypeScript
- Designed MongoDB schemas supporting efficient storage and retrieval of coding questions
- Populated database with 300+ interview questions using the TACO dataset
- Implemented filtering, querying, and aggregation pipelines to support efficient question retrieval
- Tested REST API endpoints using Postman validating request handling, response correctness, and error handling
- Integrated Question Service into distributed microservices architecture enabling independent deployment and scalability
- Collaborated using Git branching workflow, pull requests, and Agile development practices

Tech Stack: Node.js • Express.js • TypeScript • MongoDB Atlas • Mongoose • Postman

---

## Contributors

This project was developed collaboratively by:

- William Nayar — https://github.com/Wnayar  
- Lu Bolin — https://github.com/LuBolin  
- BlazeChron — https://github.com/BlazeChron  
- TheOnlyJuan — https://github.com/TheOnlyJuan  
- darHH — https://github.com/darHH  

---

## Group: Gxx

## Project Overview

PeerPrep is a collaborative coding platform that matches users to solve coding questions together in real-time.

This platform demonstrates distributed system design using microservices architecture, scalable backend services, and modern frontend engineering practices.

---

## Core Features

### 1. User Authentication
- Users register and log in via Firebase Authentication
- Session management through backend user service

### 2. Question Filtering
- Filter coding questions by difficulty level
- Filter by topics of interest
- Powered by Question Service microservice and MongoDB aggregation pipelines

### 3. Matchmaking System
- Users click "Find Match" to enter matchmaking queue
- Server matches users with similar preferences
- Real-time matching algorithm

### 4. Collaborative Coding Room
- Shared real-time coding environment
- Similar to LeetCode-style collaborative coding platforms
- Real-time collaborative code editing
- Shared workspace for solving problems together

---

## Architecture

PeerPrep follows a distributed microservices architecture enabling modular development and scalable backend systems.

### Frontend
- React
- TypeScript
- Vite
- Component-based architecture

### Backend Services

Microservices architecture with independently deployable services:

- User Service  
  Authentication and user management  

- Question Service *(My contribution)*  
  - REST API exposing 15 endpoints  
  - MongoDB schema design  
  - Query filtering and aggregation pipelines  
  - Interview question retrieval and management  

- Additional planned services:
  - Matching Service
  - Collaboration Service

### Database
- MongoDB Atlas
- Mongoose schema modeling
- Aggregation pipelines for efficient querying

### Authentication
- Firebase Authentication

---

## Microservices Design Principles

This system demonstrates key distributed systems principles:

- Independent service deployment
- Clear API boundaries between services
- Stateless backend services
- Scalable system architecture
- Modular backend design

---

## Question Database

The Question Service uses data from the TACO dataset.

License: Apache-2.0  
Dataset: https://huggingface.co/datasets/BAAI/TACO  
Copyright: Beijing Academy of Artificial Intelligence (BAAI)

Database populated with 300+ coding interview questions.

---

## Engineering Focus

This project demonstrates:

- Microservices architecture design
- REST API backend development using Express.js and TypeScript
- MongoDB schema design and aggregation pipelines
- Distributed systems integration
- Scalable backend engineering practices
- API testing and validation using Postman

---
