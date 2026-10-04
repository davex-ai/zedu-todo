# AGENTS.md

Instructions for any AI agent working in this project. Read this file before starting and follow it for every task.

## Project

A single-file todo list app (`todo.html`). No build step, no dependencies. Tasks persist in the browser via `localStorage`.

## Scope

In scope: add, complete, delete, filter (all / open / done), clear completed.
Out of scope for now: deploying to the web, pushing to GitHub, accounts, syncing.

## How to work

1. **Plan first.** Before editing, write a short plan (3-5 bullets) of what will change and why.
2. **One change at a time.** Make the smallest change that moves the task forward, then check it before starting the next.
3. **Keep it single-file.** HTML, CSS and JS stay in `todo.html`. Do not add frameworks or build tools without asking.
4. **Verify.** After each change, open the page and confirm: add a task, complete it, filter, delete, reload and check it persisted.
5. **Report.** End each task with a two-line summary: what changed, and what to do next.

## Code conventions

- Plain JavaScript, no frameworks. Small functions with clear names.
- Use CSS variables for colors; support light and dark mode.
- Always wrap `localStorage` access in `try/catch`.
- Keep the UI accessible: labels on inputs and buttons, visible focus, keyboard support (Enter adds a task).
- UI copy: sentence case, plain verbs, same name for an action everywhere ("Add task", "Delete").

## Todo workflow for the agent

Track your own work in this order and update the status as you go:

- [x] Build the todo list app
- [x] Write AGENTS.md
- [ ] (Skipped) Deploy to the web
- [ ] (Skipped) Push to private GitHub

## Do not

- Do not delete the user's data or change the `todos` storage key without a migration.
- Do not add features outside the scope above without asking first.
- Do not leave debug code or console logs behind.
