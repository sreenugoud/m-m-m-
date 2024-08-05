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

nothing to commit, working tree clean

palla.goud@WKSCHE03TRNG016 MINGW64 ~/Gitbash/mphrepo (main)
$
