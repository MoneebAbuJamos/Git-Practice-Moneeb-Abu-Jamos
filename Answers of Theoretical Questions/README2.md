
# Git and GitHub Task Answers
## 2. Explain the difference between `git pull` and `git fetch`.
 ## git fetch ##

Contacts the remote (GitHub) and downloads new commits, branches, and tags.

It does not change my current branch or working directory.

I use this when I want to review changes before merging.

## git pull ##

It runs git fetch + git merge (by default).

It brings in changes from the remote and merges them into your current branch.

Use when you're ready to update your branch with the latest remote changes.