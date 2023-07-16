## Task Management App
This is a Task Management App that allows you to manage and edit tasks. The app provides functionality to edit and save task details, as well as search for specific tasks based on their title.

# Features
The Task Management App provides the following features:

Edit Task: This feature allows you to edit the details of a task. When you click the "Edit" button for a task, the task details become editable, including the title, description, and type. After making the necessary changes, you can save the edits.

Save Edit: Once you have made changes to the task details, you can save the edits using the "Save Changes" button. This updates the task's information and stores it in the app's state.

Search Task: The app allows you to search for tasks based on their title. When you enter a search term in the search bar, the app filters the task list and displays only the tasks that match the search criteria.

Code Explanation
The provided code contains the JavaScript functions that implement the app's functionality. Here's a brief explanation of each function:

editTask: This function is triggered when the "Edit" button is clicked for a task. It retrieves the task's details and enables editing by setting the contenteditable attribute of the relevant elements to true. The button's functionality is also modified to call the saveEdit function when clicked.

saveEdit: This function is called when the "Save Changes" button is clicked after editing a task. It retrieves the modified task details, updates the corresponding task in the app's state, and saves the updated state to local storage. The contenteditable attribute of the task elements is set back to false, and the button's functionality is reset to open the task modal.

searchTask: This function is triggered when a search term is entered in the search bar. It filters the task list based on the title, case-insensitively, and updates the display to show only the matching tasks.

Usage
To use the Task Management App, you can incorporate the provided code into your project and ensure the necessary HTML structure and CSS styles are in place. Additionally, you may need to implement the following components:

Task List: Display the list of tasks in your app's interface. Each task should include the task title, description, type, and an "Edit" button.

Task Modal: Implement a modal or popup window to display the details of a task when selected. Include an "Edit" button within the modal.

Search Bar: Add a search bar where users can enter their search queries to filter the task list based on the task title.

Make sure to link the appropriate event handlers to the corresponding elements in your HTML markup. You can customize the UI and styling of the app to fit your project's requirements.

License
This Task Management App is open source and available under the MIT License.

Feel free to modify and adapt the app according to your needs. Contributions are welcome.

Troubleshooting
If you encounter any issues or have questions regarding the Task Management App, please open an issue in the repository or contact on my email.
Contact
For additional information or inquiries about the Task Management App, you can contact me at tusharaggarwal274@gmail.com.

