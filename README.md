# QuickPyQuiz
"An interactive Python quiz project where users can challenge themselves with dynamic questions. Features multiple-choice questions,  and score tracking."

This README provides an overview and explanation of the Quiz Application code.
1. Overview
The Quiz Application is a Python script designed to test users with a series of multiple-choice questions. Each question has a prompt, a set of answer choices, and one correct answer. The user's answers are compared to the correct answer, and their score is calculated based on how many questions they answer correctly.
2. Structure of the Code
Questions List
The script begins by defining a list of questions, where each question is represented as a dictionary. Each dictionary contains the following keys:
- 'prompt': The question text that will be displayed to the user.
- 'choices': A list of possible answer options for the user to choose from.
- 'answer': The correct answer choice, represented by one of the options (A, B, C, or D).
run_quiz Function
The run_quiz function is responsible for executing the quiz. It performs the following steps:
1. Initializes the user's score to 0.
2. Iterates over each question in the list and displays the prompt and choices.
3. Collects the user's input and checks if it matches the correct answer.
4. Provides feedback on whether the user's answer was correct or incorrect.
5. Updates the user's score if the answer is correct.
6. After all questions are answered, it displays the user's final score.
3. How to Run the Code
To run the Quiz Application, follow these steps:
1. Ensure Python is installed on your system.
2. Copy the provided code into a Python (.py) file.
3. Run the script in your terminal or IDE of choice.
4. The quiz will start immediately, displaying each question and asking for your answer.
4. Customizing the Quiz
You can modify the questions in the 'questions' list by adding or removing questions. Each question should follow the same dictionary format, with 'prompt', 'choices', and 'answer' keys.
