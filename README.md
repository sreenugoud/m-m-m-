# m-m-m-

palla.goud@WKSCHE03TRNG016 MINGW64 ~
$ cd c:

palla.goud@WKSCHE03TRNG016 MINGW64 /c
$ cd C:\Users\palla.goud\Gitbash\mphrepo
bash: cd: C:Userspalla.goudGitbashmphrepo: No such file or directory

palla.goud@WKSCHE03TRNG016 MINGW64 /c
$ cd Users/pa
palla.goud/        panjagalla.sushma/

palla.goud@WKSCHE03TRNG016 MINGW64 /c
$ cd Users/palla.goud/Gitbash/

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .
error: 'mphrepo/' does not have a commit checked out
fatal: adding files failed

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ cd mphrepo/

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ ls
first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "first commit"
[main (root-commit) 874a039] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ cd ..

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        mphrepo/

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .
warning: adding embedded git repository: mphrepo
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> mphrepo
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached mphrepo
hint:
hint: See "git help submodule" for more information.
hint: Disable this message with "git config advice.addEmbeddedRepo false"

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   mphrepo


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "mphrepo"
[master 79b4964] mphrepo
 1 file changed, 1 insertion(+)
 create mode 160000 mphrepo

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git config -global code editor
error: did you mean `--global` (with two dashes)?

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git config -global core.editor code
error: did you mean `--global` (with two dashes)?

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git config --global core.editor code

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ code

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "modified.txt"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "Modified"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add first.txt
fatal: pathspec 'first.txt' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "Modified text"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add first.txt
fatal: pathspec 'first.txt' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "Modified text"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add first.txt
fatal: pathspec 'first.txt' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "modified.txt"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ cd mphrepo/

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   first.txt.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   first.txt.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modified"
[main 9f80370] modified
 1 file changed, 1 insertion(+)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        third.txt

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add third
fatal: pathspec 'third' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add third.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   third.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   third.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m"modified"
[main f4fdc1c] modified
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    third.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        four.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add four
fatal: pathspec 'four' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add four.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m"modified"
[main 258a34e] modified
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 four.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    third.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    four.txt
        deleted:    third.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        five.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    four.txt -> five.txt
        deleted:    third.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modified"
[main abf8971] modified
 2 files changed, 0 insertions(+), 0 deletions(-)
 rename four.txt => five.txt (100%)
 delete mode 100644 third.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    first.txt.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    first.txt.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modified"
[main 4fddc62] modified
 1 file changed, 1 deletion(-)
 delete mode 100644 first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)


------------------------------------

palla.goud@WKSCHE03TRNG016 MINGW64 ~
$ cd c:

palla.goud@WKSCHE03TRNG016 MINGW64 /c
$ cd C:\Users\palla.goud\Gitbash\mphrepo
bash: cd: C:Userspalla.goudGitbashmphrepo: No such file or directory

palla.goud@WKSCHE03TRNG016 MINGW64 /c
$ cd Users/pa
palla.goud/        panjagalla.sushma/

palla.goud@WKSCHE03TRNG016 MINGW64 /c
$ cd Users/palla.goud/Gitbash/

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .
error: 'mphrepo/' does not have a commit checked out
fatal: adding files failed

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ cd mphrepo/

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ ls
first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "first commit"
[main (root-commit) 874a039] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ cd ..

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        mphrepo/

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .
warning: adding embedded git repository: mphrepo
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> mphrepo
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached mphrepo
hint:
hint: See "git help submodule" for more information.
hint: Disable this message with "git config advice.addEmbeddedRepo false"

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   mphrepo


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "mphrepo"
[master 79b4964] mphrepo
 1 file changed, 1 insertion(+)
 create mode 160000 mphrepo

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git config -global code editor
error: did you mean `--global` (with two dashes)?

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git config -global core.editor code
error: did you mean `--global` (with two dashes)?

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git config --global core.editor code

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ code

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "modified.txt"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "Modified"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add first.txt
fatal: pathspec 'first.txt' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "Modified text"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add first.txt
fatal: pathspec 'first.txt' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "Modified text"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git add first.txt
fatal: pathspec 'first.txt' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git commit -m "modified.txt"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   mphrepo (modified content)

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash (master)
$ cd mphrepo/

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   first.txt.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   first.txt.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modified"
[main 9f80370] modified
 1 file changed, 1 insertion(+)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        third.txt

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add third
fatal: pathspec 'third' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add third.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   third.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   third.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m"modified"
[main f4fdc1c] modified
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    third.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        four.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add four
fatal: pathspec 'four' did not match any files

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add four.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m"modified"
[main 258a34e] modified
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 four.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    third.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    four.txt
        deleted:    third.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        five.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    four.txt -> five.txt
        deleted:    third.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modified"
