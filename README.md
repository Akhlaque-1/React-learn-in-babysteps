📘 React — Day 1 (Baby Steps / Beginner Start)
✅ What I Learned Today

React is a JavaScript library used to build user interfaces.

React helps make fast, dynamic, and component-based UI.

We use Vite to create and run React apps easily.

💻 Commands I Used Today
1️⃣ Check Node.js & npm version

node -v

npm -v

2️⃣ Create a new React project using Vite

npm create vite@latest my-react-app --template react

3️⃣ Go inside the project folder

cd my-react-app

4️⃣ Install all node modules

npm install

5️⃣ Run the React project

npm run dev

📂 Project Folder Structure 

my-react-app/

├── index.html

├── package.json

├── README.md

└── src/

  ├── App.jsx

  ├── main.jsx

  └── assets/

🖥️ Hello World Example

Open src/App.jsx and replace the code with:

function App() {
  return (
    <>
      <h1>Hello World!</h1>
    </>
  );
}

export default App;


Run the dev server:

npm run dev


Open http://localhost:5173/

 in your browser. You will see Hello World!

🧠 Simple Understanding from Day 1

App.jsx → main component of your React app

main.jsx → connects React to the browser

npm run dev → starts local development server

Default URL → http://localhost:5173/

🎯 D