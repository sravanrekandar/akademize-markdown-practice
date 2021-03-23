# Markdown Practice

## Learning GIT

Git is a version control software

## Learning Git hub

Github is an open place to upload your code

```
srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$ ls
README.md

srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$ git add README.md
warning: CRLF will be replaced by LF in README.md.
The file will have its original line endings in your working directory

srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$ git log
fatal: your current branch 'master' does not have any commits yet

srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$ git commit -m "First commit"
[master (root-commit) dbe5e95] First commit
 1 file changed, 9 insertions(+)
 create mode 100644 README.md

srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$ git log
commit dbe5e952426c4011807b9f15bc605aff64b19b4d (HEAD -> master)
Author: SRAVAN REKANDAR <sravanrekandar@drishya.ai>
Date:   Tue Mar 23 16:35:27 2021 +0530

    First commit

srava@DESKTOP-AI1P9ES MINGW64 ~/akademize/akademize-markdown-practice (master)
$

```