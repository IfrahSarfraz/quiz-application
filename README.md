
# Quiz App

This is a simple Quiz Application built using HTML, CSS, and JavaScript. The app presents multiple-choice questions to users and provides immediate feedback. It tracks the user's selections, calculates scores, and provides a summary of the quiz results at the end.

## Screenshots
![website img](https://github.com/user-attachments/assets/17b6fe6b-bcf6-48e0-8445-03e6681b9e96)

## Demo

Check out the live demo of the dashboard [here](https://ifrahsarfraz.github.io/quiz-application/).
## Features

- Timer: Each question has a 15-second timer.
- Progress Bar: Shows the progress of the quiz.
- Multiple-Choice Questions: Users can select from multiple options.
- Feedback: Correct answers are highlighted in green, wrong answers in red.
- Score Summary: At the end of the quiz, the total score, attempted, unattempted, and wrong answers are displayed.
- Replay and Exit Options: Users can replay the quiz or exit at the end.

## Installation

To run this project locally, you can simply clone the repository and open `index.html` in your web browser.
git clone https://github.com/IfrahSarfraz/quiz-application
open index.html


## Usage

1. Start the Quiz: Click on the 'Start' button to begin.
2. Read Instructions: Review the quiz rules and click 'Start Quiz'.
3. Answer Questions: Select an option for each question. Click 'Next' to move to the next question.
4. View Results: At the end, the result card will display your score, attempted, unattempted, and wrong answers. You can choose to replay or exit the quiz.

## Code Overview

- HTML: Defines the structure of the quiz app, including buttons, containers, and result display.
- CSS: Styles the quiz app, including layout, colors, and responsiveness.
- JavaScript: Manages the quiz logic, including question display, timer, scoring, and feedback.

### Key JavaScript Functions:

- `startQuiz`: Initializes the quiz and starts the timer.
- `displayQuestion`: Displays the current question and its options.
- `checkAnswer`: Checks the selected answer and provides feedback.
- `nextQuestion`: Moves to the next question and updates the progress.
- `updateTimer`: Manages the countdown timer for each question.
- `updateProgress`: Updates the progress bar based on the current question.
- `endQuiz`: Ends the quiz and displays the result card.

## Contributing

If you have any suggestions or improvements, feel free to fork the repository and submit a pull request.

## License

This project is open-source and available under the MIT License.


