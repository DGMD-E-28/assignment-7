# Wordle Redux Part 2

## Assignment Overview
This project is part of **DGMD E-28: Developing Single Page Web Applications**. It recreates a simplified version of the Wordle game using **React with JSX**.

---

## Requirements

Technologies used:

- **HTML** for structure  
- **CSS** for layout and visual feedback  
- **React with JSX (via Babel)** to render the board and components dynamically

---

## 📌 Tasks

### 🔹 Wordle Game Structure

- Create a **6x5 board** using React
- Hardcode 3 guesses: `"might"`, `"flood"`, `"stray"`
- Use `"moody"` as the answer
- Compare each guess to the answer and:
  - Display a green tile for correct letter & position
  - Display a yellow tile for correct letter, wrong position
  - Display a grey tile for letters not in the word

### 🔹 Visual Indicators

- Correct = green background with white text  
- Present = goldenrod background  
- Absent = grey background  
- Remaining unused board rows remain blank

### 🔹 On-screen Keyboard

- Display three rows:
  - QWERTYUIOP
  - ASDFGHJKL
  - ZXCVBNM
- Keyboard is static (non-interactive)

---

## 🚀 Deliverables

- `index.html`

---

## 💡 Reflection Questions

1. **Which seems better for creating the elements of the app: JS alone or JS with React?**  
   Using React with JSX is better for organizing and reusing code through components. It makes building structured UIs more maintainable than raw JS.

---

## Project Details

- **Author:** Elizabeth Koch  
- **Date:** Fri Apr 11, 2025  
- **Live URL:** *https://dgmd-e-28.github.io/assignment-7/*  

---

Happy Coding! ⌨️🟩🟨⬜