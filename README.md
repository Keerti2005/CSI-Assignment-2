# React To-Do List

A simple To-Do List application built with React class components.  
Features task addition, removal, completion marking, editing, filtering, and persistence using `localStorage`.

---

## Features

- Add new tasks with validation (non-empty input required)
- Mark tasks as done/undone
- Edit existing tasks
- Filter tasks by: All, Done, To-Do
- Delete individual tasks, all tasks, or only completed tasks
- Tasks persist across browser reloads using `localStorage`

---

## Installation

### Clone the repository:
```bash
git clone https://github.com/Keerti2005/CSI-Assignment-2
cd CSI-Assignment-2
```

### Install dependencies:
```bash
npm install
```

### Start the development server:
```bash
npm start
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Testing Guidance

To verify the core functionalities of the To-Do List app, perform the following manual tests in your browser after running `npm start`:

### Add Task
- Enter a non-empty string in the input box and submit.
- Confirm the new task appears in the list with the correct title.
- Try submitting an empty input and confirm no task is added.

### Mark Task Complete/Incomplete
- Click the checkbox icon on a task to toggle its completion status.
- Confirm the task's style changes to indicate completion (e.g., strikethrough).
- Click again to toggle back to incomplete.

### Edit Task
- Click the pencil icon on a task.
- Confirm the task title appears in the input box for editing.
- Modify the text and submit.
- Confirm the task updates with the new title.

### Delete Task
- Click the trash icon next to a task.
- Confirm the task is removed from the list.

### Filter Tasks
- Use the "All", "Done", and "Todo" buttons to filter tasks.
- Confirm the list updates to show the correct subset of tasks.

### Bulk Delete
- Click "Delete done tasks" to remove all completed tasks.
- Click "Delete all tasks" to clear the entire list.
- Confirm tasks are removed appropriately.

### Persistence Check
- Refresh the page and confirm that tasks and their completion status persist.

---

## Dependencies

- React
- uuid (for unique IDs)
- FontAwesome (for icons) — ensure you have included the CSS in `public/index.html` or install via npm

---

## Notes

- The project uses React class components for state management.
- Task completion and editing are fully functional.
- Input validation prevents empty tasks from being added.
- The app is styled using Bootstrap classes; ensure Bootstrap CSS is included.
