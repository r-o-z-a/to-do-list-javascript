# To-Do List Web Application

## Overview

This simple web application allows users to create, edit, and delete tasks in a to-do list. Users can mark tasks as completed, edit task names, and delete tasks. The application uses local storage to persist tasks even when the page is refreshed or reopened.

## Features

- **Add Task:** Enter a task in the input field and press 'Enter' to add it to the to-do list.
- **Mark as Completed:** Check the checkbox next to a task to mark it as completed. Completed tasks are visually distinguished from active tasks.
- **Edit Task:** Click the edit button (pencil icon) next to a task to edit its name. Press 'Enter' to save the changes.
- **Delete Task:** Click the delete button (trash icon) to remove a task from the to-do list.

## Usage

1. Open the HTML file in a web browser.
2. Enter a task in the input field and press 'Enter' to add it to the to-do list.
3. Use the checkbox to mark tasks as completed.
4. Click the edit button to edit a task's name.
5. Click the delete button to remove a task from the list.

## Local Storage

Tasks are saved to local storage, allowing the to-do list to persist even if the page is refreshed or reopened. Edits and deletions are also stored, ensuring a seamless user experience.

## External Dependencies

- [Material Icons](https://fonts.googleapis.com/icon?family=Material+Icons): Used for checkbox icons.
- [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css): Used for edit and delete icons.

## Additional Files

- **style.css:** Contains styles for the to-do list.

## CSS Overview

The styles in `style.css` are designed to give the to-do list a visually appealing and user-friendly appearance. Here is an overview of the key styles:

- **Font:** The entire application uses the 'Riverdell' font from [Google Fonts](https://fonts.cdnfonts.com/css/riverdell) for a cursive and bold look.
- **Background:** The background is set to a black color.
- **Container:** The to-do list container has a red box shadow, a rose image background, and is positioned in the center of the screen.
- **Input and Buttons:** Styling for input fields and buttons is customized with a transparent background, removing borders and outlines. Buttons have a transparent background and show reduced opacity on hover.
- **List Items:** Tasks have a red background color, and completed tasks are visually distinguished with a line-through text decoration.
- **Header (h1):** The header has a black background with a red border at the bottom.

Feel free to explore and modify the CSS to suit your preferences!
