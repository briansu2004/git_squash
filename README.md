# git_squash

How to git squash?

## Before

6 commits

![1678404503231](image/README/1678404503231.png)

## Commands

6 - 1 = 5

```dos
git reset --soft HEAD~5
git commit --amend
# :q
git push -f
```

## After

![1678405098807](image/README/1678405098807.png)
