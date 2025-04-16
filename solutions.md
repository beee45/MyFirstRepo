Git 101🧑🏻‍🚀
Exercise 1
• [ ] Who created git? and what is the essence of git.
Ans: Linus Torvalds, basically for code tracking(changes), and allows multiple people to work on the same project. It tracks and records of the work
Exercise 2
• [ ] What is the difference between git, gitlab and github?
Ans: Git is a language (version control system), GitHub is an app for sharing git repositories, and git lab is a platform that uses git with some additional features to have more control of repositories
Exercise 3
• [ ] Apart from git, is there any other version control system? If there is, kindly list them.
Ans: Concurrent Version System (CVS), Subversion (SVN)

Exercise 4
• [ ] What does git status do?
Ans: shows changes in the directory and staging area

Exercise 5
• [ ] What is a commit in git. Explain and show examples of a commit in the terminal.
Ans: It’s a snapshot of changes saved in the repo. We use git commit after git add to commit our changes
Exercise 6
• [ ] In git, there is a way to ignore file, how is this done.
Ans: Yes use gitignore file
o [ ] Create some files and intentionally ignore them.
Exercise 7
• [ ] What does git log do? Show examples of git log in the terminal.
Ans: Shows the commit history
Exercise 8
• [ ] What does it mean to do git add.
Ans: its stagging the changes
Exercise 9
• [ ] What is a staging area in git and how do you get items into the staging area.
Ans git add (file name) is used and stagging is the initial process before committing. You cannot commit without staging
o [ ] Illustrate this in the terminal by moving an untracked file to the tracked state and then staging area.
Exercise 10
• [ ] How do you commit in git with the message on the same line?
Ans: git commit -m” the message”
Exercise 11
• [ ] What is the difference between the pull, push and fetch command in git.
Ans: pull fetches sand merges remote changes into local branch, push sends local commit to repo and fetch updates from the repo but doesn’t change local files
Exercise 12
• [ ] What command do you run in git, if you want to see more information about a remote in git. Illustrate this in the terminal and try and understand the output.
Ans: git remote -v
Exercise 13
• [ ] What is the difference between rebase and merge in git. Illustrate with examples.
Ans: Merge combines branches with a new commit and rebase moves commits to the top of another branch
Exercise 14
• [ ] What is git checkout?
Ans: It is used to switch between branches  
o [ ] git checkout has another alias. What is it?
Ans: git switch
o [ ] Show that both checkout and its alias are doing the same thing in the terminal.
Exercise 15
• [ ] What are tags in git, and what types of tags are there?
Ans: It is a mark in specific points in the history
Exercise 16
• [ ] What are git aliases. Alias your favorite git command and show it in the terminal.
Ans: Custom shortcuts for git commands
Exercise 17
• [ ] Can you change a branch name? If yes what is the command? Illustrate this in the terminal.
Ans: git branch -m your-name
Exercise 18
• [ ] What does git pull do?
Ans: pull fetches sand merges remote changes into local branch
Exercise 19
• [ ] Do you know that, you can delete a branch in git?
Ans: git branch -D (branch name)
o [ ] Create a branch and delete it.
o [ ] Wait....what is the difference between deleting with -d and -D arguments in git?
