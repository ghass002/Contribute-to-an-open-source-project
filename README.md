# Contribute to an open source project

Steps to contribute to an open source project on GITHUB:
1. Fork the project into your GITHUB profile
2. Clone the folder using git
3. Look for the contributing guideline in the #contributing.md# file in the project and follow their steps
4. Create a new branch to be able to do changes without affecting the master branch:
      1. git branch <name-branch>
      2. git checkout <name-branch>
- Open your code in your favorite IDE and start making changes and coding
- Apply contribute guidelines to your code to be ready for master branch
- take a look at the difference between the original code and your code: git diff
- Make sure you are in sync with Master by switching to Master and pull request: 
      * git checkout master
      * git pull
- If you are already up to date switch to the contributing branch and set the branch to sync with master:
      - git branch --set-upstream-to=origin/master <name-branch>
- Submit these changes: 
      - git add . 
      - git commit -m "your-commit"
      - git push origin <name-branch>
- Return to your forked repo and submit a pull request according to the contributing guidelines 
- Wait for code review
  
