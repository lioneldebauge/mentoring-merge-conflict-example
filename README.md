# How to create a merge conflict ?

1. Create a branch with the following `git checkout -b conflict-branch`
2. In the User model modify the name of the method `hello` to `salut`
3. Commit
4. Go to the main branch (`git checkout main`)
5. In the User model modify the name of the method `hello` to `good_morning`
6. Commit
7. Go to conflict-branch (`git checkout conflict-branch`)
8. Try to merge main inside conflict-branch (`git merge main`)

# Best practice to avoid conflicts

1. Make sure that your main branch is up to date. Especially when you create feature branch from your main branch.
2. Make sure that your feature branch is always up to date with your main branch by running `git merge main-branch-name`
3. Use VS Code editor interface to solve merge conflicts easily.

Good luck 💪 
