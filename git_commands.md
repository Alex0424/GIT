# GIT COMMANDS

```
git pull                                # download the latest updates from branch
git add                                 # add files to stage
git commit                              # 
git push                                # push changes to repo
git log                                 # show all previus commits in your current branch
git log --oneline                       # show all previus commits with smaller information
git show <commit id>                    # replace id | this shows changes 
git branch -a                           # list all branches
git branch -c <branch_name>             # create a new branch
git branch -d <branch_name>             # delete a local branch
git branch -D <branch_name>             # force delete branch locally
git diff file                           # difference made in a file
git diff --cached                       # difference that in a file that is staged
git diff <commit_id>..<commit_id>       # difference between 2 selected commits
git checkout <file>                     # undo changes in a file to recent git push change
git restore --staged <file name>        # restore a staged file
git revert HEAD                         # revert a commit | this would be saved as history in a commit
git reset --hard <commit_id>            # go back in time to a commit_id and remove future history/commits | won't create a commit in timeline
```
