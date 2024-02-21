
## Commit Guidelines

### Commit Types:
- **[UPDATING]:** Use this when updating existing code.
- **[FIX]:** Use this when fixing a bug or resolving an issue.
- **[ADDED]:** Use this when adding new features or functionalities.
- **[REMOVED]:** Use this when removing code, files, or features.
- **[DOCUMENTATION]:** Use this when updating or adding documentation.
- **[TEST]:** Use this when adding or modifying tests.
- **[STYLE]:** Use this when making code style changes (e.g., formatting, indentation).
- **[REFACTOR]:** Use this when refactoring code without changing its external behavior.

### Commit Message Format:
- For updating code, the commit statement should start with "[UPDATING]" followed by a brief description of the update.
  Example: `[UPDATING] Fixed formatting issue in README.md`

- For fixing a bug or resolving an issue, use "[FIX]" followed by a brief description.
  Example: `[FIX] Resolved null pointer exception in ModuleX`

- For adding new features or functionalities, use "[ADDED]" followed by a brief description.
  Example: `[ADDED] Implemented user authentication feature`

- For removing code, files, or features, use "[REMOVED]" followed by a brief description.
  Example: `[REMOVED] Deprecated legacy module`

- For updating or adding documentation, use "[DOCUMENTATION]" followed by a brief description.
  Example: `[DOCUMENTATION] Updated API documentation for endpointX`

- For adding or modifying tests, use "[TEST]" followed by a brief description.
  Example: `[TEST] Added unit tests for UserService`

- For making code style changes, use "[STYLE]" followed by a brief description.
  Example: `[STYLE] Improved code readability in ControllerX`

- For refactoring code without changing its external behavior, use "[REFACTOR]" followed by a brief description.
  Example: `[REFACTOR] Extracted utility function from ModuleY`

### Best Practices:

1. **Be Clear and Concise:**
   - Keep commit statements clear, concise, and focused on the changes made.

2. **Use Present Tense:**
   - Write commit messages in the present tense for consistency and clarity.

3. **Include Relevant Details:**
   - Provide enough information to understand the purpose of the commit.

4. **Reference Issues:**
   - If your commit resolves a GitHub issue, include the issue number in the commit message.
     Example: `Resolved #123: Fixed authentication bug`

5. **Separate Concerns:**
   - If a commit involves multiple changes, consider breaking them into separate commits with specific messages.

### Examples:

- `[UPDATING] Refactored database connection code`
- `[FIX] Resolved #456: NullPointerException in User class`
- `[ADDED] Implemented file upload feature`
- `[REMOVED] Deprecated function removeOldRecords()`
- `[DOCUMENTATION] Updated installation guide in README`
- `[TEST] Added integration tests for ProductService`
- `[STYLE] Improved variable naming in ModuleZ`
- `[REFACTOR] Extracted common logic from ServiceA`

### Notes:
- Feel free to customize the commit types and message formats based on your project's needs.
- Consistent and descriptive commit messages contribute to better collaboration and code maintainability.

Happy coding! 🚀
