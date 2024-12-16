# Contribution Guide
This guide outlines the process for contributing to the viviboom open source project.


## Guidelines
**Replace all copyrighted assets:**
Logos, images, and animations provided in the source code are for reference only and must be replaced with your own assets.

1. Branching and Pull Requests: Use a descriptive branch name following the format feature/* for new features or fix/* for bug fixes (e.g., fix/read-me).
    ```bash
    git checkout -b feature/your-feature-name
    ```
1. Create a new branch for your work:
    ```bash
    git checkout -b feature/<feature-name>   # For new features
    git checkout -b fix/<issue-name>        # For bug fixes
    ```
    - Example:
    ```bash
    git checkout -b fix/read-me
    ```
1. Commit your changes:
    ```bash
    git add <modified_files>
    git commit -m "Your commit message"
    ```
1. Push your branch:
    ```bash
    git push origin feature/your-feature-name
    ```
1. Create a pull request:
    - Go to the project repository on GitHub.
    - Locate your branch and click "New Pull Request."
    - Assign someone to review your pull request.

## Files Structure
Here's an overview of the project's directory structure:

Directory   |   Purpose
------------|----------
**Apis**  |         Files related to APIs
**Components**    |    Components that render to the screen
**Config**    |        Multi-environment configurations
**Css**   |           Images and styles
**Data**  |          Global constant variables
**Enums** |         Named constants
**Hooks**   |     Custom hooks
**Js**    |            External static files (considered for merging into css & project)
**Redux** |         Redux actions and reducers
**Sass**  |          External static files (considered for merging into css & project)
**Socket**    |         Event handlers for sockets
**Store** |         Application state data
**Tests** |          Unit tests
**Translations**  |  Translated terms for views
**Utils** |          Utility functions

## Coding Conventions

#### File Naming
- Use snake_case for filenames (e.g., my_component.jsx).

#### Variable Naming
- Use PascalCase for enums and keys (e.g., FirstName)
- Use camelCase for variables (e.g., isLoggedIn).
- Use PascalCase for imported objects (e.g., MyComponent).

#### Styling
- Primarily use margins and paddings in increments of 4 (unless there are obscure cases).


If the convention is not otherwise stated, refer to airbnb's convention https://github.com/airbnb/javascript/tree/master/react


**We appreciate your contributions to this project!**


