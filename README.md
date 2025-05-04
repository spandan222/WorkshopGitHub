# Version Control Workshop

Welcome to the Version Control Workshop repository! This repository serves as a hands-on learning resource for beginners getting started with Git and GitHub.

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

## Overview

This repository contains a simple HTML page demonstrating Git and GitHub basics for version control. It's designed as a starting point for workshop participants to practice common Git commands and workflows.

## Getting Started

### Prerequisites

- Git installed on your computer (Download from [git-scm.com](https://git-scm.com/downloads))
- A GitHub account (Sign up at [github.com](https://github.com/))
- A text editor of your choice (VS Code, Sublime Text, etc.)

### Fork and Clone the Repository

1. Fork this repository by clicking the "Fork" button at the top right of this page
2. Clone your forked repository to your local machine:
```bash
git clone https://github.com/YOUR-USERNAME/hello-github.git
cd hello-github
```

## Workshop Exercises

### Exercise 1: Add Yourself to CONTRIBUTORS.md

1. Open `CONTRIBUTORS.md` in your text editor
2. Add your name and GitHub username using the format provided
3. Check the status of your changes:
   ```bash
   git status
   ```
4. Stage your changes:
   ```bash
   git add CONTRIBUTORS.md
   ```
5. Commit your changes:
   ```bash
   git commit -m "Add [YOUR NAME] to contributors list"
   ```

### Exercise 2: Collaborate with Others (Fork & Pull Request Workflow)

1. Push your changes to your forked repository:
   ```bash
   git push origin main
   ```
2. Go to your fork on GitHub and click "Pull Request"
3. Create a new Pull Request to the original repository
4. Have the workshop instructor or another participant review and merge your changes
5. Update your fork with changes from the original repository:
   ```bash
   git pull
   ```

## Common Git Commands

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository |
| `git status` | Check the status of your working directory |
| `git add <file>` | Stage changes for commit |
| `git commit -m "message"` | Commit staged changes |
| `git log` | View commit history |
| `git branch` | List branches |
| `git checkout <branch>` | Switch to another branch |
| `git merge <branch>` | Merge a branch into your current branch |
| `git pull` | Fetch and merge changes from remote |
| `git push` | Push commits to remote repository |

## Additional Resources

- [Official Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [Interactive Git Learning](https://learngitbranching.js.org/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to all workshop participants for your enthusiasm and engagement!
- Happy coding and committing!