## Working with a Local Repository

In this section, you will learn how to create and work with a local repository using Git. You can use the following Git commands:

1. Initialize an empty Git repository:

git init


2. Show the status of your repository:

git status


3. Stage a specific file:

git add readme.txt


4. Stage all changed files:

git add .


5. Commit the staged files:

git commit -m "Create readme file"


6. Define notepad as an editor. It will be used when you run the git commit command without -m parameter:

git config --global core.editor notepad


7. Show the changes of a specific file:

git diff readme.txt


8. Show the changes in your working directory:

git diff


9. Show the changes in your staging area:

git diff --staged


10. Show the history/log:

git log


11. Show the history/log with one commit per line:

git log --pretty=oneline


12. Checkout a specific commit by its snapshot hash:

git checkout b346471


13. Navigate back to your main branch:

git checkout main



Now you know how to work with a local repository using Git.
