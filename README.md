ToDo List App

This is a simple ToDo list application written in JavaScript. It allows you to add, cross out, and delete items from a list.

Features

Adding a new item to the list of items.
Crossing out an item from the list of items.
Adding a delete button to remove an item from the list.
Reordering the items.
Usage

To use the application, follow these steps:

Clone or download the project repository.
Open the index.html file in your web browser.
Enter a task in the input field and click the "Add" button or press Enter.
The task will be added to the list.
Double-click on a task to mark it as completed (or undo the completion).
Click on the "X" button next to a task to delete it from the list.
You can also reorder the tasks by dragging and dropping them.
Code Explanation

The code consists of the following functions:

newItem(): This function handles the process of adding a new item to the list. It retrieves the input value, creates a new list item (<li>), and appends it to the list. It also handles validation to ensure that the input is not empty.
crossOut(): This function is responsible for crossing out an item when it is double-clicked. It toggles the "strike" class on the list item.
deleteListItem(): This function adds the "delete" class to the list item, which sets its display to none. It is triggered when the delete button ("X") is clicked.
The code also includes functionality for reordering the items using the jQuery UI sortable() method.

Dependencies

This application relies on the following dependencies:

jQuery: It is used for DOM manipulation.
jQuery UI: It is used for the sortable functionality.
Please make sure to include these dependencies in your project for the application to work correctly.

