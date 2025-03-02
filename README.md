# Learn Git - Step-by-Step Guide 🚀

This repository showcases a detailed, step-by-step process of learning Git with screenshots at each stage. Below, you'll find 20 steps showing how to set up, commit, configure, and push to GitHub with proper explanations.

---

## 00. [GitHub New Repository Page] 📄
![S00](screens/S00.png)

This is the page where you start by creating a new repository on GitHub. Fill out the repository name, description, and other settings.

---

## 0. [GitHub Page For Defined Repository Information] 🔍
![S0](screens/S0.png)

After creating the repository, you'll be directed to a page with information about the defined repository, including its name and description.

---

## 1. [Create a folder called learn_git.] 🔍
![S1](screens/S1.png)

This step shows the GitHub page after your repository has been defined. You'll see basic information about your repository, like its name and description.

---

## 2. [Cd (change directory) into the learn_git folder.] 💻
![S2](screens/S2.png)

Clone your newly created GitHub repository to your local machine using the `git clone` command. This allows you to work on your files locally.

---

## 3. [Create a file called third.txt.] 🧭
![S3](screens/S3.png)

After cloning, navigate into the project folder. This step shows how to move into your project directory using `cd <repo_name>`.

---

## 4. [Initialize an empty git repository] ✍️
![S4](screens/S4.png)

Here, we create a new file called `third.txt` in the local repository using the `touch` command.

---

## 5. [Add `third.txt` to Staging Area] 📥
![S5](screens/S5.png)

The `git add` command stages the file `third.txt` to be tracked by Git. This prepares it for commit.

---

## 6. [Commit Changes with Message] 💬
![S6](screens/S6.png)

Commit your staged changes with a custom message, like `"adding third.txt"`, to keep track of changes in your repository.

---

## 7. [Check Git Log] 📜
![S7](screens/S7.png)

Use `git log` to view the commit history of your repository. This shows the changes made, along with commit messages.

---

## 8. [Create a New File - `fourth.txt`] ✍️
![S8](screens/S8.png)

Create another file named `fourth.txt` in your local repository.

---

## 9. [Add `fourth.txt` to Staging Area] 📥
![S9](screens/S9.png)

Stage the `fourth.txt` file for commit by adding it to Git’s staging area with the `git add` command.

---

## 10. [Commit `fourth.txt` with a Custom Message] 💬
![S10](screens/S10.png)

Commit the new file `fourth.txt` with the message `"adding fourth.txt"` to track changes.

---

## 11. [Remove a File - `third.txt`] 🗑️
![S11](screens/S11.png)

In this step, we remove the previously added file `third.txt` using the `git rm` command.

---

## 12. [Add Removal of `third.txt` to Staging Area] 📥
![S12](screens/S12.png)

After removing the file, stage this change using `git add .` to include the removal in the next commit.

---

## 13. [Commit File Removal with Message] 📝
![S13](screens/S13.png)

Commit the removal of `third.txt` with a message like `"removing third.txt"` to log the deletion.

---

## 14. [Check Commits using git log] 🔍
![S14](screens/S14.png)

Here, we modify the global Git configuration to set `core.pager=cat`, which allows you to view logs without pagination.

---

## 15. [Change Git Configuration - `core.pager=cat`] ⚙️
![S14](screens/S15.png)

Here, we modify the global Git configuration to set `core.pager=cat`, which allows you to view logs without pagination.

---

## 16. [Check Current Git Configuration] 🔧
![S15](screens/S16.png)

Use the `git config --global --list` command to check the global configuration settings applied to your Git installation.

---

## 17. [Add Remote Repository] 🌍
![S16](screens/S17.png)

Add a remote repository (like GitHub) with the `git remote add origin` command to link your local repository to a remote one.

---

## 18. [Branch  Remote] 🚀
![S17](screens/S18.png)

Branch remote repository on GitHub using `git branch -M main`.

---


## 19. [Push Changes to Remote Repository] 🚀
![S17](screens/S19.png)

Push your local commits to the remote repository on GitHub using `git push -u origin main`.

---

## 20. [Final Result ] 🔀
![S20](screens/S20.png)

Finally, available on [https://github.com/daniel10027/learn_git.git]

---

## Conclusion 🎉

By following these 20 steps, you've learned how to initialize a repository, commit files, remove files, push changes to GitHub, and use basic Git commands like `git log`, `git add`, and `git commit`. Keep practicing, and soon you'll be a Git pro! 👨‍💻👩‍💻

Happy coding! 😊
