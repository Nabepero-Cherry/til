`git cherry-pick {commit hash}` command allows to pick commits from different branch and apply it to current working branch.

#Commands
1. `git cherry-pick {commit hash}`
    If there are file conflicts, resolve conflict and
    `git add directory\filename.php`
    `git cherry-pick --continue`

2.  `git cherry pick A..D`
     To cherry-pick a certain range of commit where `A` is the oldest commit `D` is the latest commit hash.
     This command will pick and apply changes for commits `A-B-C-D`