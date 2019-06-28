This is the readme for Sir Yes Sir (title is a wip)

Git Instructions:

######When updating your work & committing:
1. git fetch origin
2. git merge origin/master
3. [make some changes]
4. git status
5. git add .
6. git status
7. git commit -m [comment on what you changed]
8. git push

^steps 1 & 2 basically updates your local copy to match master -> if it prompts you for a reason for merge at step 2, just type ':wq' and press enter

^step 4 the files you changed should be highlighted in red

^step 6 the files you changed should be highlighted in green

######When you make changes before fetching/merging origin
1. git stash
2. git fetch origin
3. git merge origin/master
4. git stash pop

^git stash basically stashes away the changes you made, and then replaces it back when you do the pop

######When navigating on cmd line:
1. ls -> list all the files
2. cd -> change directory

######Useful commands to know:
1. git status -> shows you the status of your branch/commits
2. git diff -> shows you the differences
3. git branch -vv -> shows you all the branch versions and upstreams
4. git remote show origin -> show remote origin
5. git branch --set-upstream-to origin/[branch_name] [other_branch_name] -> for setting upstreams

Setting up (everything in square brackets are user-defined and do not include the square brackets i.e. [comment])
1. git clone https://github.com/whatthefoong/working_in_progress.git
2. git checkout -b [name_of_your_branch]
3. [make some changes]
4. git add .
5. git commit -m [comment on what you changed]
6. git push --set-upstream origin test_branch
