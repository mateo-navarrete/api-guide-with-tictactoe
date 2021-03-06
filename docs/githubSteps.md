### GITHUB STEPS

`git branch`
** // checks which branch you’re in **

`git branch NEW_BRANCH_NAME`
** // creates new_branch_name **

`git checkout NEW_BRANCH_NAME`
** // selects new_branch_name **

`git add .`
** // add files to update **

`git commit -m “commitMsg"`
** // commit files **

`git checkout master`
** // switch to local master branch

---

`git push origin NEW_BRANCH_NAME`
** // push from new_branch_name => allows for tracking pull requests form github.com/REPO_NAME **

**OR**

`git merge NEW_BRANCH_NAME`
** // merge branch updates to local master branch

`git push origin master`
// push updates from local master branch => changes are automatic (iow cannot track pull request files changes this way!)

---
Navigate to Github.com/REPO_NAME:

https://github.com/dianacgaona/api-guide-with-tictactoe

1. * click branch link
 * press newPullRequest button (associated with NEW_BRANCH_NAME)

**OR if available:**

1. * press green compareAndPullRequest button

## IMPORTANT!!!

** 2. Update the base fork drop down button (the far left button) to the local repo (iow change it to the forked repo, NOT the original repo!) **

3. press green createPullRequest button
4. press green mergePullRequest button
5. press green confirmMerge button
---

'`git branch`
** // checks which branch you’re in **

`git checkout master`
** // switch to master branch if not there already **

`git pull origin master`
** // update local master branch **
