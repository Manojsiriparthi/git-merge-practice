Git Merge Conflict Challenge

Hello Everyone! Hope you're doing well. Today, we’ll tackle a small but exciting task in Git that will test your ability to handle merge conflicts effectively.

Challenge Overview

This repository contains two branches:

main: Includes questions with answers.

master: Includes only the questions without answers.

Your Task

✅ Clone the repository to your local system.

✅ Check the branches in your local repository. If you can't find the master branch, use the following commands:

git fetch origin

git checkout -b master origin/master

✅ Create a new branch (name it anything you like).

✅ Answer the questions in the question.txt file on your branch.

✅ Commit the changes to your branch.

✅ Check the difference between your branch's question.txt file and the main branch's question.txt file using:

git diff main <your-branch> -- question.txt

✅ Merge the main branch into your branch.

If your answers are correct and match the ones in main, the merge will succeed.

If there are differences, you will encounter merge conflicts.

✅ Resolve any merge conflicts by comparing your answers with the correct ones in the main branch.

✅ Commit the resolved changes to your branch.

Key Objectives

Practice Git basics: branching, committing, and merging.

Understand how and why merge conflicts occur.

Develop conflict resolution strategies and improve collaboration skills.

Advanced Tips

🛠️ Use git diff to analyze differences before resolving conflicts.

📜 Follow proper commit message practices for clarity and organization.

Good luck, and enjoy the challenge! 🚀


