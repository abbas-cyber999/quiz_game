# 📝 Simple Python Quiz Game

A beginner-friendly **Python quiz game** where you answer multiple-choice questions about world capitals.  
This project is perfect for practicing **Python basics** such as input/output, variables, and conditionals.  

---

## 📂 Project Structure

```
quiz.py      # The main Python file that contains the quiz code
README.md    # Documentation file (this file)
```

---

## 🚀 Getting Started

### 1. Prerequisites
- Install **Python 3.10+**
- Works on Windows, macOS, or Linux

Check if Python is installed:
```bash
python --version
```
or
```bash
python3 --version
```

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/quiz-game.git
cd quiz-game
```

### 3. Run the Game
```bash
python quiz.py
```

---

## 🎮 How to Play

- You will be asked **3 questions** about world capitals.  
- For each question, you’ll see multiple-choice options.  
- Type your answer (e.g., `berlin`, `damascus`, `newdelhi`).  
- The game tells you if your answer is correct ✅ or wrong ❌.  

---

## 💻 Example Gameplay

```
What is the capital of Germany?
select from : 
#1 - Amesterdam
#2 - Berlin
#3 - Damascus
Choose the right answer !berlin
coooool it`s a correct answer!

What is the capitaal of Syria
select from : 
#1 - Amesterdam
#2 - Berlin
#3 - Damascus
Choose the right answer !damascus
coooool it`s a correct answer!

What is the capital of India
select from : 
#1 - Amesterdam
#2 - Berlin
#3 - Newdelhi
Choose the right answer !newdelhi
coooool it`s a correct answer!
```

---

## 🛠️ Code Explanation

### Input and Output
```python
quistion1 = "What is the capital of Germany?"
print(quistion1)
```
➡️ Displays a question to the user.

```python
userinput = input("Choose the right answer !").lower()
```
➡️ Waits for the user to type an answer and converts it to lowercase.

### Conditional Logic
```python
if userinput == "berlin":
    print("coooool it`s a correct answer!\n")
else:
    print("BAD LUCK .. it`s a wrong answer\n")
```
➡️ Checks if the answer is correct and prints feedback.

---

## ✨ Features

- ✅ Multiple-choice questions  
- ✅ User input with feedback  
- ✅ Simple and interactive  
- ✅ Beginner-friendly code  

---

## 🚧 Future Improvements

- [ ] Add more questions  
- [ ] Add scoring system  
- [ ] Accept answers by number (e.g., `2` for Berlin)  
- [ ] Randomize questions and answers  
- [ ] Use `match case` (Python 3.10+) for cleaner logic  

---

## 📚 Learning Purpose

This project is designed for **beginners in Python**.  
You’ll practice:
- Variables  
- Strings and print statements  
- `input()` function  
- `if/else` conditions  

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it.  

---
👨‍💻 Created with ❤️ for learning Python basics.
