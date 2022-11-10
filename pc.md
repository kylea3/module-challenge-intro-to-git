## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a tool to manage source code by tracking changes in the code and allowing different branches (forks) of the original code to be worked on simultaneously by developers.
2. What is the difference between Git and GitHub?
Git is the open source software that actually tracks the changes whereas GitHub is the library that stores the updated information.
3. Why do we create a branch?
Branches allow you to work on your own version of the code without modifying the main code itself. This allows you to modify the code, make changes, and update it until it is approved to replace the main code.
4. What is the purpose of a Pull Request?
A pull request takes any of the changes you have made on your computer and pulls them into GitHub with the commentary on proposed changes.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
$ git switch -c main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
$ git fetch - Downloads all history from the remote tracking branches

$ git merge - Combines remote tracking branches into current local branch

$ git pull- Updates your current local working branch with all new commits from the corresponding remote branch on GitHub.

7. What is a merge conflict?
If there are multiple branches that have competeing commits, Git will need help deciding which changes should be included in the final merge.

8. How do you resolve a merge conflict?
Manually edit the source files to remove conflicting changes are resolved.