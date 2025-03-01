# Todo List Application (TypeScript)## Features

- Add new todo items
- Mark todo items as completed
- Remove todo items
- List all todo items

---

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (latest LTS recommended)
- TypeScript (install globally if not installed):
  ```sh
  npm install -g typescript
  ```

---

## Running the **Interactive CLI Version** (Accepts User Input)

### Open the project folder
```sh
  cd <repo-folder>
```
### Initialize package.json
```sh
  npm init -y
```

### Compile the TypeScript file
```sh
  tsc todo.ts
```

### Run the compiled JavaScript file
```sh
  node todo.js
```

### Follow the on-screen menu
The application will prompt you with options:
- Press `1` to add a task
- Press `2` to complete a task
- Press `3` to remove a task
- Press `4` to list tasks
- Press `5` to exit

---

## File Structure
```
|-- todo.ts       # TypeScript source code
|-- package.json  # Json package
|-- todo.js       # Compiled JavaScript file
|-- README.md     # Documentation
```

---
