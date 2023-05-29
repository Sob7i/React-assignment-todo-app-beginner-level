# Assignment: 
Build a Todo List App using React

## Objective: 
To create a simple Todo list application using React, where users can add, complete, and delete tasks.

### Git workflow:
1.  Fork this Git repository.

2.  Clone the forked repository to your local machine.

3.  Create a new branch for each task separately. Name the branches as follows:

    -   Branch 1: `task-1-add-todo-form`
    -   Branch 2: `task-2-display-todo-list`
    -   Branch 3: `task-3-mark-complete-delete`
    -   Branch 4: `task-4-styling`

    Note: Create additional branches for any additional tasks or improvements you implement.

4.  Start working on each task in its respective branch.
5.  Implement the required functionality for each task following the instructions provided in the README file.

6.  Make regular commits with descriptive commit messages as you progress through each task.

7.  Push your commits to your forked repository.

8.  Assign a reviewer for your pull requests.

### App requirement:
1.  Create a new React application using `create-react-app` or any other preferred method.

2.  The application should have a main component called `TodoApp` that serves as the parent component.

3.  The `TodoApp` component should maintain an array of tasks as its state.

4.  Create a child component called `TodoForm` that displays an input field and a submit button.

5.  When the user enters a task in the input field and clicks the submit button, the task should be added to the array of tasks in the `TodoApp` state.

6.  Create another child component called `TodoList` that displays the list of tasks.

7.  The `TodoList` component should receive the array of tasks as a prop from the `TodoApp` component.

8.  For each task in the array, display the task text along with a checkbox to mark the task as complete and a delete button to remove the task.

9.  When the user marks a task as complete by checking the checkbox, update the task's status in the `TodoApp` state.

10. When the user clicks the delete button, remove the task from the `TodoApp` state.

11. Bonus: Add CSS styling to make the app visually appealing.

Note: You can use functional components with hooks (such as `useState` and `useEffect`) to manage the state and update the UI.
