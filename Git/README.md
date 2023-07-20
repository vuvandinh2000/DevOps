# Git command
```bash
git branch -c <branch-name> # create new branch, (same code with CURRENT branch)
git branch -a # list all branch and remote

git diff <last commit>..<before commit> # xem diff cua before va last
```

# Rollback
```bash
git checkout <filepath> # neu file chua duoc staging (git add), neu da staging can `git restore --staged <file>`
git revert HEAD # redo commit gan nhat (tao ra 1 commit moi la "Revert 'last commit'")
git reset --hard <commit id> # redo commit id (khong tao ra commit moi)
```