# Git Cheatsheet

- [GitHub's cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet/)
- [GitHub's .gitignore files](https://github.com/github/gitignore)

---

Revert to specific commit ([source](https://stackoverflow.com/questions/4372435/how-can-i-rollback-a-git-repository-to-a-specific-commit))
```sh
git reset --hard commitID
```
> This command completely removes the changes made after the specified commitID, effectively reverting the code back to its previous state.

