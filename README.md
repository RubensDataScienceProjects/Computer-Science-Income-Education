# Computer-Science-Income-Education
Overleaf: https://www.overleaf.com/project/65c3a6e6089768143fa5e722

Small Git Guide:
1. Download git: https://git-scm.com/downloads
2. Open up command prompt and check if the command "git" will give an output, if so it is installed correctly
3. Go to a folder where you want to work on with the jupyter notebook with the command: "cd *file path * "
4. Type: "git clone https://github.com/RubensDataScienceProjects/Computer-Science-Income-Education" (you might see an authorization here or later at the steps)
5. You should see a file named .git in the folder in the windows explorer, if not, click on the folder with the Project name and also make sure to go there in the command prompt with "cd *folder name *"
6. the command "git status" will now show you, it is correctly installed
7. Remember the following commands in this order to push new edited files in the online repo:
   * "git add .": takes all modified files in your working directory and places the modified version in a staging area (dont forget the dot in the command)
   * "git commit -m "*message *" takes everything from the staging area and makes a permanent snapshot of the current state of your repository and the message (the command should look like: "git commit -m "test commit" "
   * "git push": to push it from the local repo to the online repo
