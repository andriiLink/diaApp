# React TypeScript Starter Pack

To use this template click `Use this template`

### Available Scripts

`Deploy` - available to deploy your application to gh-pages, to deploy the project, change the second line of code in package.json, specifically the homepage value, from "." to the repository name

`SCSS Preprocessor` - available to write your styles with modern style language

## Project Overview: Todo Application

This is a full-featured task management application (**Todo App**) designed to showcase best practices using React and TypeScript for frontend development and API interaction.

### Core Features:

* **Create** new tasks. (A new task is added only if the input field is not empty).
    * Tasks can be created by typing in the input field and pressing the **`Enter`** key.
    * The input field is **focused automatically** upon page load, and focus returns to it after a task is created, allowing for continuous input.
* **Edit** the text of existing tasks.
    * When editing, pressing the **`Escape`** (`Esc`) key will **cancel** the changes made.
    * If you delete all text during editing, the task will be **removed**.
* **Toggle** tasks as completed/uncompleted.
* **Delete** tasks.
* **API Interaction**: Handles fetching, creating, updating, and deleting tasks via a simulated API layer.

## Project Structure

The project is organized for clean code and easy maintenance:

* **`src/components`**: Contains all reusable React components.
* **`src/styles`**: Houses all SCSS styles, grouped by component.
* **`src/types`**: Contains all TypeScript type declarations (e.g., the `Todo` type).
* **`src/utils`**: Includes utility functions, specifically for executing `fetch` requests.
* **`src/api`**: Contains files for API interaction, such as `todos.ts`, which utilizes the functions from `src/utils` to handle backend communication.
* **`index.html`**, **`App.tsx`**, **`index.tsx`**: The main application entry points.

### Installation

After cloning the repository, install the necessary dependencies:

```bash
npm install
# or
yarn install
```

## Running the Project
To run the project in development mode:

```bash
npm start
# or
yarn start
```

### Deploy
To successfully deploy the project to GitHub Pages, you must change the value of `homepage` in the `package.json` file from the current "." to your repository's name:

// package.json
"homepage": "https://<USERNAME>.github.io/<REPO_NAME>",
