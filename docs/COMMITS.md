# Commits

Good commit messages make it easier to understand the history of a project, track down bugs, and collaborate effectively. Follow these conventions when committing changes.

## ✅ "Do"s

* **Use clear, concise messages** Summarize the change in one line if possible.
  *Example:* `fix: correct typo in login button label`
* **Use imperative mood** Treat the message like giving a command.
  *Example:* `add: user profile picture upload` (not `added` or `adding`)
* **Include context for complex changes** Explain *why* the change was made if it’s not obvious.
  *Example:*

  ```
  refactor: optimize search algorithm
  ```
  
* **Reference issues or PRs** Link related tickets to provide context.
  *Example:* `fix: resolve crash on startup (#42)`

## ❌ "Don't"s

* **Don’t include unrelated changes** Each commit should do one thing.
* **Don’t commit broken code** Ensure all tests pass before committing.
* **Don’t include personal or temporary files** Example: IDE configs, `.DS_Store`, logs.
* **Don’t make huge, monolithic commits** Large PRs are hard to review and debug.

## Recommended Commit Types

Use prefixes to make your commit history consistent:

| Prefix      | When to use                                                |
| ----------- | ---------------------------------------------------------- |
| `feat:`     | Adding a new feature                                       |
| `fix:`      | Bug fixes                                                  |
| `docs:`     | Documentation changes                                      |
| `style:`    | Formatting, whitespace, semicolons, etc. (no code changes) |
| `refactor:` | Code restructuring that doesn’t fix a bug or add a feature |
| `perf:`     | Performance improvements                                   |
| `test:`     | Adding or fixing tests                                     |
| `chore:`    | Maintenance tasks (build, CI, tooling, etc.)               |

## Example Commit

```
feat: add dark mode toggle to settings
```
