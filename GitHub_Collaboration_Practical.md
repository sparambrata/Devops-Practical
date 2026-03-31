Practical Title:
To apply GitHub-based collaboration techniques including branching and merging

Name:
Parambrata Sanyal

Date:
March 31, 2026

Repository:
https://github.com/sparambrata/Devops-Practical

Collaborator:
https://github.com/shiv0666

Theory:

1. What is GitHub Collaboration?
GitHub Collaboration is a way for multiple developers to work together on the same project using shared repositories, branches, pull requests, code reviews, and merge workflows.

2. What is Branching in Git?
Branching is creating an isolated line of development so new features or fixes can be developed without affecting the main branch.

3. What is Merging?
Merging is combining changes from one branch into another branch, usually from a feature branch into main.

4. What is Pull Request (PR)?
A Pull Request is a GitHub feature to propose, review, discuss, and approve changes from one branch before merging into another branch.

Procedure:

Step 1: Create a GitHub Repository
Done at:
https://github.com/sparambrata/Devops-Practical

Step 2: Clone Repository
Commands:
    cd "C:\Users\spara\Desktop"
    git clone https://github.com/sparambrata/Devops-Practical.git
    cd Devops-Practical

Step 3: Create a New Branch
Commands:
    git switch -c lab2-collaboration

Step 4: Make Changes and Commit
Commands:
    echo "Collaboration practical update" >> practical2.txt
    git add practical2.txt GitHub_Collaboration_Practical.md
    git commit -m "Add collaboration practical content"

Step 5: Push Branch to GitHub
Commands:
    git push -u origin lab2-collaboration

Step 6: Create Pull Request on GitHub
Open:
https://github.com/sparambrata/Devops-Practical/compare/main...lab2-collaboration

Step 7: Merge Pull Request
Merge using GitHub web interface after review.

Step 8: Pull Updated Code
Commands:
    git switch main
    git pull origin main

Output Screenshots:
Picture 1: Repository page on GitHub
Picture 2: Clone command output in terminal
Picture 3: Branch creation output
Picture 4: Commit output
Picture 5: Push output
Picture 6: Pull Request page
Picture 7: Merge confirmation page
Picture 8: Pull latest code output

Activity / Task:

Task 1:
Create a repository and collaborate with at least one teammate.

Repository Link:
https://github.com/sparambrata/Devops-Practical

Collaborator Link:
https://github.com/shiv0666

Task 2:
Write the steps to resolve merge conflicts.

Steps to resolve merge conflicts:
1. Pull latest changes:
   git pull origin main
2. Start merge:
   git merge branch-name
3. Check conflicts:
   git status
4. Open conflicted files and remove conflict markers.
5. Keep correct final content and save files.
6. Stage resolved files:
   git add .
7. Complete merge:
   git commit -m "Resolve merge conflict"
8. Push updates:
   git push origin main

Advantages of GitHub Collaboration:
1. Better team coordination and visibility.
2. Safe experimentation through branches.
3. Structured review process with pull requests.
4. Clear history and accountability of changes.
5. Easy integration with project and CI tools.

Challenges:
1. Merge conflicts during parallel development.
2. Poor branch management can create confusion.
3. Delayed reviews can slow team progress.
