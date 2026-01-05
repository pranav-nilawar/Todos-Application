
# Todos Application

A sleek, functional To-Do List application built with JavaScript. This project focuses on efficient DOM manipulation, event delegation, and providing a clean user experience.
## Features

- Add Tasks: Quickly add new items to your list.
- Input Validation: Prevents empty tasks or whitespace-only entries.
- Toggle Completion: Click on a task to mark it as finished with a visual strike-through.
- Delete Tasks: Remove specific items from the list instantly.
- Local Storage: Save tasks so they persist after refreshing the page.


## Technical Challenges

1. #### DOM Manipulation
The app dynamically creates, appends, and removes elements from the Document Object Model (DOM) without requiring a page refresh.

2. #### Event Handling & Delegation
Instead of attaching listeners to every single list item, the project utilizes Event Delegation. By attaching a listener to the parent <ul>, we efficiently manage clicks on "Delete" buttons and "Complete" checkboxes, even for items added after the page loads.

3. #### Input Validation
To ensure data integrity, the app validates user input by checking if the input string is empty.


## Project Structure

├── index.html           
├── index.css            
└── index.js           
## How To Run

1. Clone this repository:

git clone https://github.com/yourusername/todo-list-js.git  

2. Navigate to the project folder.

3. Open index.html in your favorite web browser.