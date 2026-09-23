# A02

# A tutorial on how to use WebStorm with Git and GitHub

## 1. Downloading Git
1. Go to [Git's official website](https://git-scm.com/install/)
2. Download the version for your operating system
3. Run the installation after the download is complete

## 2. Downloading WebStorm
1. Go to [JetBrains' website for WebStorm](https://www.jetbrains.com/webstorm/)
2. Download the version for your operating system
3. Run the installer after the download is complete

## 3. Getting GitHub
1. Make an account on [**GitHub**](https://github.com/)
2. Sign in

## 4. Using WebStorm
1. Open WebStorm
2. Select New Project
3. Choose the type of project you want to make
4. Name the project
5. Choose the location for the project
6. Connect the project to **Git**

## 5. Create a **GitHub** **repository**
1. Sign in to **GitHub**
2. Click the + button
3. Select New **repository**
4. Enter a name for the **repository** and adjust settings as needed
5. Create the **repository**

## 6. Clone a **repository** from GitHub
1. Go to the **GitHub** **repository** you want to **clone**
2. Select the Code button
3. Copy the **repository** URL
4. Open WebStorm
5. Paste the **repository** URL into the URL box
6. Choose the project location
7. Select Clone

After you **clone** your **repository** into WebStorm, you can make changes to the files there. Cloning creates a local copy of a **repository** from GitHub on your computer. This allows changes to be pulled from and pushed to the **remote repository**.

## 7. Connect the WebStorm project to **GitHub**
You can connect the local project to **GitHub** in WebStorm by adding it to the **remote** **repository** through Git version control tools. You can also use the terminal and run the command **git remote** add origin https://github.com/(user)/(repo).git where (user) is your **GitHub** username and (repo) is your **repository** name.

## 8. Adding files to Git
1. Go to WebStorm and open your project
2. Create or edit a file
3. Click **Commit** tool
4. Any files that are not tracked can be added to **Git**

You can also use the terminal and run the command **git** add . where it adds changes to the current project

## 9. Create a **commit**
In the Commit tool, once you are done adding and reviewing your changes, select the files you want to include to **commit**, enter a **commit** message, and select Commit. Your **commit** message should briefly explain what was changed. You can also run the terminal command: **git commit** -m "Your message here"

## 10. Creating a branch
1. Go on WebStorm and find the current **branch** name
2. Select the **branch** name
3. Select New Branch.
4. Give the **branch** a name.
5. Select the option to switch to the new **branch**.

Branches are good to have when working on something new because changes can be made without immediately changing the main **branch**. You can use the terminal command: **git** checkout -b (**branch**) where **branch** is your **branch** name.

## 11. Making changes to your project
1. After creating a **branch**, open the project files in WebStorm.
2. Make the required changes and save the files.
3. For example, if the project contains a README.md file, information about **Git**, WebStorm, and **GitHub** can be added to the file.
4. After making changes, check the **Commit** window in WebStorm. The changed files should appear there.

## 12. Push changes to GitHub
Commits are done locally so you must **push** them so they can appear in **GitHub**'s **remote** **repository**. Push your project in WebStorm. You can also do this with the terminal command: **git push** origin (**branch**) where **branch** is your **branch** name.

## 13. Pull changes from GitHub
Sometimes there will be changes done on **GitHub** or by someone else so your local project may be up to date. Pull your project in WebStorm. You can also do this with the terminal command: **git pull** origin (**branch**) where **branch** is your **branch** name.

The **pull** will get any changes from the **remote** **repository** and combine it with the local **branch**.

## 14. Fetch changes
Use the terminal command: **git fetch** origin. You can use this to see what changed on **GitHub** before merging these changes into the local project. You can also use Git's update tools in WebStorm to **fetch** changes.

## 15. Merge changes
There are two terminal commands to use in sequence. **git** checkout (**branch**1) and then **git merge** (**branch**2). **branch**1 is the **branch** you want to **merge** your changes to from **branch**2.

A **merge** combines changes from one **branch** with another **branch**. WebStorm also provides tools for merging **branch**es.

## 16. Resolving a **merge conflict**

Sometimes a **merge conflict** happens when Git cannot automatically combine two changes. When this happens, WebStorm will identify the file with the conflict. From there, you must:
1. Decide which changes should remain
2. Remove the unneeded changes that caused the conflict
3. Save the file
4. Add the file to **Git**
5. Create a **commit**

# Glossary of terms
**Branch** - A separate version of a project where you can make changes

**Clone** - Making a copy of a GitHub repository onto your local computer

**Commit** - Saving changes to your Git project

**Fetch** - Getting new changes from GitHub without adding them to the current local project

**Git** - A tool that tracks changes to files and projects

**GitHub** - A website used to store and share Git projects remotely

**Merge** - Combining changes from two branches

**Merge Conflict** - A problem that happens when Git finds different changes in the same part of a file

**Push** - Sending your changes from your local computer onto GitHub

**Pull** - Getting the latest changes from GitHub

**Remote** - Online version of a Git repository

**Repository** - A project folder that contains files and its change history

# References
https://docs.github.com/en/get-started/using-git/about-git

https://docs.github.com/en/get-started/git-basics/set-up-git

https://docs.github.com/en/get-started/git-basics/about-remote-repositories

https://docs.github.com/en/get-started/git-basics/managing-remote-repositories

https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository

https://docs.github.com/en/get-started/using-git/getting-changes-from-a-remote-repository

https://www.jetbrains.com/help/webstorm/meet-webstorm.html