[main abf8971] modified
 2 files changed, 0 insertions(+), 0 deletions(-)
 rename four.txt => five.txt (100%)
 delete mode 100644 third.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    first.txt.txt

no changes added to commit (use "git add" and/or "git commit -a")

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    first.txt.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modified"
[main 4fddc62] modified
 1 file changed, 1 deletion(-)
 delete mode 100644 first.txt.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        six.txt

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   six.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m"mod"
[main a6f75ec] mod
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 six.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ rm six.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    six.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    six.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "noi"
[main daad05e] noi
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 six.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        java.txt

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git mv java.txt java2.txt
fatal: not under version control, source=java.txt, destination=java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        java.txt

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "name Change"
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        java.txt

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   java.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modified"
[main d16aa12] modified
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 java.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git mv java.txt java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    java.txt -> java2.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "java to java2"
[main fa0af26] java to java2
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename java.txt => java2.txt (100%)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 887 bytes | 10.00 KiB/s, done.
From https://github.com/sreenugoud/mphrepo
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

commit a6f75ec0a712ff4945108216f526ef29a865949f
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:59:12 2024 +0530

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:54:04 2024 +0530

    modified
:...skipping...
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

commit a6f75ec0a712ff4945108216f526ef29a865949f
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:59:12 2024 +0530

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:54:04 2024 +0530

    modified

commit abf8971d85f582e85127c37073d2bb71a0a8cc23
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:50:29 2024 +0530

    modified

commit 258a34e488485f18115f05ad4d65efcd9c196d9e
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:48:18 2024 +0530

    modified

commit f4fdc1c288c3479acff1c6ba902285130aac8ed7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:47:08 2024 +0530
:
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

commit a6f75ec0a712ff4945108216f526ef29a865949f
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:59:12 2024 +0530

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:54:04 2024 +0530

    modified

commit abf8971d85f582e85127c37073d2bb71a0a8cc23
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:50:29 2024 +0530

    modified

commit 258a34e488485f18115f05ad4d65efcd9c196d9e
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:48:18 2024 +0530

    modified

commit f4fdc1c288c3479acff1c6ba902285130aac8ed7
:
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

commit a6f75ec0a712ff4945108216f526ef29a865949f
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:59:12 2024 +0530

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:54:04 2024 +0530

    modified

commit abf8971d85f582e85127c37073d2bb71a0a8cc23
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:50:29 2024 +0530

    modified

commit 258a34e488485f18115f05ad4d65efcd9c196d9e
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:48:18 2024 +0530
:
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

commit a6f75ec0a712ff4945108216f526ef29a865949f
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:59:12 2024 +0530

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:54:04 2024 +0530

    modified

commit abf8971d85f582e85127c37073d2bb71a0a8cc23
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:50:29 2024 +0530

    modified

commit 258a34e488485f18115f05ad4d65efcd9c196d9e
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:48:18 2024 +0530

    modified

commit f4fdc1c288c3479acff1c6ba902285130aac8ed7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:47:08 2024 +0530

    modified

commit 9f80370ba8c56b7b27faa6a0ccd3198cfb30518c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:44:32 2024 +0530

    modified

commit 874a0393507bb2678939b334d570d5c4e0fef1e7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 11:51:15 2024 +0530

    first commit
