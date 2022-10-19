# git-playground

- Rebasing - checkout topic-1 branch
- Rebasing with conflict - checkout topic-2 branch
- Squashing, reordering commit - checkout topic-3 branch

## rebase
1. checkout main
2. git pull
3. checkout feature branch
4. git rebase main

or

1. at your feature branch (topic-1)
2. `git pull -r origin main` helps to skip a few steps from first option