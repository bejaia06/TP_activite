
packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite ((241295b...))
$ git init
Initialized empty Git repository in C:/xampp/htdocs/test/tp/activite/.git/

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.txt
        debug.log
        fichier_1.html
        fichier_2.html

nothing added to commit but untracked files present (use "git add" to track)

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git add README.txt

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git add fichier_1.html

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git add fichier_2.html

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.txt
        new file:   fichier_1.html
        new file:   fichier_2.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        debug.log

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git commit -m "premier commit de README.txt"
[master (root-commit) b64f594] premier commit de README.txt
 3 files changed, 39 insertions(+)
 create mode 100644 README.txt
 create mode 100644 fichier_1.html
 create mode 100644 fichier_2.html

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.txt

no changes added to commit (use "git add" and/or "git commit -a")

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git add README.txt

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.txt


packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git commit -m "premier commit de fichier_1.html"
[master 1978138] premier commit de fichier_1.html
 1 file changed, 46 insertions(+)

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git status
On branch master
nothing to commit, working tree clean

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git commit -m "premier commit de fichier_2.html"
On branch master
nothing to commit, working tree clean

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git status
On branch master
nothing to commit, working tree clean

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git log
commit 197813842b2784f54a6a28cd613a1d5ac9f464d1 (HEAD -> master)
Author: Abdelkader <miliabdelkader@hotmail.fr>
Date:   Sun Sep 15 11:19:04 2019 +0200

    premier commit de fichier_1.html

commit b64f594023e062add2f648810636084bf69be7f6
Author: Abdelkader <miliabdelkader@hotmail.fr>
Date:   Sun Sep 15 11:18:10 2019 +0200

    premier commit de README.txt

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ code . README.txt

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git commit -m "Ajout d'un 2ème paragraphe au fichier_1.html"
On branch master
Changes not staged for commit:
        modified:   fichier_1.html

no changes added to commit

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git add fichier_1.html

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   fichier_1.html


packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git commit -m "Ajout d'un titre h2 au fichier_2.html"
[master 61610d0] Ajout d'un titre h2 au fichier_2.html
 1 file changed, 7 insertions(+), 1 deletion(-)

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git add fichier_2.html

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git commit -m "Ajout d'un titre h2 au fichier_2.html"
[master 9e7223f] Ajout d'un titre h2 au fichier_2.html
 1 file changed, 4 insertions(+)

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ git commit -m "Ajout d'un 2ème paragraphe au fichier_1.html"
On branch master
nothing to commit, working tree clean

packardbell@Abdelkader MINGW64 /c/xampp/htdocs/test/tp/activite (master)
$ code . README.txt
