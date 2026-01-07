This repository is made to practice the fundamentals introduced to you in the Data workshop. You must follow software best practices, and be sure to execute commands in the correct order in order to prevent changes
to the main repo. You will do the following: 

# Stage 1: Branching #
Like we mentioned in the workshop, creating your own branch from the main repository and using that as your main working area is necessary for clean and organized code. NEVER WORK DIRECTLY IN MAIN.
#### TO DO: ####
1. In the terminal, run the command: git branch [feature-yourname]
2. In order to switch into the branch, you must run the command: git checkout [feature-yourname]
3. In order to ensure that your branch was made, run the command: git branch
   
** Congratulations! You have completed Stage 1! **

# Stage 2: Editing, Committing, and Pushing #
Now that you have your own branch, you can make any edits to files in the repository. Open the file "CONTRIBUTORS.md".
#### TO DO: ####
1. Open the file "CONTRIBUTORS.md"
2. Find your name in the list and add a fun fact about yourself next to it.
3. In order to save your changes you must stage and commit your changes. Run the command: git add . & git commit -m [message], in that order
4. In order for your edit to be saved to the repo, you must push it. Run the command: git push -u origin [feature-yourname] --> the -u flag links your local branch to the remote, so later on you will only have to run git push. 

** Congratulations! You have completed Stage 2! **

# Stage 3: Pulling and Merging #
You have to make sure that you are constantly up-to-date with the current main branch, and that any changes you make can be seen by everyone else on the project. 
#### TO DO: ####
1. In order to get the latest changes, run the command: git pull origin main
2. In order to update the main branch, you must switch into the main branch. Run the command: git checkout main
3. In order to update the main branch with your feature branch, run the command: git merge [feature=yourname]
4. Finally, run the command: git push origin main
5. Check to make sure that you can see the changes by opening the "CONTRIBUTORS.md" file in main.
   
** Congratulations! You have competed Stage 3! **

# Stage 4: Merge Conflicts # 
Now that you have practiced running the basic commands in git, we need to practice resolving merge conflicts.
#### TO DO: ####
1. Open the file "
