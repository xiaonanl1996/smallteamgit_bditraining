# Importing the demo repo using GitHub

1. Go to the demo repository URL: https://gitlab.com/jenniferc-teu/smallteamgit_bditraining
2. Click on the large blue "Clone" button on the right hand side of the project page, and copy the text provided in the "Clone with HTTPS" section

<img src="/Instructions/Images/GitHub/1_GitLabCloneLink.png" alt="Screen shot showing how to get https clone link for the demo repository" width="50%"/>

3. Go GitHub, log into your account, and select the green "New" button at the top left to create a new repository

<img src="/Instructions/Images/GitHub/2_NewRepo.png" alt="Screen shot showing selection of namespace into which to fork project" width="50%"/>

4. GitHub will take you to the new repository creation page; but at the top there's a subtle option to "Import a repository"

<img src="/Instructions/Images/GitHub/3_ImportRepo.png" alt="Screen shot showing selection of namespace into which to fork project" width="50%"/>

5. The import project page will ask for "Your old repository's clone URL". This is the link we copied in Step 2, paste it in here. You can give your new repository any name you like, and choose whether you with it to be public or private (you can change this later).

<img src="/Instructions/Images/GitHub/4_BeginImport.png" alt="Screen shot showing successful completion of fork" width="50%"/>

6. GitHub will take a moment to import the repository. When it's finished you should receive an email notification, and be able to click on the link to go to the webpage of your new repository.

<img src="/Instructions/Images/GitHub/5_ImportFinished.png" alt="Screen shot showing successful completion of fork" width="50%"/>

# Clone a local copy of the repository

1. Click on the dropdown arrow on the big green "Code" button and copy the clone link it gives you. Make sure that "HTTPS" is selected, and the link you're copying starts with "https://" (this should be the default).

<img src="/Instructions/Images/GitHub/6_CloneLink.png" alt="Screen shot showing successful completion of fork" width="50%"/>

2. Open a Git Bash terminal in the directory where you would like to make your local copy of the repo.
3. Enter the command `git clone ` and paste the https link you copied in Step 1. (In MinTTY, the default terminal, the keyboard shortcut to paste is Shift + Insert)

<img src="/Instructions/Images/GitHub/7_CloneCommand.png" alt="Screen shot showing the Git clone command in Git Bash" width="50%"/>

4. At this point Git may prompt you for login details. If it does, then enter the login details for your GitHub account.
5. The repository should now have downloaded into the folder you chose. It will be in a folder with the name of the repo on GitHub, but you can change this if you like.

<img src="/Instructions/Images/GitHub/8_ClonedFolder.png" alt="Screen shot showing the local copy of the repo after successful clone" width="50%"/>

6. If you navigate into this folder in file explorer, you should see all the files and directories that you could see in the repository on GitHub.
7. If you navigate into this folder in Git Bash, it should recognise it as a Git repository. You can use the `git remote -v` command (v stands for "verbose") to see that the remote is configured to your GitHub page for the project.

<img src="/Instructions/Images/GitHub/9_CheckRemote.png" alt="Screen shot showing how to check the remote configured for the repository" width="50%"/>

# You're now ready for the live coding practical session!