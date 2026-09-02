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


5.
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md


6.
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md


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


10.
No, the changes that I made on GihHub are not on my local README.md file


11.
To https://github.com/BenBernard13/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/BenBernard13/git-lab.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


12.
Yes, now the changes that I made on GitHub are in my local README.md file


13.
.               ..              .git            .gitignore      README.md
