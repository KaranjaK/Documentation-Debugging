# GitHUb Quick fix
## Disconnecting from a remote repo
    git remote remove origin <the remote repo url>

## Undoing/Deleting a Commit pushed to Remote repo
1. Check the commits made using the command:
    git log --oneline
2. Delete the previous made commit using the command:
    git reset --soft HEAD~1 
    N.B.: This will delete the most recent commit made
