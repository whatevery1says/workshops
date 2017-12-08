# Resolving a Merge Conflict

Use the procedure below to create a merge conflict.

1. Go to the GitHub repo website and edit the file online (click the pencil icon). Change the phrase "It was modified locally" at the bottom of this document to "It was modified online".
1. Add a commit message at the bottom of the screen and click the "Commit changes" button. Your commit will be pushed to the repo automatically by the GitHub website.
1. In VS Code open the file **without pulling from the repo** first. Change "online" back to "locally" and save the file.
1. Go to the GitHub Desktop Client and try to pull the code. You should get an error that says there is a conflict.

To resolve the conflict follow the procedure below:

1. When you get the error message, VS Code will probably open the file automatically. If it doesn't, use VS Code to open the file.
1. VS Code will give you various options for resolving the conflict between the `HEAD` of the repository and the conflict. You can choose one of these or manually edit out the code you don't want and the markers injected by `git`.
1. Save the file, re-commit it, and push the file again.

***

It was modified locally.
