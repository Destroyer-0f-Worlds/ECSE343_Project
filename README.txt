Authors:
-Eric

ECSE 343 Group Project!
Some useful git commands (feel free to modify or add some, I'm not super 
familiar with git)

>git config --list  # You can find your username and email displayed when committing
>git config --global user.name NEW_NAME   # To change your name

>git clone REPO_URL   # Initiate local git REPOSITORYURL

>git branch NEW_BNAME       # Creates a new branch, if left blank, displays current
>git checkout BNAME         # Changes current branch
>git pull origin BNAME      # Fetches changes from the branch and merges it to current branch
>git push -u origin BNAME   # Makes branch public and pushes the changes
>git merge BNAME            # Merges branch changes to current branch