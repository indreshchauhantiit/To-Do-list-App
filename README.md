# To-Do-list-App
To do list with the functionality of Add ,Edit 
,Delete and Search task .
Key Functionalities
1. Add Task
○ A text input field and an "Add" button are provided to allow users to create tasks.
○ When the user types a task into the input field and clicks "Add," the task is added 
to the task list dynamically using JavaScript and displayed in a styled container.
2. Edit Task
○ Each task includes an "Edit" option that allows users to update task details.
○ Upon clicking "Edit," the task text transforms into an editable input field. The 
task's original text is pre-filled in the input box for modification.
○ A "Save" button is displayed, allowing users to save their changes.
3. Save Task
○ Once changes are made in the editable input field, clicking the "Save" button 
updates the task with the modified text.
○ The task returns to its non-editable state, and the changes are dynamically 
reflected in the task list without reloading the page.
4. Search Task
○ A search input field is provided at the top of the task list to filter and display tasks 
based on user-entered keywords.
○ As the user types in the search bar, only tasks containing the search term are 
displayed, improving accessibility and ease of navigation for users.
Code Implementation
1. HTML Structure
○ The To-do list system includes an input section for adding tasks, a list container 
for displaying tasks, and a search section to filter tasks.
2. CSS Design
○ The interface is styled using a minimalistic and modern approach, with a visually 
appealing task container, button styles, and dynamic states for elements like the 
"Save" button and input fields.
○ The layout ensures responsiveness and usability by utilizing a flexbox design.
3. JavaScript Functionality
○ JavaScript is used to dynamically handle task addition, editing, saving, and 
searching:
■ Adding Tasks: Tasks are appended to the DOM using JavaScript.
■ Editing Tasks: When the user clicks "Edit," the task's content is replaced 
with an editable input field and a "Save" button.
■ Saving Changes: On clicking "Save," the edited task replaces the input 
field, and the button is hidden.
■ Search: An event listener on the search input dynamically filters tasks as 
the user types.
