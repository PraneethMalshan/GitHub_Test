<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study
#Make a directory -> mkdir malshan
$ mkdir malshan -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study
#Go to directory -> cd malshan 
$ cd malshan -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan
#Open code editor -> code .
$ code . -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan
#Check created files from code editor -> ls -la
$ ls -la
total 0
drwxr-xr-x 1 ASUS 197121 0 Sep 17 15:59 ./
drwxr-xr-x 1 ASUS 197121 0 Sep 17 15:57 ../
-rw-r--r-- 1 ASUS 197121 0 Sep 17 15:59 index.html -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan
#Check git status(Git ekata add karanna mokuth thiinawada kiyala balanne meeken) -> git status
$ git status
fatal: not a git repository (or any of the parent directories): .git -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan
#Mulinma git ekata add karanna issellaa gahana command eka. -> git init
$ git init
Initialized empty Git repository in F:/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan/.git/ -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Git ekata init kalaata passe .git file eka create welaada kiyala balanawa. -> ls -la
$ ls -la
total 4
drwxr-xr-x 1 ASUS 197121 0 Sep 17 16:03 ./
drwxr-xr-x 1 ASUS 197121 0 Sep 17 15:57 ../
drwxr-xr-x 1 ASUS 197121 0 Sep 17 16:03 .git/
-rw-r--r-- 1 ASUS 197121 0 Sep 17 15:59 index.html -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track) -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Git ekata index.html file ekA add kiriima -> git add index.html
$ git add index.html -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Git ekata add unaada kiyala checkkaranawa 
$ git status 
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Thawath files tikak hadala eewa thiinawada kiyala check karanna puluwan. -> ls -la
$ ls -la
total 4
drwxr-xr-x 1 ASUS 197121 0 Sep 17 16:08 ./
drwxr-xr-x 1 ASUS 197121 0 Sep 17 15:57 ../
drwxr-xr-x 1 ASUS 197121 0 Sep 17 16:08 .git/
-rw-r--r-- 1 ASUS 197121 0 Sep 17 16:08 index.css
-rw-r--r-- 1 ASUS 197121 0 Sep 17 15:59 index.html
-rw-r--r-- 1 ASUS 197121 0 Sep 17 16:08 index.js -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Add karapu files 2 thinawada kiyala check kalaa
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.css
        index.js -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Git ekata add kalaa -> git add --all
$ git add --all -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Git ekata add unaadakiyala  balanawa.
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.css
        new file:   index.html
        new file:   index.js -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Api karana dee comment ekakin damiima -> git commit -m "comment"
$ git commit -m "I Created my first and I added some files to it."
[master (root-commit) ff3b2ab] I Created my first and I added some files to it.
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.css
 create mode 100644 index.html
 create mode 100644 index.js -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
$ git status
On branch master
nothing to commit, working tree clean -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Git ekata log welaa balanawa api karala thiina dee. Eeka commit eken karapu dee pennanawa. -> git log
$ git log
commit ff3b2ab73070f87541d6dff2e90bad1f8112037e (HEAD -> master)
Author: PraneethMalshan <praneethmalshan12345@gmail.com>
Date:   Tue Sep 17 16:12:13 2024 +0530

    I Created my first and I added some files to it. -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#"test" kiyala branch ekak create kiriima -> git branch test 
$ git branch test -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Hadala thiina branch tika baliima -> git branch
$ git branch
* master
  test -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Branch ekakata maaru wiima -> git checkout test
$ git checkout test
Switched to branch 'test' -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#test branch ekee monawath thiinawada kiyala balanawa.
$ git status
On branch test
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a") -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#test branch eke thina eewath git ekata add kiriima. -> git add --all
$ git add --all -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#Commit karala karala thiina dee comment ekakin damiima
$ git commit -m "I modified index.html"
[test 5009d9f] I modified index.html
 1 file changed, 11 insertions(+) -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#nawathath git ekata add unaada kiyala balanawa.
$ git status
On branch test
nothing to commit, working tree clean -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#nawathath master branch ekata maaru wenawa. dn master branch ekee index.html ekee monuth naa.. heethuwa test branch ekee witharayi add kale. eeka master branch ekata addkaranna oona okkoma wada clear nam. -> git checkout master
$ git checkout master
Switched to branch 'master' -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#aaye balanakota test branch ekee thiinna oona karapu tika.
$ git checkout test
Switched to branch 'test' -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
# Branch ekak athule thawa branch ekak create kiriima -> git checkout -b test1
$ git checkout -b test1
Switched to a new branch 'test1' -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test1)
#thiina branches tika baliima -> git branch
$ git branch
  master
  test
* test1 -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test1)
#test1 branch ekee sita test branch ekatamaaru wiima -> git checkout test
$ git checkout test
Switched to branch 'test' -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#Delete karanna oona nam delet karana braanch ekata issellaa thiina branch ekata gihin oona delet karanna. git branch -d test1
$ git branch -d test1
Deleted branch test1 (was 5009d9f). -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#Dan test1 branch eka delete welaa.
$ git branch
  master
* test -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#master branch ekata yanawa -> git checkout master
$ git checkout master
Switched to branch 'master' -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#test branch ekee thiina saama deyakma master branch ekata damiima -> git merge test
$ git merge test
Updating ff3b2ab..5009d9f
Fast-forward
 index.html | 11 +++++++++++
 1 file changed, 11 insertions(+) -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
$ git status
On branch master
nothing to commit, working tree clean -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#README.md file ekak crerate karala eeka thiinwada kiyala balanawa.
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track) -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#hadapu REACME.md file eka git ekata add kiriima -> git add --all
$ git add --all -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.md -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Git ekata addkalaa kiyala comment ekak daanawa.
$ git commit -m "I created README.md file in master branch"
[master 29c342e] I created README.md file in master branch
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
$ git status
On branch master
nothing to commit, working tree clean -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (master)
#Master branch ekee idala test ekata maaru wenoo...
$ git checkout test
Switched to branch 'test' -->


<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
#test ekee idala thamaa master branch ekata test branch ekee thiina eewa daanne.. eekata kiyanawa "merge" karanawa kiyala. -> git merge master
$ git merge master
Updating 5009d9f..29c342e
Fast-forward
 README.md | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md -->

<!-- ASUS@LAPTOP-KK3ET04D MINGW64 /f/Praneeth/IJSE/My_Full_Sylabus_Cover_At_Home/GIT_Study/malshan (test)
$ -->

<!-- 
$ git remote add origin https://github.com/PraneethMalshan/GitHub_Test.git -> meka github eken copy karla aragena daala enter karanna.
 -->

 <!-- 
 git push -u origin master -> meka dammata passe github ekata add welaa thiinawa balaa ganna puluwan.
  -->

<!-- ======================================================== -->
  <!-- GitHub wala thina repositories git ekata kohomada danne & Git wala thina repositories GitHub ekata kohomada ganne wagee deewal & Branch kohomada api git & github athara huwamaru kara ganne ohomada kiyala baliiima.-->

  <!--1. apita git hub ekenuth code eka edit kara ganna puluwan. adaala thanata gihin uda thiinawa edit icon eka. eekan dunnaama code edit karala commit ekak gahala thiyanna puluwan.  -->

  <!--2. Ehema GitHub ekee edit karapu code eka Local git ekata ekathu kara ganne  mehemayi. $ git pull origin
-->