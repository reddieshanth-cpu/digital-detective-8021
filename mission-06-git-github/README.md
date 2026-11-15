# Mission 6 — Git and GitHub

## 1. Task / Objective

Understand version control, practise the basic Git workflow, create and use a branch, publish changes to GitHub, create a Pull Request and explain how Git supports collaboration.

## 2. Work Completed

- Checked the repository status using Git.
- Viewed recent commit history.
- Created a new branch named `update-about`.
- Updated the root `README.md` with a **My Learning** section.
- Staged and committed the README changes.
- Published the `update-about` branch to GitHub.
- Created Pull Request #1 from `update-about` into `main`.
- Reviewed the Pull Request and confirmed there were no merge conflicts.
- Kept the Pull Request open without merging it.

## 3. Commands / Tools Used

| Command | Purpose |
|---|---|
| `git init` | Initialises a Git repository. |
| `git status` | Checks the current repository status. |
| `git add README.md` | Stages the selected README file. |
| `git commit -m "message"` | Records staged changes in Git history. |
| `git log -5 --oneline` | Displays the five most recent commits. |
| `git branch` | Lists available local branches. |
| `git switch -c update-about` | Creates and switches to a new branch. |
| `git push -u origin update-about` | Publishes the branch and sets its upstream. |
| `git pull` | Retrieves and integrates remote changes. |

**Tools used:** macOS Terminal, Git, GitHub and TextEdit.

## 4. My Understanding

Git is a version control system that tracks changes in files. GitHub is an online platform used to host Git repositories and collaborate with other developers.

### Difference between staging and committing

- **Staging:** `git add` selects the changes that should be included in the next commit.
- **Committing:** `git commit` records the staged changes in the local Git history.

### Branch

A branch is a separate line of development. It allows developers to work on new changes without directly modifying the main branch.

### Pull Request

A Pull Request (PR) is a request to review changes from one branch before merging them into another branch. It allows team members to review, discuss and check changes.

### Why branches and Pull Requests are useful

They allow developers to work independently, review changes before merging and reduce the risk of directly affecting the main project.

## 5. Git Command Glossary

- `git init` — Initialises a new Git repository.
- `git status` — Displays the current status of files.
- `git add` — Stages selected changes.
- `git commit` — Records staged changes.
- `git log` — Displays commit history.
- `git branch` — Creates or lists branches.
- `git switch` — Switches between branches.
- `git push` — Publishes local commits to a remote repository.
- `git pull` — Retrieves and integrates remote changes.

## 6. Difficulties Faced

Initially, understanding the difference between branches, commits and Pull Requests was confusing. I also needed to understand how changes made on a separate branch could be reviewed before merging.

## 7. How I Resolved Them

I practised creating the `update-about` branch, editing the root README, staging and committing changes, and pushing the branch to GitHub. I then followed GitHub's interface to create and review a Pull Request.

## 8. Evidence / Files

- `mission-06-git-github/README.md` — Mission documentation.
- Root `README.md` — Updated with the My Learning section.
- Branch: `update-about`.
- Commit on branch: `d833f2b`.
- Pull Request: [#1 — Add learning summary to root README](https://github.com/reddieshanth-cpu/digital-detective-8021/pull/1).

## 9. Commit Details

**Branch:** `update-about`

**Branch commit message:** `Add learning summary to root README`

**Branch publication:** Successfully pushed to GitHub.

**Pull Request:** #1 — Open and not merged.

**Mission 6 README commit:** Pending.

The Mission 6 documentation will be committed and pushed separately after completing this README.