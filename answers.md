Answer 1

git version 2.26.2.windows.1
Answer 2

diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
credential.helper=manager
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.email=bw310219@ohio.edu
user.name=Branden Webb
core.editor="D:\Sublime Text 3\sublime_text.exe" -w

Answer 3
When you type git --help it displays a list of commands that you can use and briefly describes them.

Answer 4
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5
On Branch Master

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 6
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 8 
commit 768f2c5cb3cd16a6d5fd8258491c2bff898e358a (HEAD -> master)
Author: Branden Webb <bw310219@ohio.edu>
Date:   Wed Aug 26 21:04:33 2020 -0400

    Initial commit

Answer 9
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 10
The local copy does not reflect what I have done on github.com, it does not show up.

Answer 11
To https://github.com/bw310219/git-lab.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/bw310219/git-lab.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
//does not work.

Answer 12
the README.md was updated in the local directory to reflect the changes that I made online.

Answer 13
.  ..  .git  .gitignore  README.md
