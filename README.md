# Lufti's Task Manager CLI Project 📝

### 1. Project Overview
This is a Command Line Interface (CLI) application built with **Node.js**. The app allows you to manage a to-do list directly from your terminal. It supports creating tasks with different priority levels and saves all data into a local `tasks.json` file so your information is never lost.

### 2. How to Run the Project
1. Ensure you have **Node.js** installed on your computer.
2. Open your terminal or command prompt.
3. Navigate to the `task-tracker-cli` folder.
4. Run the commands using `node index.js`.
   *(Note: The app will automatically create the storage file for you in the data folder on the first run!)*

### 3. Examples of CLI Commands
You can interact with the app using the following commands:

* **Add a Task:** `node index.js add "Buy milk" --priority low`
* **List All Tasks:** `node index.js list`
* **List Only Completed Tasks:** `node index.js list --completed`
* **List Only Pending Tasks:** `node index.js list --pending`
* **Filter by Priority:** `node index.js list --priority high`
* **Mark as Done:** `node index.js done 1`
* **Delete a Task:** `node index.js delete 1`

### 4. Sample Terminal Output
When you run the commands, here is what the output looks like:

**Adding a task:**
```text
> node index.js add "Finish Assignment" --priority high
Task added