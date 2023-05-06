# github-3.2-wee
assignment 3.2

what is GitHub Authentication and how what methods available to be implemented?

To keep your account secure, you must authenticate before you can access certain resources on GitHub. When you authenticate to GitHub, you supply or confirm credentials that are unique to you to prove that you are exactly who you declare to be.

You can access your resources in GitHub in a variety of ways: in the browser, via GitHub Desktop or another desktop application, with the API, or via the command line. Each way of accessing GitHub supports different modes of authentication.

Username and password with two-factor authentication
Personal access token
SSH key


simple_cloud_project
Git Clone
git clone is used for just downloading exactly what is currently working on the remote server repository and saving it in your machine's folder where that project is placed. (Only one time)

Git Fetch
git fetch just "downloads" the changes from the remote to your local repository.

Git Pull
git pull is a (clone(download) + merge) operation and mostly used when you are working as teamwork. (Can be multiple time if there is new changes on the repo). git pull downloads the changes and merges them into your current branch.

Git Add
git add is used to stage the all the file for commit to your local repository by the following command.

Git Branch
git branch is used to see list of available branch on local repository

Git Remote
To change the remote to SSH
git remote set-url origin git@github.com:bxianlim/simple_cloud_project.git