# Quiz Game 🎯

A simple and responsive quiz game built with HTML, CSS, and Vanilla JavaScript.

## 🚀 Live Demo

[View the Quiz Game](https://vanelli-afk.github.io/quiz-game/)

## 📖 About

Quiz Game is a simple front-end project created to practice fundamental web development concepts using **HTML, CSS, and JavaScript**.

The application presents multiple-choice questions, provides immediate feedback, tracks the user's score, displays quiz progress, and shows a final result when the quiz is completed.

## ✨ Features

* Start and restart quiz
* Multiple-choice questions
* Dynamic answer buttons
* Correct and incorrect answer feedback
* Automatic score tracking
* Question counter
* Progress bar
* Final score screen
* Performance-based result message
* Responsive design for mobile devices

## 🛠️ Technologies

* **HTML5** — page structure
* **CSS3** — styling and responsive design
* **JavaScript (ES6+)** — quiz logic and DOM manipulation

## 📂 Project Structure

```text
Quiz-Game/
├── index.html
├── style.css
├── script.js
└── README.md
```

### Files

* `index.html` — application structure and quiz screens
* `style.css` — layout, colors, buttons, feedback states, and responsiveness
* `script.js` — questions, quiz logic, score calculation, events, and results
* `README.md` — project documentation

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/Vanelli-afk/quiz-game.git
```

### Open the project

```bash
cd quiz-game
```

Then open `index.html` directly in your browser.

You can also use **VS Code with Live Server** for local development.

---

## 🎮 How It Works

The quiz questions are stored in a JavaScript array, with each question containing its possible answers and the correct option.

When the user starts the quiz, JavaScript dynamically generates the answer buttons and updates the interface according to the current question.

After an answer is selected, the application:

1. Checks whether the answer is correct.
2. Updates the score.
3. Displays visual feedback.
4. Moves to the next question.
5. Shows the final results when the quiz is completed.

## 📝 Customizing the Quiz
New questions can be added directly to the `quizQuestions` array in `script.js`.

```javascript
{
  question: "Your question here?",
  answers: [
    { text: "Option A", correct: false },
    { text: "Option B", correct: true },
    { text: "Option C", correct: false },
    { text: "Option D", correct: false }
  ]
}
```

The total number of questions and maximum score are automatically updated based on the number of questions in the array.

## 👤 Author
### More about me
* GitHub: [@Vanelli-Afk](https://github.com/Vanelli-afk)
* LinkedIn: [Miguel Vanelli](https://linkedin.com/in/miguel-vanelli)
