# To-Do List (React)

A simple and modern To-Do List web application built with React. This project provides a clean UI for adding, completing, and deleting tasks, and is a great starter app to practice state management and React hooks.

## 🚀 Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Responsive UI
- Persistent logic ready to extend (e.g., localStorage integration)

## 🧩 Project Structure

- `src/index.js` - Entry point
- `src/App.jsx` - Main application component
- `src/components/InputArea.jsx` - Input field for adding tasks
- `src/components/ToDoItem.jsx` - Single task item display
- `src/styles.css` - Global styling

## 🛠️ Technologies

- React
- JavaScript (ES6+)
- CSS

## ▶️ Run Locally

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start development server:
   ```bash
   npm start
   ```
3. Open in browser: `http://localhost:3000`

## 📦 Build (Production)

```bash
npm run build
```

This outputs static assets under `build/`.

## 🧪 Testing

No tests are configured in this boilerplate, but you can add Jest and React Testing Library as needed.

## ✨ Notes

- If you want to persist to-dos across browser refresh, integrate `localStorage` in `App.jsx`.
- You can add filtering (All / Active / Completed) in the list component.

## 📜 License

MIT License
