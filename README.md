# Github_Large_Files
- This a repository in which you can learn how to upload large files (>100Mb) into your Github. \
  
- IMPORTANT: ¡You must have previously established your Github ssh key! To do it... visit this link: https://docs.github.com/en/github-ae@latest/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent \
  
 - The text strings in quotes are the ones you have to modify with your personal information.

1. You have to access to your target folder (in which you have your previously cloned Repository)
   
3. Initialize a new Git repository in this previously mentioned directory
   > git init
   
4. Add a remote repository named "origin" to your local Git repository:
   > git remote add origin git@github.com:Enriquedlrm16/Shiny-app.git
   
5. Set or update the URL of a remote repository named "origin" in your Git configuration
   > git config remote.origin.url git@github.com:Enriquedlrm16/Shiny-app.git
   
6. Set or update the global email address associated with your Git user
   > git config --global user.email enriquedlrm98@usal.es

7. Set or update the global username associated with your Git user
   > git config --global user.name Enriquedlrm16

8. Fetch changes from a remote repository and integrate them into your local branch
   > git pull origin main --set-upstream

9. Tell Git Large File Storage (LFS) which files in your Git repository should be managed as large files
   > git lfs track "sc1gexpr.h5"

10. Stage changes for a commit in your Git repository
    > git add sc1gexpr.h5

11. Create a new commit in your Git repository, capturing the changes you have previously staged using the git add command
    > git commit -m "sc1gexpr.h5"

12. Push changes from your local Git repository to the remote repository
    > git push origin master

