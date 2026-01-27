# 📘 React Learning Journey

A beginner-friendly **React practice repository** documenting my day-by-day learning using **React + Vite**. This repo is created for **self-learning** and to help **friends** learn React step by step with clear examples.

---

## 🧭 React Learning Journey — Start → Where?

### 📍 Start Point

This journey starts from **absolute React basics**:

* What is React?
* Project setup with **Vite**
* JSX, Components, and Props

### 🏁 End Point (Goal of This Repo)

This repository will be considered **complete** when I can:

* Build small to medium **React projects** independently
* Use **Props, State (useState), Effects (useEffect)** confidently
* Handle **events, forms, conditional rendering, lists**
* Add **routing** and **API integration**
* Style apps using **Tailwind CSS**
* **Deploy** a React app (Vercel/Netlify)

After reaching this point, the focus moves from *learning notes* to *real projects*.

---

## 🚀 Tech Stack

* React
* Vite
* JavaScript (ES6+)
* Node.js & npm
* Tailwind CSS

---

## ✅ Day 1 — Baby Steps / Beginner Start

### 📌 What I Learned

* React is a JavaScript library for building user interfaces
* React uses a component-based architecture
* Vite helps create and run React apps quickly

### 💻 Commands Used

```bash
node -v
npm -v
npm create vite@latest my-react-app --template react
cd my-react-app
npm install
npm run dev
```

### 📂 Project Structure

```
my-react-app/
├── index.html
├── package.json
├── README.md
└── src/
    ├── App.jsx
    ├── main.jsx
    └── assets/
```

### 🧠 Understanding

* App.jsx → Main UI component
* main.jsx → Connects React to the browser
* npm run dev → Starts local server
* Default URL → [http://localhost:5173/](http://localhost:5173/)

---

## ✅ Day 2 — JSX & Components

### 📌 What I Learned

* JSX allows writing HTML-like code inside JavaScript
* JSX must return a single parent element
* Components are reusable UI blocks
* Component names must start with a capital letter

### 🧪 Example

```jsx
const name = "React Learner";

function App() {
  return (
    <div>
      <h1>Hello, {name}</h1>
      <p>Welcome to Day 2</p>
    </div>
  );
}

export default App;
```

### 🧠 Understanding

* `{}` is used for JavaScript inside JSX
* Components help reuse UI logic

---

## ✅ Day 3 — Props (Passing Data)

### 📌 What I Learned

* Props are used to pass data from parent to child components
* Props make components dynamic and reusable
* Props are read-only

### 🧪 Props Example

**Child Component (`ProfileCard.jsx`)**

```jsx
function ProfileCard({ name, role }) {
  return (
    <div>
      <h2>{name}</h2>
      <p>{role}</p>
    </div>
  );
}

export default ProfileCard;
```

**Parent Component (`App.jsx`)**

```jsx
import ProfileCard from "./ProfileCard";

function App() {
  return (
    <>
      <ProfileCard name="Akhlaque" role="React Learner" />
      <ProfileCard name="Friend" role="Beginner" />
    </>
  );
}

export default App;
```

### 🧠 Understanding

* Parent sends data → Child receives data
* Helps avoid code duplication

---

## 🎨 Tailwind CSS Setup (React + Vite)

### Install Tailwind

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### Configure `tailwind.config.js`

```js
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,jsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### Add Tailwind to `src/index.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Test Tailwind

```jsx
<h1 className="text-3xl font-bold text-blue-600">
  Tailwind is working
</h1>
```

---

## 🧩 Mini Project — Personal Profile Card App

### 🎯 Project Goal

Build a small React app that displays **multiple profile cards** using props and Tailwind CSS.

### 📂 Suggested Structure

```
src/
 ├── components/
 │   └── ProfileCard.jsx
 ├── App.jsx
 └── main.jsx
```

### 🧠 Concepts Covered

* Components
* Props
* JSX
* Tailwind Styling
* Reusability

---

## 📈 Learning Progress

* ✅ Day 1: React Basics & Setup
* ✅ Day 2: JSX & Components
* ✅ Day 3: Props
* ⏳ Day 4: useState Hook (Next)

---

## 🤝 Contribution

This repository is open for learning and practice.
Feel free to clone, fork, and learn together.

---

## ⭐ Support

If this repository helps you:

* ⭐ Star the repo
* 🤝 Share with friends

Happy Coding 🚀
