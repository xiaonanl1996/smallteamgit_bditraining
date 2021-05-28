# Forking the demo repo using GitLab

1. Go to the repository URL: https://gitlab.com/jenniferc-teu/smallteamgit_bditraining
2. Click the "Fork" button

<img src="/Instructions/Images/GitLab/1_Fork.png" alt="Screen shot showing location of fork button in GitLab" width="50%"/>

3. Select the namespace into which to fork the project. You probably only have one option here.

<img src="/Instructions/Images/GitLab/2_Namespace.png" alt="Screen shot showing selection of namespace into which to fork project" width="50%"/>

4. Wait while GitLab processes the fork
5. The page should automatically refresh and show your new project (note your GitLab username is now in the url), with a banner declaring the success of the fork and a link back to the original repository.

<img src="/Instructions/Images/GitLab/3_Success.png" alt="Screen shot showing successful completion of fork" width="50%"/>

To view the official GitLab documentation for forking a repository, click [here](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html#fork)

# Clone a local copy of the repository

1. Click on the large blue "Clone" button on the right hand side of the project page, and copy the text provided in the "Clone with HTTPS" section

<img src="/Instructions/Images/GitLab/4_CloneLink.png" alt="Screen shot showing the https clone link" width="50%"/>

2. Open a Git Bash terminal in the directory where you would like to make your local copy of the repo.
3. Enter the command `git clone ` and paste the https link you copied in Step 1. (In MinTTY, the default terminal, the keyboard shortcut to paste is Shift + Insert)

<img src="/Instructions/Images/GitLab/5_CloneCommand.png" alt="Screen shot showing the Git clone command in Git Bash" width="50%"/>

4. At this point Git may prompt you for login details. If it does, then enter the login details for your GitLab account.
5. The repository should now have downloaded into the folder you chose. It will be in a folder with the name of the repo on GitLab, but you can change this if you like.

<img src="/Instructions/Images/GitLab/6_ClonedFolder.png" alt="Screen shot showing the local copy of the repo after successful clone" width="50%"/>

6. If you navigate into this folder in file explorer, you should see all the files and directories that you could see in the repository on GitLab.
7. If you navigate into this folder in Git Bash, it should recognise it as a Git repository. You can use the `git remote -v` command (v stands for "verbose") to see that the remote is configured to your GitLab page for the project.

<img src="/Instructions/Images/GitLab/7_CheckRemote.png" alt="Screen shot showing how to check the remote configured for the repository" width="50%"/>

To view the official GitLab documentation for cloning a repository, click [here](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html#clone-a-repository)

# You're now ready for the live coding practical session!