(END)

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:54:04 2024 +0530

    modified

commit abf8971d85f582e85127c37073d2bb71a0a8cc23
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:50:29 2024 +0530

    modified

commit 258a34e488485f18115f05ad4d65efcd9c196d9e
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:48:18 2024 +0530

    modified

commit f4fdc1c288c3479acff1c6ba902285130aac8ed7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:47:08 2024 +0530

    modified

commit 9f80370ba8c56b7b27faa6a0ccd3198cfb30518c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:44:32 2024 +0530
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

commit a6f75ec0a712ff4945108216f526ef29a865949f
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:59:12 2024 +0530

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
:
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

commit a6f75ec0a712ff4945108216f526ef29a865949f
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:59:12 2024 +0530

    mod

commit 4fddc62df150229cbb12b1199775026f201b7dd2
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:54:04 2024 +0530

    modified

commit abf8971d85f582e85127c37073d2bb71a0a8cc23
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:50:29 2024 +0530

    modified

commit 258a34e488485f18115f05ad4d65efcd9c196d9e
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:48:18 2024 +0530

    modified

commit f4fdc1c288c3479acff1c6ba902285130aac8ed7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:47:08 2024 +0530

    modified

commit 9f80370ba8c56b7b27faa6a0ccd3198cfb30518c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:44:32 2024 +0530

    modified

commit 874a0393507bb2678939b334d570d5c4e0fef1e7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 11:51:15 2024 +0530

    first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ log --oneline
bash: log: command not found

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --oneline
fa0af26 (HEAD -> main) java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log -p
commit fa0af260b1617e4878f146c3dd58b5a5417c3d72 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

diff --git a/java.txt b/java2.txt
similarity index 100%
rename from java.txt
rename to java2.txt

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

diff --git a/java.txt b/java.txt
new file mode 100644
index 0000000..e69de29

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git pull --allow-unrelated-histories
Merge made by the 'ort' strategy.
 README.md | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 README.md

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 11 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --author=sreenugoud619@gmail.com
commit 688c73cd1eaad6b113f22a7f006bd7ca92529b26 (HEAD -> main)
Merge: fa0af26 c7bcd6a
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:48:02 2024 +0530

    Merge branch 'main' of https://github.com/sreenugoud/mphrepo

commit fa0af260b1617e4878f146c3dd58b5a5417c3d72
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:13:45 2024 +0530

    java to java2

commit d16aa1243b4d288a72841d259387757a8ff512bd
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:07:56 2024 +0530

    modified

commit daad05e5b8e3859652d64197b679af686626ce0c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 14:00:41 2024 +0530

    noi

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --reverse
commit 874a0393507bb2678939b334d570d5c4e0fef1e7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 11:51:15 2024 +0530

    first commit

commit 9f80370ba8c56b7b27faa6a0ccd3198cfb30518c
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:44:32 2024 +0530

    modified

commit f4fdc1c288c3479acff1c6ba902285130aac8ed7
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:47:08 2024 +0530

    modified

