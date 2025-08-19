# POC - Git

[Repository Link](https://github.com/raj-thombare2/task1)

## 1. Git Init & Hidden Folder

```bash
git init
ls -a
```

## 2. Git Staging & Commit

```bash
git add <filename>
git add .
git reset <filename>
git restore <filename>
git restore --staged <filename>
git commit -m "message"
git log
git log --oneline
```

## 3. Git Branching & Merge

```bash
git branch <branch>
git branch -a
git switch <branch>
git switch -c <branch>
git checkout <branch>
git checkout -b <branch>
git merge <branch>
git branch -d <branch>
```

## 4. Git Revert

```bash
git revert <commit-hash>
```

## 5. Git Diff & Stash

```bash
git diff
git diff --staged
git diff <commit1> <commit2>

git stash
git stash pop
git stash list
git stash apply
git stash drop stash@{0}
```

## 6. Git Reset & Amend

```bash
git reset --soft <commit-hash>
git reset --mixed <commit-hash>
git reset --hard <commit-hash>

git commit --amend -m "new message"
git commit --amend --no-edit
git push -f
```

## 7. Git Rebase

```bash
git rebase main
git rebase -i HEAD~3
```

## 8. Git Cherry-pick & Blame

```bash
git cherry-pick <commit-hash>
git blame <file>
```
