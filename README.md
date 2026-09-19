# FocusList — Task Manager

A premium, frontend-only To-Do application built with vanilla HTML, CSS, and JavaScript.

## Live Demo
[Live Deployment Link](https://jovial-eclair-1f0063.netlify.app/)

## Tech Stack
- Vanilla JavaScript (ES6+)
- CSS Custom Properties (Variables)
- LocalStorage for persistence
- No dependencies, no build step, no backend.

## Features
- Create, complete, edit, and delete tasks
- Priority levels (High, Medium, Low)
- Live search and combinable filters
- Real-time statistics and progress ring
- Dark mode with OS detection
- Keyboard shortcuts (/ to search, n for new, Esc to blur)
- Export/Import JSON backups

## How to Run Locally
Because this is a static, single-page application, no build step is required.

1. Clone the repository:
   `git clone https://github.com/soodxkeshav/focuslist.git`
2. Navigate to the folder:
   `cd focuslist`
3. Open `index.html` directly in your browser:
   - **Mac:** `open index.html`
   - **Windows:** `start index.html`
   - Or simply double-click the `index.html` file.

## How to Test
1. Add a task in the input field and click "Add Task".
2. Toggle the checkbox to mark it complete.
3. Click "Edit" to change the title inline. Press Enter to save, Escape to cancel.
4. Click "Delete" to remove a task (a confirmation dialog will appear).
5. Use the search bar and filter buttons to narrow down the list.
6. Toggle dark mode using the moon/sun icon in the top right.
7. Refresh the page to verify tasks persist via LocalStorage.