commit 258a34e488485f18115f05ad4d65efcd9c196d9e
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 13:48:18 2024 +0530

    modified


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --pretty='format:%C(auto)%h (%s,%ad)'
688c73c (Merge branch 'main' of https://github.com/sreenugoud/mphrepo,Mon Aug 5 14:48:02 2024 +0530)
c7bcd6a (Create README.md,Mon Aug 5 14:24:59 2024 +0530)
fa0af26 (java to java2,Mon Aug 5 14:13:45 2024 +0530)
d16aa12 (modified,Mon Aug 5 14:07:56 2024 +0530)
daad05e (noi,Mon Aug 5 14:00:41 2024 +0530)
a6f75ec (mod,Mon Aug 5 13:59:12 2024 +0530)
4fddc62 (modified,Mon Aug 5 13:54:04 2024 +0530)
abf8971 (modified,Mon Aug 5 13:50:29 2024 +0530)
258a34e (modified,Mon Aug 5 13:48:18 2024 +0530)
f4fdc1c (modified,Mon Aug 5 13:47:08 2024 +0530)
9f80370 (modified,Mon Aug 5 13:44:32 2024 +0530)
874a039 (first commit,Mon Aug 5 11:51:15 2024 +0530)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git branch psg

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git branch sreenu

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git branch -l
* main
  psg
  sreenu

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git checkout psg
Switched to branch 'psg'

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git branch -l
  main
* psg
  sreenu

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ ls
'New folder'/   README.md   five.txt   java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git ls -files
git: 'ls' is not a git command. See 'git --help'.

The most similar command is
        lfs

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ ls
'New folder'/   README.md   five.txt   java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ echo from deepbranch >f1.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git ls-files
README.md
five.txt
java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ ls
'New folder'/   README.md   f1.txt   five.txt   java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git status
On branch psg
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        f1.txt

nothing added to commit but untracked files present (use "git add" to track)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git add f1.txt
warning: in the working copy of 'f1.txt', LF will be replaced by CRLF the next time Git touches it

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git commit m -"modified"
error: pathspec 'm' did not match any file(s) known to git

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git commit -m "modiied"
[psg fc39016] modiied
 1 file changed, 1 insertion(+)
 create mode 100644 f1.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git status
On branch psg
nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git ls-files
README.md
f1.txt
five.txt
java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git checkout sreenu
Switched to branch 'sreenu'

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git ls-files
README.md
five.txt
java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git checkout psg
Switched to branch 'psg'

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git checkout sreenu
Switched to branch 'sreenu'

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$  echo from deepbranch2 >f2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ ls
'New folder'/   README.md   f2.txt   five.txt   java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git ls-files
README.md
five.txt
java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git add f2.txt
warning: in the working copy of 'f2.txt', LF will be replaced by CRLF the next time Git touches it

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git status
On branch sreenu
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   f2.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git commit -m "modified"
[sreenu 5ee08e8] modified
 1 file changed, 1 insertion(+)
 create mode 100644 f2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git status
On branch sreenu
nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 11 commits.
  (use "git push" to publish your local commits)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git ls-files
README.md
five.txt
java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git merge psg
Updating 688c73c..fc39016
Fast-forward
 f1.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 f1.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git ls-files
README.md
f1.txt
five.txt
java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git merge sreenu
Merge made by the 'ort' strategy.
 f2.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 f2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git ls-files
README.md
f1.txt
f2.txt
five.txt
java2.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git merge sreenu
Already up to date.

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git branch -a
* main
  psg
  sreenu
  remotes/origin/main

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ echo firstfiledata>first.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ echo second file data>second.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .
warning: in the working copy of 'first.txt', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'second.txt', LF will be replaced by CRLF the next time Git touches it

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 14 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   first.txt
        new file:   second.txt


palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m"modified"
[main 56ea859] modified
 2 files changed, 2 insertions(+)
 create mode 100644 first.txt
 create mode 100644 second.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 15 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ vim first.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .
warning: in the working copy of 'first.txt', LF will be replaced by CRLF the next time Git touches it

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m"modified"
[main df86390] modified
 1 file changed, 2 insertions(+), 1 deletion(-)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 16 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ vim second.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .
warning: in the working copy of 'second.txt', LF will be replaced by CRLF the next time Git touches it

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "modiied data"
[main 972fde2] modiied data
 1 file changed, 1 insertion(+), 1 deletion(-)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 17 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --oneline
972fde2 (HEAD -> main) modiied data
df86390 modified
56ea859 modified
2faedbe Merge branch 'sreenu'
5ee08e8 (sreenu) modified
fc39016 (psg) modiied
688c73c Merge branch 'main' of https://github.com/sreenugoud/mphrepo
c7bcd6a (origin/main) Create README.md
fa0af26 java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log head
commit 972fde2e57a5f9d5440055ef35404dac1e9ccc00 (HEAD -> main)
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 16:57:42 2024 +0530

    modiied data

commit df8639084fc6eb2e92d0fd9d22af4cbcb9019b60
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 16:56:07 2024 +0530

    modified

commit 56ea859b26816e40d4840e18ea85c55b021448c4
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 16:53:09 2024 +0530

    modified

commit 2faedbe9c4f742fa8f98e8f0ca9f081397eb425c
Merge: fc39016 5ee08e8
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 16:28:27 2024 +0530

    Merge branch 'sreenu'

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git show head~1
commit df8639084fc6eb2e92d0fd9d22af4cbcb9019b60
Author: sreenugoud <sreenugoud619@gmail.com>
Date:   Mon Aug 5 16:56:07 2024 +0530

    modified

diff --git a/first.txt b/first.txt
index addebc2..dd994eb 100644
--- a/first.txt
+++ b/first.txt
@@ -1 +1,2 @@
-firstfiledata
+njkhfkfjijjkljlbsjfkfsoflo
+gfojgkjjg

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git reset --hard head~1
HEAD is now at df86390 modified

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git reset --hard head~1
HEAD is now at 56ea859 modified

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ vim second.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git commit -m "change second.txt"
[main 5da1d79] change second.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --oneline
5da1d79 (HEAD -> main) change second.txt
56ea859 modified
2faedbe Merge branch 'sreenu'
5ee08e8 (sreenu) modified
fc39016 (psg) modiied
688c73c Merge branch 'main' of https://github.com/sreenugoud/mphrepo
c7bcd6a (origin/main) Create README.md
fa0af26 java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git revert 5da1d79
[main eaf28fb] Revert "change second.txt"
 1 file changed, 1 insertion(+), 1 deletion(-)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --oneline
eaf28fb (HEAD -> main) Revert "change second.txt"
5da1d79 change second.txt
56ea859 modified
2faedbe Merge branch 'sreenu'
5ee08e8 (sreenu) modified
fc39016 (psg) modiied
688c73c Merge branch 'main' of https://github.com/sreenugoud/mphrepo
c7bcd6a (origin/main) Create README.md
fa0af26 java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git checkout psg
Switched to branch 'psg'

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ touch two.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git commit -m"data is there or not"
[psg 487a9e0] data is there or not
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 two.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git status
On branch psg
nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git log --oneline
487a9e0 (HEAD -> psg) data is there or not
fc39016 modiied
688c73c Merge branch 'main' of https://github.com/sreenugoud/mphrepo
c7bcd6a (origin/main) Create README.md
fa0af26 java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (psg)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 17 commits.
  (use "git push" to publish your local commits)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git rebase psg
Successfully rebased and updated refs/heads/main.

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --oneline
da76ac9 (HEAD -> main) Revert "change second.txt"
11f026b change second.txt
21451fa modified
ebea94c modified
487a9e0 (psg) data is there or not
fc39016 modiied
688c73c Merge branch 'main' of https://github.com/sreenugoud/mphrepo
c7bcd6a (origin/main) Create README.md
fa0af26 java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git ls-files
README.md
f1.txt
f2.txt
first.txt
five.txt
java2.txt
second.txt
two.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ ls
'New folder'/   README.md   f1.txt   f2.txt   first.txt   five.txt   java2.txt   second.txt   two.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git checkout sreenu
Switched to branch 'sreenu'

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ touch three.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git add .

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git commit -m"Branch has rebased"
[sreenu b9f44df] Branch has rebased
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 three.txt

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git status
On branch sreenu
nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git --oneline
unknown option: --oneline
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git log --oneline
b9f44df (HEAD -> sreenu) Branch has rebased
5ee08e8 modified
688c73c Merge branch 'main' of https://github.com/sreenugoud/mphrepo
c7bcd6a (origin/main) Create README.md
fa0af26 java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (sreenu)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 17 commits.
  (use "git push" to publish your local commits)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git rebase sreenu
warning: skipped previously applied commit ebea94c
hint: use --reapply-cherry-picks to include skipped commits
hint: Disable this message with "git config advice.skippedCherryPicks false"
Successfully rebased and updated refs/heads/main.

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --oneline
d83e442 (HEAD -> main) Revert "change second.txt"
acc3880 change second.txt
8f5cd86 modified
c46b411 data is there or not
2994773 modiied
b9f44df (sreenu) Branch has rebased
5ee08e8 modified
688c73c Merge branch 'main' of https://github.com/sreenugoud/mphrepo
c7bcd6a (origin/main) Create README.md
fa0af26 java to java2
d16aa12 modified
daad05e noi
a6f75ec mod
4fddc62 modified
abf8971 modified
258a34e modified
f4fdc1c modified
9f80370 modified
874a039 first commit

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --pretty='format:%C(auto)&h (%s, %ad)'
&h (Revert "change second.txt", Mon Aug 5 17:13:43 2024 +0530)
&h (change second.txt, Mon Aug 5 17:12:12 2024 +0530)
&h (modified, Mon Aug 5 16:53:09 2024 +0530)
&h (data is there or not, Mon Aug 5 17:34:27 2024 +0530)
&h (modiied, Mon Aug 5 16:06:47 2024 +0530)
&h (Branch has rebased, Mon Aug 5 17:44:36 2024 +0530)
&h (modified, Mon Aug 5 16:11:31 2024 +0530)
&h (Merge branch 'main' of https://github.com/sreenugoud/mphrepo, Mon Aug 5 14:48:02 2024 +0530)
&h (Create README.md, Mon Aug 5 14:24:59 2024 +0530)
&h (java to java2, Mon Aug 5 14:13:45 2024 +0530)
&h (modified, Mon Aug 5 14:07:56 2024 +0530)
&h (noi, Mon Aug 5 14:00:41 2024 +0530)
&h (mod, Mon Aug 5 13:59:12 2024 +0530)
&h (modified, Mon Aug 5 13:54:04 2024 +0530)
&h (modified, Mon Aug 5 13:50:29 2024 +0530)
&h (modified, Mon Aug 5 13:48:18 2024 +0530)
&h (modified, Mon Aug 5 13:47:08 2024 +0530)
&h (modified, Mon Aug 5 13:44:32 2024 +0530)
&h (first commit, Mon Aug 5 11:51:15 2024 +0530)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ git log --pretty='format:%C(auto)%h (%s, %ad)'
d83e442 (Revert "change second.txt", Mon Aug 5 17:13:43 2024 +0530)
acc3880 (change second.txt, Mon Aug 5 17:12:12 2024 +0530)
8f5cd86 (modified, Mon Aug 5 16:53:09 2024 +0530)
c46b411 (data is there or not, Mon Aug 5 17:34:27 2024 +0530)
2994773 (modiied, Mon Aug 5 16:06:47 2024 +0530)
b9f44df (Branch has rebased, Mon Aug 5 17:44:36 2024 +0530)
5ee08e8 (modified, Mon Aug 5 16:11:31 2024 +0530)
688c73c (Merge branch 'main' of https://github.com/sreenugoud/mphrepo, Mon Aug 5 14:48:02 2024 +0530)
c7bcd6a (Create README.md, Mon Aug 5 14:24:59 2024 +0530)
fa0af26 (java to java2, Mon Aug 5 14:13:45 2024 +0530)
d16aa12 (modified, Mon Aug 5 14:07:56 2024 +0530)
daad05e (noi, Mon Aug 5 14:00:41 2024 +0530)
a6f75ec (mod, Mon Aug 5 13:59:12 2024 +0530)
4fddc62 (modified, Mon Aug 5 13:54:04 2024 +0530)
abf8971 (modified, Mon Aug 5 13:50:29 2024 +0530)
258a34e (modified, Mon Aug 5 13:48:18 2024 +0530)
f4fdc1c (modified, Mon Aug 5 13:47:08 2024 +0530)
9f80370 (modified, Mon Aug 5 13:44:32 2024 +0530)
874a039 (first commit, Mon Aug 5 11:51:15 2024 +0530)

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$ ^C

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$
