# Auto Text Effect Animation

A clean, lightweight web animation built with vanilla HTML, CSS, and JavaScript that dynamically types out a rotating list of titles/roles character by character in an infinite loop[cite: 7].

## Preview

<img width="1917" height="851" alt="Screenshot 2026-11-17 124651" src="https://github.com/user-attachments/assets/053fab5a-596b-48f5-825d-013de91b2130" />

## Features

* **Character-by-Character Typing:** Uses recursive `setTimeout` intervals (400ms) to smoothly reveal each letter of the active title.
* **Smart Grammar Handling:** Automatically switches between `"a"` and `"an"` based on the starting letter of the word (e.g., *"I am a Student"* vs. *"I am an IT graduate"*)[cite: 7].
* **Infinite Loop:** Cycles seamlessly through the entire array of titles (`Student`, `Web Developer`, `Trekker`, `Player`, `IT graduate`).
* **Bold Stylized Typography:** Centered full-viewport layout styled with Flexbox, a salmon background, and Google Fonts' **Permanent Marker** typeface[cite: 7].

---

## Project Structure

```text
├── index.html      # Main HTML container structure
├── style.css       # Flexbox centering, background theme, and Google Font import
├── index.js        # Recursive typing logic, career array, and article matching
└── preview.png     # Application screenshot for the README
