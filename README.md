# assigment6-Question-2
to make braanch create a GitHub repository, add code, create a feature branch, make changes to the code, test it, and then merge it into the master branch. Assuming you already have Python code in main.py and math_function.py:
Here are the steps to create a GitHub repository, add code, create a feature branch, make changes to the code, test it, and then merge it into the master branch. Assuming you already have Python code in `main.py` and `math_function.py`:

1. **Create a Local Repository:**

   Open your terminal and navigate to the directory where your code is located.

   ```bash
   cd /path/to/your/codebase
   ```

   Initialize a local Git repository:

   ```bash
   git init
   ```

2. **Add and Commit Files:**

   Add your code files to the repository and make an initial commit:

   ```bash
   git add main.py math_function.py
   git commit -m "Initial commit"
   ```

3. **Push Your Repository to GitHub:**

   Create a new repository on GitHub.

   Now, connect your local repository to the GitHub remote repository:

   ```bash
   git remote add origin https://github.com/Jemiardp/assigment6-Question-2
   ```

   Push your code to GitHub:

   ```bash
   git push -u origin master
   ```

4. **Create a New Feature Branch:**

   Create a new branch for the feature:

   ```bash
   git checkout -b feature/add_mul_div
   ```

5. **Add New Math Functions:**

   Edit `math_function.py` to add the new math functions (multiplication and division). Save the changes.

6. **Test New Functions:**

   Update `main.py` to test the new functions you added in `math_function.py`.

7. **Commit and Push Feature Branch:**

   Commit the changes in the feature branch:

   ```bash
   git add main.py math_function.py
   git commit -m "Add multiplication and division functions"
   ```

   Push the feature branch to your public repo on GitHub:

   ```bash
   git push origin feature/add_mul_div
   ```

8. **Merge Feature Branch into Master:**

   Switch back to the master branch:

   ```bash
   git checkout master
   ```

   Merge the feature branch into the master branch:

   ```bash
   git merge feature/add_mul_div
   ```

   Resolve any merge conflicts if they occur.

9. **Push to Public Repo:**

   Finally, push the changes to your public repository:

   ```bash
   git push origin master
   ```

10. **Submit the Link:**

    After completing these steps, your code changes and commit history will be on your public repository on GitHub. You can provide the link to your public repository to the reviewer.

Your public repository on GitHub will contain the master branch with the commit history, and the feature/add_mul_div branch with the new math functions and their associated commits.
