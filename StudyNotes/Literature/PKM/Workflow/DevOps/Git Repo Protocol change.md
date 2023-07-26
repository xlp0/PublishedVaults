How to change GIT protocol from HTTP to GIT on Github

To change the protocol from HTTP to GIT on GitHub, follow these steps:

1. Open your terminal or command prompt.

2. Navigate to the local repository directory where you have cloned the GitHub repository.

3. Verify the current remote URL by running the following command:
   ```
   git remote -v
   ```

4. If you see URLs starting with `https://`, it means you are using the HTTP protocol.

5. To change it to GIT, remove the existing remote URL using the following command:
   ```
   git remote remove origin
   ```

6. Now, add a new remote URL with the GIT protocol using the following command:
   ```
   git remote add origin git@github.com:<username>/<repository>.git
   ```
   Replace `<username>` and `<repository>` with your GitHub username and repository name respectively.

7. Verify that the new remote URL has been added successfully by running:
   ```
   git remote -v
   ```

8. You should now see URLs starting with `git@github.com:` indicating that you are using the GIT protocol.

9. Finally, push any local changes to the updated remote repository using:
   ```
   git push origin <branch-name>
   ```
   Replace `<branch-name>` with the name of the branch you want to push.

By following these steps, you have successfully changed the Git protocol from HTTP to GIT for your GitHub repository.