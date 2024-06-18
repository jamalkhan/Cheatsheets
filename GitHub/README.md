# Git Cheatsheet

Here are some commonly used Git Commands

```
/// show the current status of your repo.
git status

/// check out an existing branch named prod
git checkout prod

/// create a new branch named newbranch. NOTE does not switch branches
git branch newbranch

/// switch to the new branch
git checkout newbranch

<EDIT YOUR CODE />

/// show all of the files you've edited (will show up in red if they are changed but not staged)
git status

/// open a graphical viewer to see what has changed. (Windows only)
gitk

/// stage a single file. NOTE staging a file is not the same as commiting a file. This only prepares it for a commit... Commiting actually writes the history to source control.
git add <filename>

/// stage ALL changed files
git add .

/// show all files you've edited but not staged in red, all staged files in green.
git status

/// Commit all staged files. After this command, the history will be written to your local copy of source control, but it will not be available on the server / to other users.
git commit

/// Push your branch + changes to the server
git push

/// YOU WILL NOW GET AN ERROR. This is because you have not set your local branch to have
/// a remote "upstream" destination. The error message includes a command to set a remote
/// upstream destination. 

/// Set the Upstream Branch Name, also push it to the branch
git push --set-upstream origin newbranch

<REPEAT CODE CHANGES + COMMITS UNTIL YOU'RE READY TO MERGE IT BACK INTO PROD>

/// since you're still on newbranch, merge prod into newbranch
git merge prod

 -- IF MERGE CONFLICTS
/// if any merge conflicts, use mergetool to fix merge problems
git mergetool

/// add any merge changes if necessary.
git add .

/// if any merge conflicts, after merging, commit your changes. (use git status and gitk if necessary)
git commit

/// push the merge to the server.
git push

-- END IF MERGE CONFLICTS

/// Now that your branch is up to date with prod... merge your branch into prod
git checkout prod

/// Merge brach into prod
git merge branchname

/// If necessary resolve merge conflicts.

/// Then push it to the server
git push
```
