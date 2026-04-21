# Quiz Game

A console-based trivia application built with Python, utilizing OOP to manage question data and game logic independently.

## Key Features
- Custom Question Modeling: Uses a Question class to standardize data input (text and answer).
- Centralized Game Engine: The QuizBrain class handles score tracking, question sequencing, and user input validation.
- Dynamic Data Loading: Easily expandable question bank through the data.py module.
- Minimalist Interface: Clean, text-based UI designed for distraction-free interaction.

## Technical Implementation
The project is designed to keep data and logic strictly separated:
- question_model.py: The blueprint for individual question objects.
- quiz_brain.py: Contains the logic for checking answers, tracking the current question number, and maintaining the  user's score.
- main.py: The entry point that initializes the question bank and runs the game loop.

## Core Logic
The game uses a while loop that continues as long as quiz.still_has_questions() returns True. This ensures the game scales automatically regardless of how many questions are added to the data set.

## How to Run:
1. Clone the repository: git clone https://github.com/janice-1705/Quiz_Game.git
2. Navigate to the project directory and run: python main.py
3. Follow the on-screen prompts to answer "True" or "False" to the trivia questions.
