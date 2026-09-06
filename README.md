# Daymark Todo App

Daymark is a clean, responsive todo app for organizing daily tasks and staying focused. It provides a simple task workflow with a calm, lightweight interface that works on desktop and mobile browsers.

## Features

- Add new tasks from the main input
- Mark tasks as completed or incomplete
- Delete individual tasks
- Filter tasks by:
  - Everything
  - In progress
  - Done
- View total, completed, and remaining task counts
- Track completion progress with a progress bar
- Clear all completed tasks at once
- Toggle the interface theme
- Responsive layout for smaller screens
- Accessible labels for interactive controls
- Automatically displays the current date

## Preview

Open the app in a browser to view the Daymark todo interface.

## Getting Started

### Prerequisites

No build tools, package manager, or backend are required. A modern web browser is enough.

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/<your-repository>.git
   ```

2. Open the project folder.

3. Open `index.html` directly in your browser.

You can also use the **Live Server** extension in VS Code for a local development server.

## Usage

1. Enter a task in the **What needs to be done?** field.
2. Press **Enter** or select **Add task**.
3. Select the circle beside a task to mark it complete.
4. Use the filters to switch between all, active, and completed tasks.
5. Select the delete control to remove a task.
6. Use **Clear completed** to remove every completed task.

Tasks are stored in memory for the current page session. Refreshing the browser clears the current list.

## Project Structure

```text
TodoApp/
├── index.html   # App markup and client-side todo behavior
├── styles.css   # Layout, responsive styles, colors, and animations
├── app.js       # Original prompt-based JavaScript exercise
└── README.md    # Project documentation
```

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts: Manrope and DM Mono

## Notes

The current browser interface uses the JavaScript included in `index.html`. The separate `app.js` file contains the original console and prompt-based todo exercise and is kept as part of the course project.

## License

This project is available for personal and educational use.
