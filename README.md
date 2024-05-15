# my_first_repo

git add "your file name (without quotation marks, of course)" --> code is tested etc and added to the staging area

git diff --> shows the changes that could be told to Git (with "add"), but haven't been so far

git diff --cached <commit> --> view the changes staged for the next commit relative to the named <commit>. If you do not give <commit>, it defaults to HEAD.
                                If HEAD does not exist (e.g. unborn branches) and <commit> is not given, it shows all staged changes. --staged is a synonym of --cached.

git status --> has "git add "file"" been successful; meaning, hast something been added to commit? Would be marked in green.

git commit -m "short comment about what have been changed" --> transfer the changes to the local repository

gut push --> upload the changes to the remote repository for to be available to everyone