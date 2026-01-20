# Git Course
This is a Git Tutorial (Commands in Terminal 👇)

1.git config --global user.name 'Demo'
2.git config --global user.email 'baskar63699@gmail.com'
3.git config --global init.defaultBranch main
4.git init
5.git status
6.git add readme.md
7.git commit -m 'readme'
8.git log
9.git add . (To add all file)
10.git commit -m 'initial commit'

# This is from bug branch

Objective - new-bug changes has to be merged with main branch 
Conflicts iruku
main -> new-bug
resolve conflicts
new-bug -> main
This is creating a new branch 👇
1.git branch bug
2.git checkout bug
3.git checkout -b feature
(To save the changes)
1.git add .
2.git commit -m 'update readme'

# To push the branch to the github
1.git push --set-upstream origin (new-bug)👈 branch name
2.git push -u origin feature (In easy way to push branch)
# To save the file After any change
a.git add .
b.git commit -m 'update readme'
3.git push
