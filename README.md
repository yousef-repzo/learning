# React Learning Path: Building a To-Do List App

## 1. Getting Started: Git, GitHub, and Initial Setup

### Topics Covered

- Git basics
- GitHub repository setup
- Project scaffolding with Vite

### Resources

- 📘 [Git Documentation](https://git-scm.com/doc)
- 🎥 [Git and GitHub for Beginners](https://www.youtube.com/watch?v=RGOj5yH7evk)
- 📘 [Vite Docs](https://vitejs.dev/)

### Task

1. **Set up the project:**

   - Initialize a React project using Vite:
     ```bash
     npm create vite@latest todo-app --template react
     ```
   - Install dependencies:
     ```bash
     cd todo-app
     npm install
     ```

2. **Set up Git and GitHub:**
   - Initialize a Git repository:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     ```
   - Create a GitHub repository and push the code:
     ```bash
     git remote add origin https://github.com/<your-username>/todo-app.git
     git branch -M main
     git push -u origin main
     ```

---

## 2. Basic React Concepts

### Topics Covered

- JSX syntax
- Components and props
- Rendering lists

### Resources

- 📘 [React Docs: JSX](https://react.dev/learn/writing-markup-with-jsx)

### Task

1. **Feature:** Display a static task list.
2. **Steps:**
   - Create a `Task` component that accepts `title` as a prop and displays it.
   - Create a `TaskList` component that renders a static array of tasks using the `Task` component.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Add static task list"
     git push
     ```

---

## 3. React Fundamentals

### Topics Covered

- State (`useState`)
- Event handling
- Conditional rendering

### Resources

- 📘 [React Docs: State](https://react.dev/reference/react/useState)
- 🎥 [React State Tutorial](https://www.youtube.com/watch?v=O6P86uwfdR0)

### Task

1. **Feature:** Add dynamic task management.
2. **Steps:**
   - Use `useState` to manage a list of tasks.
   - Add an input field and a button to allow users to add new tasks.
   - Display a "No tasks available" message if the task list is empty.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Add dynamic task management"
     git push
     ```

---

## 4. Styling

### Topics Covered

- Using Tailwind CSS or CSS modules
- Responsive design

### Resources

- 📘 [React Docs: Adding Styles](https://react.dev/learn/typescript#typing-style-props)
- 📘[Tailwind Docs](https://tailwindcss.com/docs/installation/using-vite)
- 🎥 [Tailwind Tutorial](https://www.youtube.com/watch?v=dFgzHOX84xQ)

### Task

1. **Feature:** Style the task list.
2. **Steps:**
   - Add Tailwind CSS to the project.
   - Style tasks to visually differentiate between completed and pending tasks.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Add styling to task list"
     git push
     ```

---

## 5. Context API

### Topics Covered

- Context API for global state management

### Resources

- [useContext Docs: Context API](https://react.dev/reference/react/useContext)
- 📘 [React Docs: Context API](https://react.dev/learn/passing-data-deeply-with-context)
- 🎥 [React Context API Tutorial](https://www.youtube.com/watch?v=5LrDIWkK_Bc)

### Task

1. **Feature:** Add filtering functionality.
2. **Steps:**
   - Use Context API to manage the global state for tasks.
   - Add filters to show all tasks, only completed tasks, or only pending tasks.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Add filtering with Context API"
     git push
     ```

---

## 6. Routing

### Topics Covered

- React Router for navigation and dynamic routing

### Resources

- 📘 [React Router Docs](https://reactrouter.com/en/main)
- 🎥 [React Router Crash Course](https://www.youtube.com/watch?v=Ul3y1LXxzdU&ab_channel=WebDevSimplified)

### Task

1. **Feature:** Add a task detail page.
2. **Steps:**
   - Install React Router and set up routes for the task list and task detail pages.
   - Use a dynamic route to display details for individual tasks.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Add routing for task details"
     git push
     ```

---

## 7. Fetching Data

### Topics Covered

- Fetch API
- Handling loading and errors

### Resources

- 📘 [React Docs: Fetching Data](https://react.dev/reference/react/useEffect#fetching-data-with-effects)

### Task

1. **Feature:** Fetch tasks from an API.
2. **Steps:**
   - Fetch tasks from [JSONPlaceholder](https://jsonplaceholder.typicode.com/todos).
   - Add a loading spinner and error message.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Add task fetching from API"
     git push
     ```

---

## 8. Performance Optimization

### Topics Covered

- Memoization with `React.memo`, `useMemo` and `useCallback`
- Code splitting

### Resources

- 📘 [React Docs: useMemo](https://react.dev/reference/react/useMemo)
- 📘 [React Docs: useCallback](https://react.dev/reference/react/useCallback)
- 📘 [React Docs: memo](https://react.dev/reference/react/memo)

### Task

1. **Feature:** Optimize task rendering.
2. **Steps:**
   - Use `React.memo` to prevent unnecessary re-renders of the `Task` component.
   - Optimize filtering logic with `useMemo`.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Optimize performance"
     git push
     ```

---

## 9. Testing

### Topics Covered

- Unit testing with Jest
- Integration testing with React Testing Library

### Resources

- 📘 [React Testing Library Docs](https://testing-library.com/docs/react-testing-library/intro/)
- 🎥 [React Testing Crash Course](https://www.youtube.com/watch?v=7dTTFW7yACQ&list=PL4cUxeGkcC9gm4_-5UsNmLqMosM-dzuvQ&ab_channel=NetNinja)

### Task

1. **Feature:** Add tests for core features.
2. **Steps:**
   - Write unit tests for the task addition and deletion features.
   - Write integration tests for the filtering functionality.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Add unit and integration tests"
     git push
     ```

---

## 10. Final Deployment

### Topics Covered

- GitHub Pages or Vercel deployment

### Resources

- 📘 [GitHub Pages Docs](https://docs.github.com/en/pages)
- 📘 [Vercel Deployment Docs](https://vercel.com/docs)

### Task

1. **Feature:** Deploy the final app.
2. **Steps:**
   - Deploy the app to GitHub Pages or Vercel.
   - Share the live app link.
   - Commit changes to Git:
     ```bash
     git add .
     git commit -m "Deploy app"
     git push

     ```
