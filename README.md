This is the readme for Sir Yes Sir (title is a wip)

Git Instructions:

Setting up (everything in square brackets are user-defined and do not include the square brackets i.e. [comment])
1. git clone https://github.com/whatthefoong/working_in_progress.git
2. git checkout -b [name_of_your_branch]
3. [make some changes]
4. git add .
5. git commit -m [comment on what you changed]
6. git push --set-upstream origin test_branch

Subsequently, when updating your work & committing:
1. git fetch origin
2. git merge origin/master
3. [make some changes]
4. git add .
5. git commit -m [comment on what you changed]
6. git push

Useful commands to know:
1. git status -> shows you the status of your branch/commits
2. git diff -> shows you the differences
3. git branch -vv -> shows you all the branch versions and upstreams
4. git --set-upstream-to origin/[branch_name] [other_branch_name] -> for setting upstreams