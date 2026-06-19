# Online Quiz System (Java Console Application)

## Overview

This project is a console-based Online Quiz System developed in Java. It allows users to register, select subjects and difficulty levels, attempt quizzes, and view their results and quiz history.

The system is built using Object-Oriented Programming (OOP) principles such as abstraction, inheritance, and encapsulation, along with collections and exception handling.


## Features

- User registration with validation
- Login using registration number and password
- Subject selection (Math, Science, History, Geography, Literature, General Knowledge)
- Difficulty level selection (Easy, Medium, Hard)
- Dynamic quiz generation based on subject and difficulty
- Score calculation after quiz completion
- Quiz history tracking for each user
- Input validation for secure and clean interaction
- Error handling for stable execution


## Technologies Used

- Java (Core Java)
- Object-Oriented Programming (OOP)
- Java Collections Framework (List, ArrayList)
- Scanner for user input
- Console-based application

---

## OOP Concepts Implemented

### Abstraction
- `User` is an abstract class defining the structure of system users.

### Inheritance
- `RegularUser` extends `User` and adds quiz-related functionality.

### Encapsulation
- User credentials and quiz data are protected using private/protected access modifiers.

## Class Structure

### User (Abstract Class)
- registrationNumber
- password
- Abstract method: displayRole()

### RegularUser
- Stores quiz history
- Methods:
  - viewProfile()
  - addQuizToHistory()
  - showQuizHistory()

### Quiz Class
- category
- difficultyLevel
- questions, options, correctAnswers
- Methods:
  - addQuestion()
  - getQuestions()
  - getOptions()
  - getCorrectAnswer()

### Onlinequiz (Main Class)
- Handles user interaction
- Manages quiz flow
- Generates questions dynamically
- Calculates score
- Displays results

your-username/online-quiz-system.git
