# Contributing to Project POS

All forms of contributions are welcome and appreciated. Refer to the Table of Contents for various ways to assist and details on how this project manages them. Be sure to read the pertinent section before contributing.

## Table of Contents

-   Making a branch (Github)
-   How to work with git?
-   Pull requests
-   Github issues
-   Adding a new library
-   Coding Practices (Style Guide)

## Making a branch (Gitflow)

### Naming a branch

When naming your branch, follow this format: start with a description of the task you're working on, then add a `/` and specify the component. e.g (`feat/login`)

Use these keywords:

-   `feat` for a new feature branch.
-   `refactor` when modifying a branch for code optimization.
-   `fix` for addressing a bug within that branch.
-   `docs` for any changes linked to documentation.

### `master` branch

-   this serves as our primary branch where all features and code adjustments are merged. (Don't work in your master branch)

### `feat` branches (in your own repos)

-   these branches are intended for developing new features.
-   once ready, they will be merged into the `main` branch.

### `refactor` branches (in your own repos)

-   for refactoring or enhancing specific features within the `develop` branch.

### `fix` branches (in your own repos)

-   for addressing and fixing bugs within the `develop` branch.

## How to work with git?

- Create a new branch for each feature you're working on. This allows for numerous small, independent pull requests instead of one large one with various unrelated features.
- Avoid using GitHub's online edit function, as it often results in messy and non-functional commits.
- Strive for well-organized commits with clear, readable, and detailed commit messages, adhering to our format.

    ```css
    fix(login): fix login logic;
    ```

You can also check this out for more [commit message guide](https://github.com/RomuloOliveira/commit-messages-guide).

-   Make small pull requests that are easy to review but make sure they do add value by themselves / individually

## Pull requests

-   When creating a new pull request, please make sure to utilize and complete our pull request template available in the .github directory.

```css
.github/
    -- PULL_REQUEST_TEMPLATE/
        --PULL_REQUEST_TEMPLATE.md
```

-   the commit series in the PR should be _linear_ (it **should not contain merge commits**). This is necessary because we want to be able to bisect bugs easily. Rewrite history/perform a rebase if necessary

-   PRs **should not have conflicts** with master branch. If there are, please resolve them rebasing and force-pushing

## Github issues

- When creating a new branch and pull request, it is crucial to also create a new GitHub issue in the Projects tab. This issue should be directly linked to the branch you are working on.

- Furthermore, ensure the pull request is connected to the newly created GitHub issue. This practice allows all project contributors to easily see the ongoing tasks and their progress.


## Coding Practices (Style Guide)

Explore our comprehensive style guide in the `STYLE_GUIDE.md` document.
