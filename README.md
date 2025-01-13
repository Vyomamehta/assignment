# Full-Stack Web Application with Frontend, Django Chat, and AWS Lambda Functions

## Overview

This project is a full-stack web application that includes:

1. **Frontend Development**: A responsive webpage with a fixed navbar, collapsible left menu, and a dynamic layout that adjusts based on screen size.
2. **Django Chat Application**: A chat system where users can sign up, log in, and initiate real-time conversations with other users. All messages are stored and retrieved from a database, using WebSockets for real-time communication.
3. **AWS Lambda Functions**: Two AWS Lambda functions:
   - One that adds two numbers and returns the result.
   - Another that stores a document or PDF file in an S3 bucket.

## Table of Contents

1. [Frontend Development](#frontend-development)
2. [Django Chat Application](#django-chat-application)
3. [AWS Lambda Functions](#aws-lambda-functions)

### 1. Frontend Development

**Features**
- **Fixed Navbar**
- **Three Sections**: Left Menu, Main Content, Right Panel
- **Responsive Design**

**Steps to Run**
- Create an HTML file with the provided HTML, CSS, and JavaScript code.
- Implement responsive design using JavaScript to adjust the page width based on the screen size.

### 2. Django Chat Application

**Features**
- **User Authentication**
- **Real-Time Messaging** using WebSockets
- **Database Storage** for Users and Messages

**Steps to Run**
- Install required dependencies: `pip install django channels channels_redis`
- Set up Django, Channels, and Redis.
- Run the server: `python manage.py runserver`

### 3. AWS Lambda Functions

**Features**
- **Lambda Function for Addition**
- **Lambda Function to Upload Files to S3**

**Steps to Run**
- Create Lambda functions in AWS Console.
- Invoke them via API Gateway or AWS CLI.

## Conclusion
This project demonstrates a full-stack web application integrating **frontend development**, **real-time chat functionality with Django and WebSockets**, and **AWS Lambda functions** for serverless computing.
