README.md

AS A project team member with multiple tasks to organize
I WANT a task board
SO THAT I can add individual project tasks, manage their state of progress and track overall project progress accordingly

GIVEN a task board to manage a project
WHEN I open the task board
THEN the list of project tasks is displayed in columns representing the task progress state (Not Yet Started, In Progress, Completed)
WHEN I view the task board for the project
THEN each task is color coded to indicate whether it is nearing the deadline (yellow) or is overdue (red)
WHEN I click on the button to define a new task
THEN I can enter the title, description and deadline date for the new task into a modal dialog
WHEN I click the save button for that task
THEN the properties for that task are saved in localStorage
WHEN I drag a task to a different progress column
THEN the task's progress state is updated accordingly and will stay in the new column after refreshing
WHEN I click the delete button for a task
THEN the task is removed from the task board and will not be added back after refreshing
WHEN I refresh the page
THEN the saved tasks persist

Thank you for your hard work and effort on the Module 5 Third-Party APIs Challenge. While the result may not be what you hoped for, remember that every project is an opportunity to learn and grow. Here are some specific points to focus on for improvement:

Application Deployment:

It appears that your application isn't deployed. Deployment is a critical step in sharing your work with others. Look into platforms like GitHub Pages, Netlify, or Vercel for easy deployment options. This will allow others to access and interact with your application.

Delete Task Functionality:

The application currently does not support deleting tasks. Implementing this feature is essential for task management. Review how to add event listeners for delete actions and update your code accordingly.

Add Task Modal:

The 'Add Task' button opens a modal dialog with input fields for title and description, which is a good start. However, including a due date using a jQuery date picker would enhance this feature. Continue refining this functionality to improve user input options.

localStorage Implementation:

No application changes are persisted via localStorage. This is crucial for data persistence. Review the basics of localStorage and try implementing it to save tasks, delete tasks, and change the status of tasks. This will ensure that user data is not lost when the page is refreshed.

Task Color Coding:

Tasks are not color-coded to indicate whether they are due today or overdue. Implementing this feature will greatly enhance the user experience by providing visual cues about task urgency. Use conditional styling in CSS or JavaScript to achieve this functionality.

Repository README:

Your README is missing key elements such as screenshots, a description, and a link to the deployed application. A high-quality README is essential for presenting your project professionally. Refer to this guide on writing a great README for help.
User Experience:

The application user experience could be more intuitive and easy to navigate. Focus on simplifying the design and improving the navigation flow. User testing and feedback can help you identify areas for enhancement.

User Interface:

The user interface could be improved to be cleaner and more polished. Pay attention to design principles and consider exploring modern UI/UX trends. A more refined interface will make your application more appealing and user-friendly.

Mock-Up Functionality:

The application could resemble the mock-up functionality provided in the challenge instructions more closely. Pay attention to the details in the mock-up and strive to match your application's layout and features accurately.

Remember, each project is a learning experience. By focusing on these areas, you can significantly enhance your project and your skills. Don’t hesitate to seek help from peers, mentors, or online resources to overcome these challenges.
