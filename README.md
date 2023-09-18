Import necessary modules from the Tkinter library.

Create a Todo class that defines the main application.

In the __init__ method:

Set up the main application window with a title and geometry.
Create labels for the application's title, "Add task," and "Tasks."
Create a Listbox widget (main_text) to display the list of tasks.
Create a Text widget (text) for entering new tasks.
Define two functions (add and delete) for adding and deleting tasks:

add(): Reads the task from the Text widget, inserts it into the Listbox, and appends it to a file named "data.txt."
delete(): Deletes the selected task from the Listbox and also removes it from the "data.txt" file.
Read tasks from the "data.txt" file and populate the Listbox with them when the application starts.

Create two buttons, "Add" and "Delete," which execute the add and delete functions when clicked.

In the main() function:

Create the main Tkinter window (root).
Initialize an instance of the Todo class, passing the root window.
Start the Tkinter main event loop.
