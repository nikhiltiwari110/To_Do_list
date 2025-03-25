# To-Do List Application

This is a simple To-Do List web application that allows users to add, mark as completed, and delete tasks. The application uses HTML, CSS, and JavaScript and stores tasks in the browser's local storage to persist data across sessions.

## Features

- Add new tasks to the list.
- Mark tasks as completed by clicking on them.
- Delete tasks by clicking the close (×) button.
- Tasks are saved in the browser's local storage, so they remain even after refreshing the page.


## How to Use

1. Open the `index.html` file in a web browser.
2. Enter a task in the input box and click the "Add" button to add it to the list.
3. Click on a task to mark it as completed (it will be crossed out).
4. Click the close (×) button next to a task to delete it.
5. Tasks are automatically saved to local storage and will reappear when you reopen the application.

## Local Storage

The application uses the browser's local storage to save the tasks. The `savedata` function saves the current state of the task list, and the `showTask` function retrieves and displays the saved tasks when the application is loaded.

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling the application.
- **JavaScript**: Logic for adding, deleting, and marking tasks as completed.

## License

This project is open-source and free to use.
