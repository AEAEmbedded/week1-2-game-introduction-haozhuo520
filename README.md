# Exercise 1.2 – First lines of the game

## 🎯 Goal
You will write the **introduction part** of a guessing game in C.  
This is the start of a multi-week project where you gradually expand the game.

The game should:
- Display a **welcome message**.
- Explain the goal (guess the secret number).
- Tell the player how many chances they will get (for now, just hardcode a number like 5).
- Ask the player’s name (you don’t need to store it yet).
- Print a personalized message using the name.
- End with the first input request: *"There is a secret number between 0 and 100, what is your first try:"*

---

## 🛠 Instructions
1. Open **Qt Creator**.
2. Create a new project `gameweek1`.
3. Edit your `main.c` file so it prints the introduction text using `printf()`.
4. Use `\n` in your `printf` statements to make sure each line is on its own line.
5. Add a placeholder `<name>` for now; in later weeks, you will actually read the name with `scanf()`.

---

## ✅ Example Output

```

Welcome to the guessing game!
The object of the game is to guess the secret number.
You get 5 chances for that.
To address you personally, I would like to know your name.
What is your name: <will be added>

Great <name>, let's get started.

There is a secret number between 0 and 100, what is your first try:

```

---

## 📚 What You’ll Learn
- How to use multiple `printf()` statements.
- How to format strings with `\n` to create newlines.
- How to start structuring a program for **user interaction**.
- Why it is important to **start simple** and build a program step by step.

---

## 🔎 Tips
- Don’t worry about actually asking for the name yet – just use a placeholder.  
- Keep your code readable and well-formatted (`int main(void)` is the correct form).  
- Run your program after each change to check the output matches the example.  

---