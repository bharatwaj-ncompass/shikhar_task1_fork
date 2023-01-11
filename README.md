# Scene-1
---
- [x] Cloned the repository.
- [x] Default branch: main.
- [x] Created two more branches: branch1 and branch2.
- [x] Switched branch from main to branch2.
- [x] Created some files in branch2.
- [x] Edited the files.
- [x] Staged the files but not commited them.
- [x] Later stashed the files to shift the changes to branch1 (git stash)
- [x] At last switched to branch1 and popped the stash. (git stash pop)
---

# Scene-2
---
- [x] I made changes to both the text files.
- [x] Then I commited the files.
- [x] Then using *git log* I got the *commit id* and copied it.
- [x] Afterwards I changed my branch to HEAD-->branch1.
- [x] At last I used *git merge* to make the changes in the new branch.

git cherry-pick or rebase can also be used.
---

# Scene-3
---
- [x] I made changes to both the text files.
- [x] Then I commited and pushed the files.
- [x] Then using the *commit id* I reverted the changes. (git revert *id*)
- [x] Afterwards I changed my branch and typed *git reflog*.
- [x] I took the *revert id* and using git cherry-pick *revert id* I made the changes to branch1.
- [x] At last I pushed it to remote repo.
---
