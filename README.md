Totorial: How to add a github repo and commit/push from VSCode
---

## **Step 1: Prerequisites**
Ensure you have:
- Git installed on your system.
- A GitHub account.
- VSCode installed and configured.

---

## **Step 2: Open Your Project Folder**
1. Open VSCode.
2. Go to **File > Open Folder** and select the folder containing your Python file.

---

## **Step 3: Initialize a Local Git Repository**
1. Open the **Source Control** panel by clicking the icon in the sidebar or pressing `Ctrl+Shift+G`.
2. Click on "Initialize Repository" if prompted. This will create a `.git` folder in your project, which tracks changes.

---

## **Step 4: Configure Git (One-Time Setup)**
If you haven't configured Git before, set your username and email:
1. Open the terminal in VSCode (`Ctrl+``).
2. Run these commands:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

---

## **Step 5: Stage and Commit Your Files**
1. In the Source Control panel, click the "+" icon next to your file to stage it (or click "Stage All Changes").
2. Enter a commit message (e.g., "Initial commit") in the input box at the top of the Source Control panel.
3. Click the checkmark icon (✔) or press `Ctrl+Enter` to commit your changes.

---

## **Step 6: Create a Repository on GitHub**
1. Go to [GitHub](https://github.com) and log in.
2. Click on **New Repository**.
3. Enter a name for your repository, choose public or private, and click **Create Repository**.

---

## **Step 7: Link Your Local Repository to GitHub**
1. Copy the repository URL from GitHub.
2. In VSCode's terminal, run:
   ```bash
   git remote add origin 
   ```
   Replace `` with the URL you copied.
3. Verify the remote link by running:
   ```bash
   git remote -v
   ```

---

## **Step 8: Push Your Code to GitHub**
1. In VSCode's terminal, push your changes:
   ```bash
   git push -u origin main
   ```
   If your branch is named something other than `main`, replace it with your branch name.

---

## **Alternative Method: Use VSCode's GUI**
If you'd rather avoid using the terminal:
1. After initializing the repository, click on the ellipsis (`...`) in the Source Control panel.
2. Select **Push** or **Publish Branch**.
3. If prompted, add a remote repository by pasting your GitHub URL.

---

Once completed, refresh your GitHub repository page to see your files! Repeat Steps 5 and 8 for future changes.

Citations:
[1] https://github.com/sailesh307/GitHubTutorial
[2] https://www.youtube.com/watch?v=0LrNRBI_mYU
[3] https://graphite.dev/guides/how-to-push-code-from-vscode-to-github
[4] https://www.techielass.com/how-to-push-code-from-vs-code-to-github/
[5] https://www.youtube.com/watch?v=4dkNn93DIx4
[6] https://code.visualstudio.com/docs/sourcecontrol/github
[7] https://devops.stackexchange.com/questions/15169/how-can-i-commit-and-push-only-the-files-what-i-need-while-using-vscode
[8] https://www.gitkraken.com/blog/vs-code-git
[9] https://www.reddit.com/r/webdev/comments/1ciyc6j/using_github_and_vs_code/
[10] https://stackoverflow.com/questions/63870642/commiting-changes-to-github-using-vs-code
[11] https://code.visualstudio.com/docs/sourcecontrol/intro-to-git
[12] https://code.visualstudio.com/docs/sourcecontrol/overview
[13] https://stackoverflow.com/questions/46877667/how-to-add-a-new-project-to-github-using-vs-code
[14] https://www.youtube.com/watch?v=z5jZ9lrSpqk
[15] https://stackoverflow.com/questions/46382883/shortcut-to-push-code-to-git-in-vscode
[16] https://www.reddit.com/r/vscode/comments/wuo8an/committing_and_pushing_from_vscode_instead_of/
[17] https://www.youtube.com/watch?v=PdW4_jAlPqw

---
