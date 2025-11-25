🚀 Quantum Polymers – Frontend Internship 

A modern and responsive frontend application developed during my internship at Quantum Polymers.
This project focuses on real-time API integration, component-driven development, React Hooks, and clean UI/UX.

⭐ Tech Stack

⚛ React.js (Hooks, Components, JSX)

🟨 JavaScript (ES6+)

🎨 HTML5 / CSS3 / Tailwind / Flexbox / Grid

🔗 REST API – Axios / Fetch

🛠 Git & GitHub

📌 Key Features

🔄 Real-time API Data Fetching

📱 Fully Responsive Layout (Mobile + Tablet + Desktop)

🔍 Search & Filter Functionality

🧩 Reusable Components

🚦 API Error Handling + Loading States

📝 Form Validation (Add / Update Data)

🎛 Optimized Performance with React Hooks

🧭 SVG Icon Integration

📡 API Integration

REST APIs were used for:

✔ Fetching data
✔ Posting new records
✔ Updating existing data
✔ Deleting records
✔ Rendering dynamic UI based on API response

Example API Code
import axios from "axios";

export const fetchProducts = async () => {
  try {
    const response = await axios.get("https://api.example.com/products");
    return response.data;
  } catch (error) {
    console.error("API Error:", error);
  }
};

🧩 Project Folder Structure
src/
├── api/
│   └── api.js
├── components/
│   ├── Navbar.jsx
│   ├── ProductCard.jsx
│   ├── Loader.jsx
│   └── Icon.jsx
├── pages/
│   └── Dashboard.jsx
├── styles/
│   └── main.css
├── App.js
└── index.js

🎨 Icon Component (SVG-Based)
const Icon = ({ name, size = 24 }) => {
  return (
    <svg width={size} height={size}>
      <use href={`#${name}`} />
    </svg>
  );
};

export default Icon;

🛠 Installation & Run
Using Vite
npm install
npm run dev

Using Create React App
npm install
npm start

🧪 Future Enhancements

🌙 Dark Mode

📄 Pagination

↕️ Sorting Functionality

🔐 Authentication (Login + JWT Tokens)

🗄️ Global State (Redux / Zustand)

👨‍💻 Author

Sandeep
Frontend Developer (Intern – Quantum Polymers)

⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub to show support!
