# demo
for Demo purposes 

## Procedure
1. I created a repo from github.
2. Copied the link and created a new folder and then cloned my online repo using command `git clone <link to the online repo> . `. With the dot at the end it clones the repository to the current folder.
3. Went ahead and opened the folder in VScode which is my code editor and this is where i am currently.
4. For me to push code I need to make some changes and this changes include what I am typing in this file. So assuming you have made changes or wrote code now you want to commit to your online repo.
5. I will open my vscode Terminal and type the command `git status`.This command will show me the changes i have made in the various files.
`pwd` - prints the current directory/folder we are in.
6. Now I need to stage these changes i have made so I will type the command `git add .` or `git add *`.
7. After staging I will commit by the command `git commit -m "the commit message"` for my case the commit message is `update of readme since i have made changes to readme file`.So my final command will be. `git commit -m "Update Readme file"`
8. I need to push. So I will type the command `git push origin <branch name>`. To check my current branch I type the command `git branch`
9. Now my final command will be `git push origin master`
10. To check , I will go the repo I created in Git and see the changes.Some changes might not reflect since I need to do a final push for the changes made after step 9
