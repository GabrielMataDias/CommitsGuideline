
# Commit Message Guidelines for .NET Projects

## Overview
This document outlines the standardized commit message format for our .NET projects. Adhering to these guidelines facilitates clear communication, efficient project management, and a professional workflow in our development process.

## Commit Types
- `feat`: Introduces a new feature or functionality.
- `fix`: Addresses a bug or issue in the existing code.
- `docs`: Changes related to documentation, including README updates.
- `test`: Modifications or additions to unit tests.
- `build`: Changes affecting build files and dependencies.
- `perf`: Code alterations to improve performance.
- `style`: Code style updates (formatting, missing semi-colons, etc.).
- `refactor`: Code changes that neither fix a bug nor add a feature.
- `chore`: Routine tasks or updates (e.g., package management).
- `ci`: Modifications related to continuous integration setup.
- `raw`: Changes involving configuration files, data files, parameters.

## Message Structure
### Title
- The title should be concise yet descriptive.
- Begin with the type of commit, followed by a colon and a brief description.
- Use imperative mood in the title.

### Body
- Provide a detailed explanation of the changes.
- Use bullet points for multiple changes.
- Reference related task IDs or issue numbers.

### Footer
- Include additional metadata such as `Reviewed-by` and task references (e.g., Trello or Jira IDs).

## Examples
- `git commit -m "feat: Implement user authentication system"`
- `git commit -m "fix: Resolve null reference exception in DataService"`
- `git commit -m "docs: Update README with new API documentation"`
- `git commit -m "perf: Optimize query performance in ReportGenerator"`
- `git commit -m "refactor: Refactor User class for better readability"`

## Best Practices
- Keep commits atomic: Each commit should represent a single logical change.
- Write clear and meaningful commit messages.
- Avoid generic messages like 'fix bug' or 'update file'.
- Review commits for clarity and relevance before pushing.

---

*Commit with purpose, clarity, and professionalism.*
