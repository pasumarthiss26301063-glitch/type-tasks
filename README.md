# TypeTasks — Part 1

A TypeScript-only task model containing the required `TaskStatus` union,
`Task` interface, and typed task operations.

## Included operations

- `addTask` — adds a new `todo` task with a generated unique ID.
- `completeTask` — marks the task with the matching ID as `done`.
- `filterByStatus` — filters tasks using the `TaskStatus` union.
- `deleteTask` — extra operation: removes a task by ID.
- `countByStatus` — extra operation: counts tasks in a given status.

## Compile

Install dependencies and run the TypeScript compiler:

```bash
npm install
npm run build
```

The compiler uses `strict: true`. The intentionally invalid examples from the
assignment are not included, so the project compiles cleanly.
