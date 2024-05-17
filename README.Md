This is about the basics of the GitHub Version Control System.

What Do You Understand By Git?
Git is an open-source version control system. It is known for its light-weight, fast and easy to use nature. 

Define Version Control:
Version Control is an essential aspect of modern day web development practices. It's a way of storing the history of a project in case there is need to make some alterations in the future.

Describe The Process Of Committing A Project To Github Repository
1. Create a repository on Github by clicking on the "New" button
2. Name the repo with a name that hasn't been used by me for other repo
3. Add a description for the repo
4. On the local machine, create a folder with the same title name used for the Github repo
5. Open the folder with Vscode and add an index.html file
6. Add an html 5 code with ! and add paragraphs in between the "body" tags
7. After all these have been done, it's time to push the code on the local machine to the Github remote repo
8. In the terminal, we would initialize git with this command: git init
9. After it has been initialized, we would add the files in our local machine with this command: git add .  
10. We would then run our commit with this command: git commit -m "first commit"
11. After making first commit, we would then create a branch with this command: git branch -M main
12. To confirm we are on branch "main", we would enter this command: git branch
13. We would then link the local repo to the remote repo with the command provided on Github: git remote add origin https://github.com/Ifewoye/Td-Intro-Github-Basics.git
14. We would then push with this command: git push -u origin main
15. This would then require us to authenticate for the pushing to take place.
16. If any edit is made to the code on the local machine and we want to push the changes to the remote repo, we would enter the command: git add .
17. Then commit the new changes with: git commit -m "Description of the changes made"
18. To make the changes reflect on the remote repo, we need to push with: git push origin main