## Quiz App v1

A minimalist Python quiz application that runs in the terminal using object-oriented design.

### Overview

This is a console-based quiz app built in Python. It organizes functionality across four files:
- `question_model.py`: Defines the `Question` class to represent each quiz question.
- `questions.py`: Stores or loads all question data (text, choices, correct answer).
- `quiz_brain.py`: Handles the quiz logic—fetching questions, checking answers, tracking score.
- `main.py`: Orchestrates the app flow—initializes questions and quiz logic, runs the quiz loop.

### How It Works

1. **Define Questions** — `questions.py` contains your list of questions.
2. **Model Structure** — `question_model.py` defines how each question is structured.
3. **Quiz Logic** — `quiz_brain.py` checks answers, maintains the score and moves through questions.
4. **Run the Quiz** — `main.py` ties it all together: it creates question objects, starts the quiz, and shows the final score.

### Getting Started

#### Requirements
- **Python 3.x** (no external libraries required)

#### Usage
```bash
python main.py
```

Follow the on-screen prompts to answer each question. At the end, you'll see your total score.

### Project Structure

```
├── main.py            # Entry point for the quiz
├── question_model.py  # Defines the Question class
├── questions.py       # Contains your list of questions
└── quiz_brain.py      # Quiz logic and score tracking
```
