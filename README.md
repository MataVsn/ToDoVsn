# ToDo web application using Vue, as a homework.
## This  is a simple web application that allows you to add and display a list of tasks. It's built using Vue.js.
## Functionality:
+ View task
+ Add task
+ Remove Task
+ Set task as completed

### The project consists of the following main components:
  + Card Input: A component that displays a form for adding new tasks.
  + Card: A component that displays a single task in the list.

### Data structure

The project uses a reactive `ref` link to store a list of tasks. Each task is represented by an object with the fields `id`, `title`, `descr` and `status'. `id` is the unique identifier of the task, `title` is the title of the task, `desc` is the description of the task, `status` is the status of the task (true - completed, false - not completed).

### Adding Tasks

To add new tasks, use the form in the `Card Input` component. Enter the title and description of the task, then click the "Add Task" button. The new task will be added to the list and displayed in the `Card` component.

## Installation and launch
1. Clone the repository using the command: git clone https://github.com/matavsn/ToDoVsn
2. Go to the project directory: cd ToDoVsn
3. Install the dependencies by running the command: npm install
4. Start the local development server: npm run dev

