
# 📖 Story Telling App

A simple **Story Telling App** built using **HTML, CSS, and JavaScript**.  
Users can select different story genres, and the app displays a story based on their selection.

## 🚀 Features

- Select a story genre:
  - 😱 Scary
  - 😂 Funny
  - 🗺️ Adventure
- Displays a different story based on the selected genre.
- Changes the story container's border color according to the selected genre.
- Uses JavaScript event listeners to handle button clicks.
- Uses an object to store stories and their corresponding styles.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript

## 📂 Project Structure

```text
story-telling-app/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🧠 JavaScript Concepts Practiced

This project helped me practice:

- Objects
- Object properties
- Functions
- Function parameters
- `hasOwnProperty()`
- `querySelector()`
- `getElementById()`
- `textContent`
- `addEventListener()`
- `style` property
- Dynamic property access using bracket notation

## ⚙️ How It Works

The stories and their border colors are stored inside a JavaScript object.

When the user clicks a genre button:

1. The click event is detected using `addEventListener()`.
2. The corresponding genre is passed to the `displayStory()` function.
3. JavaScript finds the selected genre in the story object.
4. The story is displayed on the page.
5. The border color is updated according to the selected genre.

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/zakiya3037/Story-Telling-App.git
```

2. Open the project folder.
3. Open `index.html` in your browser.

## 🎯 Purpose of the Project

I built this project to practice **JavaScript fundamentals and DOM manipulation** by creating an interactive web application.

## 👩‍💻 Author

**Shaik Fathima Zakiya**

Aspiring Software Engineer | JavaScript Learner
