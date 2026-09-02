1.
git version 2.50.1 (Apple Git-155)


2.
credential.helper=osxkeychain
init.defaultbranch=main
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
user.name=Benjamin Bernard
user.email=bb702625@ohio.edu
core.editor=code --wait
credential.helper=cache


3.
It shows a mini explanation of the most common cammands used in git. It doesn't show all of them, but it shows a lot of them and explains how to get more help with them. It also has a list of flags that you can use.


4.
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)


This has all of the files that haven't been added to the staging section of git. So all the files that aren't being 'tracked'.


5.
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md


Now, it has README.md as a file that is being tracked, but it hasn't been commited while answers.md is still untracked.


6.
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md


Now both files are being tracked and are on the staging section of git, but they haven't been commited yet.


7.
On branch main
nothing to commit, working tree clean


8.
commit 6b2f5638f39021e14748fb22797b82478164225c (HEAD -> main)
Author: Benjamin Bernard <bb702625@ohio.edu>
Date:   Wed Sep 2 16:45:40 2026 -0400

    Initial commit


9.
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean


Now all of the files that I have been working on on my computer, are on GitHub online in the repository that I just made.


10.
No, the changes that I made on GihHub are not on my local README.md file


Because I haven't refreshed my local directory and made sure that my local directory is up to date with the online repository in GitHub.


11.
To https://github.com/BenBernard13/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/BenBernard13/git-lab.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


Git push didn't work because it noticed that my local direcotries were not up to date with my GitHub repository, so it didn't want to overwirte a new version with my old version.


12.
Yes, now the changes that I made on GitHub are in my local README.md file


13.
.               ..              .git            .gitignore      README.md
