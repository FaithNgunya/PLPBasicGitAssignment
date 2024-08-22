# PLPBasicGitAssignment


1. **Initialization:**
   - Create a new Git repository:
     ```bash
     git init
     ```

2. **Connecting to GitHub:**
   - Add the remote repository:
     ```bash
     git remote add origin [https://github.com/FaithNgunya/plpbasicgitassignment.git](https://github.com/FaithNgunya/plpbasicgitassignment.git)
     ```

3. **Creating a File:**
   - Create a new text file:
     ```bash
     touch hello.txt
     ```
   - Add content to the file:
     ```
     Hello, Git!
     ```

4. **Staging and Committing Changes:**
   - Stage the changes:
     ```bash
     git add hello.txt
     ```
   - Commit the changes:
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

5. **Pushing to GitHub:**
   - Push the changes to the remote repository:
     ```bash
     git push origin main
     ```
