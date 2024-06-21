# Quiz

This Project implements a simple quiz game with two difficulty levels (easy and hard). 

**QuizGame Class**:
Manages the questions and score.
display_question function shows the question and answer options.
run_quiz function iterates through questions, checks user answers, and updates the score.

**Question Datasets**:
Two lists (easy_questions and hard_questions) store question details like text, options, and correct answer index.

**Difficulty Selection**:
Prompts the user to choose between "easy" and "hard" difficulty.
Based on the choice, selects the corresponding question set.

**Shuffling Questions**:
Shuffles the chosen question set (selected_questions) to randomize the order.

**Creating QuizGame Instance**:
Creates a QuizGame object with the shuffled question set.

**Running the Quiz**:
Calls the run_quiz function to start the game loop.
This code provides a basic structure for a text-based quiz game that can be extended with features like keeping track of high scores, adding time limits, or incorporating different question types.


