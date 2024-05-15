# my_first_repo

git add "your file name (without quotation marks, of course)" --> code is tested etc and added to the staging area

git diff --> shows the changes that could be told to Git (with "add"), but haven't been so far

git diff --cached <commit> --> view the changes staged for the next commit relative to the named <commit>. If you do not give <commit>, it defaults to HEAD.
                                If HEAD does not exist (e.g. unborn branches) and <commit> is not given, it shows all staged changes. --staged is a synonym of --cached.

git status --> has "git add "file"" been successful; meaning, hast something been added to commit? Would be marked in green.

git commit -m "short comment about what have been changed" --> transfer the changes to the local repository

git log --> show all the commits made and which commit is the active one on the remote repository and which one is 
            is still in the local repository

git log --pretty=oneline --> same as "git log", but much better to read, because every commit is on 1 line

git push --> upload the changes to the remote repository on GitHub