# practice-quizApp--Kyra---SJ-
Practice creating an app that  interactive quiz application that uses event handlers to capture user input, dynamically update the DOM, and provide feedback to the user.
1. HTML Setup:
Create a basic HTML structure with the following elements:
●
The question text.
●
Four buttons for answer choices.
●
An element to display feedback after an answer is selected.
●
A “Next Question” button to move onto the next question.
2. JavaScript Functionality:
●
Display Question:
○
Use an array of question objects, each containing:
■ A question string.
■ An array of four answer choices.
■ The index of the correct answer.
●
Handle Answer Selection:
○
Add click event listeners to the answer buttons.
○
When a button is clicked, check if the selected answer is correct and
update the feedback element accordingly.
○
Disable all answer buttons after a selection to prevent further clicks.
●
Next Question:
○
Attach an event listener to the "Next Question" button.
○
When clicked, load the next question and re-enable the answer
buttons.
