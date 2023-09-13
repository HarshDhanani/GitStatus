# GitStatus: Important Git Commands

This guide provides a list of important Git commands that you might need to use.

## First Round

These commands are typically used when you're setting up your Git repository for the first time.

1. `git init`
   - This command creates an empty Git repository locally.

2. `git remote add origin "REMOTE URL"`
   - This command links your local repository to the remote one.

3. `git status`
   - This command shows the status of your local repository.

4. `git add -A`
   - This command stages all changes for commit. You can check if everything is staged correctly by running `git status` and ensuring everything is green.

Before making your first commit, you need to set up your Git user name and email:

5. `git config --global user.name "YOUR NAME"`
6. `git config --global user.email "YOUR EMAIL"`

7. `git commit -m "YOUR COMMIT MESSAGE/COMMENT"`
   - This command commits your changes with a message.

8. `git push -u origin master`
   - This command pushes all changes from your local repository to the remote one. You'll be prompted to enter your remote username and password.

If you've made some changes on the remote repository and want to sync them with your local one, use this command:

9. `git pull origin master`

## Second Round

These commands are used for regular work with your Git repository:

1. `git status`
   - Check the status of your local repository.

2. `git add`
   - Stage changes for commit.

3. `git commit`
   - Commit your changes.
