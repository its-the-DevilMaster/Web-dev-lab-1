# P3 – Feature Branch Git Workflow

## Aim
To understand and implement the feature branch workflow using Git and GitHub.

## Objective
To learn how to create a separate branch, make changes without directly modifying the main branch, and merge those changes back into the main branch.

## Procedure

1. Checked the current branch using `git branch`.
2. Created a feature branch named `feature/about-section`.
3. Switched to the newly created feature branch.
4. Modified the About Me section in the portfolio's HTML file.
5. Checked the modified files using `git status`.
6. Staged the changes using `git add`.
7. Committed the changes using `git commit`.
8. Pushed the feature branch to GitHub.
9. Switched back to the main branch.
10. Merged the feature branch into the main branch.
11. Pushed the updated main branch to GitHub.

## Git Commands Used

| Command -- Description |
| `git branch` -- Displays available branches |
| `git checkout -b feature/about-section` -- Creates and switches to a new branch |
| `git status` -- Displays the current working status |
| `git add` -- Stages the changes |
| `git commit` -- Saves changes in the repository |
| `git push -u origin feature/about-section` -- Pushes the feature branch to GitHub |
| `git checkout main` -- Switches to the main branch |
| `git merge feature/about-section` -- Merges the feature branch into main |
| `git push` -- Pushes the updated main branch to GitHub |

## Result
Successfully implemented the feature branch workflow by creating a new branch, modifying the portfolio, committing and pushing changes, and merging the feature branch into the main branch.