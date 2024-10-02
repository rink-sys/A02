# A02

Tutorial for getting started with Git:
- First we need to step up git locally. Download from: https://git-scm.com/downloads 
- To check if we successfully installed git, we run the command 'git --version' on our terminal. If it is successfully installed, it will return the git's version.
- Now, we need to configure our git. Use these commands to do it:  git config --global user.name "Your Name" and git config --global user.email "your.email@example.com".
  Here, we are basically making a new git account with gmail and assigning it a username.
- Now we will create a git project. Through the terminal we can navigate to the location where we want to create the directory. We use the command 'cd' to do it. example: cd /path/to/your/project
- Then we use the command, 'mkdir' to create a directory on the location and give it a name. example: mkdir myproject.
- Now, we initialize the git using the command: 'git init'. This creates a hidden .git folder where Git will store information about your project.
- After this step, our directory is ready and we can perform actions on it through various commands such as:
  git status = To check and see if git is aware about the files running and being modified.
  git add <file-name> = To add files to the final stage where they get added tot he directory.
  git commit -m "Your commit message" = **Commit** all the added files to the directory with a message to keep track of progress. 

Tutorial for getting started with Github:
- First, we need to make an account on **Github**. Use this link: https://github.com/join
- After we are signed in, we make a new **repository**. This can be done from the 'plus' button on the top left of the **github** home screen.
- To finish creating a repository, we just need to name the **repository** and choose the visibility. Other fields are optional to fill.
- Since we have already set up a local Git repo, we are going to **push** that to **GitHub**. We can do this by adding the **remote** URL of the **github repository** (basically the link to our **github repository**)
  Use this command: git remote add origin <"remote URL of your **repository**">
- Now, we **push** the code from our local repository to **github**. We use the code: git push -u origin master
  This uploads the code to the master **branch** of the **github**.
- After our code is uploaded on **github**, we can use plethora of commands to interact and modify it.
  git checkout -b feature-branch = allows you to make **branches** of the main code.
  git checkout master = To switch back to the main **branch**
  git merge feature-**branch** =  to **merge** changes to the master **branch**
  git pull origin master = **pulls** updates from the main code and update your local repository.
  git push origin = To **push** the changes to the**github**

Tutorial for getting started with Visual Studio Code:
- First we need to download Visual Studio Code setup from the link: https://code.visualstudio.com/download. Choose whichever platform you are working on.
- Then we run the setup to install Visual Studio Code in your system.
- After installing VS code, we install extensions that are suitable for what language we are developing in. We also make sure that we have a git extension installed. So we can integrate git in our VS code.
- n VS Code, open File > Preferences > Settings, and search for "Git: User Name" and "Git: Email". Enter your username and email here. These will be tied to your **commits**, making it easier for collaborators to see who made which changes
- In VS Code, open the folder containing your project by navigating to File > Open Folder.
- On the Source Control panel (left sidebar), you’ll see a button that says Initialize **Repository**. Click this to set up a Git **repository** in your project. Now, your project is tracked by Git, and any changes you make will be reflected in the Source Control panel.
- Once you modify a file in your project, you’ll notice a small "M" (for modified) or "U" (for untracked) next to the file in the Explorer panel.
- To stage a file (prepare it for a **commit**), hover over the file in the Source Control panel and click the + icon (Stage Changes). Staged files will move to the Staged Changes section above.
- At the top of the Source Control panel, you’ll see a text box. Enter your **commit** message here. Click the checkmark icon to **commit** your changes.

Glossary:
- **Branch** = A line of development in **GIT** that allows for parallel work on different features or fixes. 
- **Clone** = The process of creating a local copy of a **repository** from a **remote** location.
- **Commit** = As a noun: A single point in the **Git** history; the entire history of a project is represented as a set of interrelated **commits**.
            As a verb: The action of storing a new snapshot of the project’s state in the **Git** history, by creating a new **commit**.
- **Fetch** = The command that retrieves updates from a **remote repository** without **merging** them into the local **repository**.
- **GIT** = A distributed version control system used to track changes in source code during software development.
- **Github** = A web-based platform for hosting **GIT repositories**, facilitating collaborative software development.
- **Merge** = The process of combining changes from one **branch** into another, typically the main line of development.
- **Merge Conflict** = A situation that arises when changes from different **branches** conflict during a **merge** and require manual resolution
- **Push** = The command to upload local **commits** to a **remote repository** on **GitHub**.
- **Pull** = The command that **fetches** and **merges** changes from a **remote repository** into the local **repository**.
- **Remote** = A version of a **repository** that is hosted on a server, enabling collaborative access and contribution.
- **Repository** = A storage space for project files and their version history, either local or hosted on a service like **GitHub**.

References:
- https://git-scm.com/docs/git
- https://www.w3schools.com/git/
- https://www.w3schools.com/git/git_remote_getstarted.asp?remote=github
- https://www.atlassian.com/git/tutorials
- https://git-scm.com/
- Lecture Notes
