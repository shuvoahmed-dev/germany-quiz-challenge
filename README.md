# Germany Quiz Challenge 🇩🇪 

A terminal-based quiz game built with Python that tests your knowledge about Germany. Whether you're learning German culture, preparing for an interview, or just up for a challenge, this fun little project is for you.

---

## 📑 Table of Contents

- [📜 Overview](#-overview)  
- [✨ Features](#-features)  
- [🛠️ Requirements](#-requirements)  
- [🚀 How to Run](#-how-to-run)  
- [🔍 How It Works](#-how-it-works)  
- [🧠 Code Logic](#-code-logic)  
- [🔧 Built With](#-built-with)  
- [📌 Notes](#-notes)  
- [📝 Final Note](#-final-note)

---

## 📜 Overview

**Germany Quiz Challenge** is a lightweight, text-based quiz game you can run directly in your terminal. The game asks 100 multiple-choice questions related to Germany's culture, geography, and general facts. Each question has 5 answer options (1–5), and you get feedback right after your selection. 

It’s a beginner-friendly project aimed at learning basic Python concepts like input handling, conditionals, and simple logic flow.

---

## ✨ Features

- ✅ 100 curated questions about Germany 🇩🇪  
- 🎯 Input-based answer selection (1 to 5)  
- 🎉 Immediate feedback for correct and incorrect answers  
- 📊 Score displayed at the end of the quiz  
- 🧪 No external libraries required  

---

## 🛠️ Requirements

- Python 3.x  
- A terminal or command prompt (Windows / Linux / macOS)  

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/shuvoahmed-dev/germany-quiz-challenge
   ```
2. Navigate to the directory:
   ```bash
   cd germany-quiz-challenge
   ```
3. Run the Python file:
   ```bash
   python quiz.py
   ```

---

## 🔍 How It Works

- The game contains a total of 100 questions, shown one at a time.
- Each question has 5 multiple-choice options.
- You enter your choice by typing a number between 1 and 5.
- If your input is valid and correct, you proceed to the next question and your score increases.
- If your answer is incorrect, the game ends immediately and shows your final score.

---

## 🧠 Code Logic

- All questions are stored in a list of 100 sublists.
- Each sublist contains:
  - A question string  
  - Five answer choices  
  - The correct answer (as a number between 1 and 5) at the end
- A loop goes through each question one by one.
- For each question:
  - The program displays the question and choices.
  - It waits for user input and checks if it's a number between 1 and 5.
  - If valid and correct, the score increases and the next question is shown.
  - If the input is incorrect, the game ends and shows the final score.

This list-based structure makes it simple to manage questions and scale up the quiz.


---

## 🔧 Built With

- [Python Standard Library](https://docs.python.org/3/library/) – No third-party dependencies  

---

## 📌 Notes

- The game assumes the player inputs numbers between 1–5. Input validation handles most edge cases, but adding a GUI or file-based question storage could enhance the game.
- All questions and logic are kept inside one script (`quiz_challenge.py`) for simplicity.
- Perfect as a mini-project for beginners trying to learn Python through real code.

---

## 🏁 Final Note

This project may be small in size, but it’s built with care.  
I'm currently learning Python, and this script—though simple—is a part of my hands-on journey to grasp the basics. Every line of code helps me grow a little more confident and curious about what's next.

Thanks for checking it out! 🎉  
Feel free to improve, remix, or extend it further.

**– Shuvo Ahmed**
