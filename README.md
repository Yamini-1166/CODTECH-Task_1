**Name-** PINISETTI YAMINI           
**Company-** CODTECH IT SOLUTIONS     
**ID-** CT08D58923
**Domain-** C Programming              
**Duration-** OCT-NOV 2024     

## Overview of the project

### Project: QUIZ GAME

### OBJECTIVES:-
The objective of this C code is to create a simple quiz game that presents multiple-choice questions to the user. The program tracks the user's score and provides immediate feedback based on their answers. It aims to test the user's knowledge on various topics through a series of predefined questions.

### KEY ACTIVITIES:-
**Function to Ask Questions:**
The askQuestion function takes in a question, an array of options, and the correct answer.
It displays the question and options, then prompts the user for their answer.
The user's answer is returned for validation.

**Score Tracking:**
An integer variable score is initialized to keep track of the number of correct answers.
After each question, the program increments the score if the user provides the correct answer.

**Questions and Options:**
The program defines multiple questions and their corresponding options as arrays of strings.
Each question is presented to the user through the askQuestion function.

**Answer Validation:**
After the user answers a question, the program checks if the answer is correct.
If the answer is correct, a message is displayed, and the score is incremented.
If the answer is incorrect, the correct answer is provided.

**Final Score Display:**
After all questions are answered, the program displays the user's final score out of the total number of questions.

### Technologies Used:-


**1. C Programming Language:**
Core Technology: The entire program is written in C, a high-level procedural programming language that is widely used for system and application development.

**2. Standard Input and Output (stdio.h):**
Header File: The program uses the standard input/output library, which provides functions for input and output operations, such as printf and scanf.

**3. Functions:**
askQuestion Function: A custom function that displays a question, presents multiple-choice options, and captures the user's answer. This modular approach helps keep the code organized and reusable.

**4. Character Handling:**
User Input Handling: The program reads and processes characters from the user's input using scanf.

**5. Control Structures:**
Conditional Statements: The program uses if-else statements to validate the user's answers and update the score accordingly.
Loops: The program does not use loops directly in the shared code, but loops are common in quizzes for handling multiple questions dynamically.

**6. Array Handling:**
String Arrays: The program uses arrays of strings to store the questions and their respective options, demonstrating basic array manipulation in C.

**7. Basic Data Types:**
Primitive Types: The program utilizes basic data types such as char for characters and int for integers.
