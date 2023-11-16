# Cheatsheet

## Docker

### Test Dockerignore File

You can use [this shell script](https://gist.github.com/sgdan/1cc6a8becc023d3b9b2c7b9dd379f102).

Note that the commonly suggested `rsync -avn . /dev/shm --exclude-from .dockerignore` method sorta works, but there's some extra syntax in `dockerignore` not in `rsync`.

[Dockerignore Syntax](https://docs.docker.com/build/building/context/#syntax), [Processor](https://github.com/jayjansheski/codebook/edit/main/cheatsheet.md)

---

## Git

- [GitHub's cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet/)
- [GitHub's .gitignore files](https://github.com/github/gitignore)

---

Revert to specific commit ([source](https://stackoverflow.com/questions/4372435/how-can-i-rollback-a-git-repository-to-a-specific-commit))
```sh
git reset --hard commitID
```
> This command completely removes the changes made after the specified commitID, effectively reverting the code back to its previous state.

