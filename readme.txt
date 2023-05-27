hello i am writing at 11:56.
git init - create a new empty repo. - create .git folder if want to remove just delete it.
working area - bunch of files not handles by git. -if we check status, it shows untracked files.
staging area - going to part of next version. - knows what changes will be done from last to next version.
repository area - contains details of all prev repository version.
git add <file> - moves file from working to staging area
git rm --cached <file> - moves file from staging to working
commit -  