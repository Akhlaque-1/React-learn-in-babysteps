# React Learning Diary 📝

This repository documents my **step-by-step learning journey in React**.  
I am practicing React daily, from beginner “Hello World” to components, props, state, and more.

---

## 📅 Day 1 — Baby Steps / Beginner Start ✅

**What I Learned Today:**

- React is a **JavaScript library** for building user interfaces.  
- Helps create **fast, dynamic, component-based UI**.  
- Using **Vite** to create and run React apps easily.

**💻 Commands Used:**

```bash
# Check Node.js & npm version
node -v
npm -v

# Create a new React project using Vite
npm create vite@latest my-react-app --template react

# Go inside project folder
cd my-react-app

# Install dependencies
npm install

# Run the React project
npm run dev
📂 Project Folder Structure:

css
Copy code
my-react-app/
├── index.html
├── package.json
├── README.md
└── src/
    ├── App.jsx
    ├── main.jsx
    └── assets/
🖥️ Hello World Example:

jsx
Copy code
function App() {
  return <>Hello World!</>;
}
export default App;
Run the server:

bash
Copy code
npm run dev
Open http://localhost:5173/ to see "Hello World!"

🧠 Key Takeaways:

App.jsx → main component

main.jsx → connects React to the browser

npm run dev → starts local development server

📅 Day 2 — Components & JSX ✅
What I Learned Today:

React components make UI modular and reusable.

JSX allows HTML-like code in React.

💻 Commands Used:

bash
Copy code
# Start the project
npm run dev

# Optional: Install React Router for routing
npm install react-router-dom
📂 Updated Project Structure:

css
Copy code
my-react-app/
├── src/
│   ├── components/
│   │   └── Header.jsx
🖥️ Creating Components:

src/components/Header.jsx

jsx
Copy code
function Header() {
  return (
    <header>
      <h1>Welcome to My React App!</h1>
    </header>
  );
}

export default Header;
src/App.jsx

jsx
Copy code
import Header from "./components/Header";

function App() {
  return (
    <>
      <Header />
      <p>This is my first React component in action!</p>
    </>
  );
}

export default App;
Run the server:

bash
Copy code
npm run dev
Open http://localhost:5173/ to see your component in action.

🧠 Key Takeaways:

Components = reusable UI pieces

JSX = HTML-like syntax in React

Import/Export = share components across files

📌 Tips:

Keep src/components/ organized

One component = one purpose

Use meaningful names for components

