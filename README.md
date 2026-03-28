# 📝 To-Do List App

A simple, interactive **To-Do List** web application built with **HTML**, **CSS**, and **JavaScript**. Users can add, complete, and delete tasks, with all tasks saved in the browser’s **localStorage** so they persist across sessions.

---

## Features

- Add new tasks to the list.
- Mark tasks as **completed** by clicking on them.
- Delete tasks individually.
- Tasks are saved automatically in **localStorage**.
- Responsive layout for different screen sizes.

---

## Technologies Used

- **HTML** – Structure of the app.
- **CSS** – Styling and layout.
- **JavaScript** – Functionality and DOM manipulation.
- **LocalStorage** – To save tasks across browser sessions.

---

## Usage

1. Clone the repository or download the files.
2. Open `index.html` in your browser.
3. Enter a task in the input box and click **Add Task**.
4. Click on a task to mark it as completed.
5. Click the **Delete** button to remove a task.


---

## How It Works

- When the page loads, tasks are fetched from `localStorage` and rendered on the page.
- **Adding a task**:
  - Input is trimmed and checked for empty value.
  - Task is saved in `localStorage`.
  - Task is displayed in the list.
- **Completing a task**:
  - Clicking on the task text toggles the `completed` class.
  - Changes are saved in `localStorage`.
- **Deleting a task**:
  - Clicking the **Delete** button removes it from the DOM and updates `localStorage`.
