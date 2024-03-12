# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
brand@Robosa MINGW64 /c/Github
$ git clone https://github.com/BrandonNathanael/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.

brand@Robosa MINGW64 /c/Github
$ git config --global user.email "brandonmontong01@gmail.com"

brand@Robosa MINGW64 /c/Github
$ cd belajarGiT

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-git)
$ touch Tugas-git.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-git)
$ git add Tugas-git.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-git)
$ git commit -m "commit tugas git"
[Tugas-git b6f76b6] commit tugas git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git merge Tugas-git
Updating b316e44..b6f76b6
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 289 bytes | 289.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/BrandonNathanael/belajarGIT.git
   b316e44..b6f76b6  main -> main

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$ ^C

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$  touch Tugas-html.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$ ^C

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$ git add Tugas-html.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$ ^C

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$ git commit -m "commit tugas html"
[Tugas-html f268afd] commit tugas html
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$ ^C

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-html)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git merge Tugas-html
Updating b6f76b6..f268afd
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ ^C

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git push origin main



Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/BrandonNathanael/belajarGIT.git
   b6f76b6..f268afd  main -> main

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-css)
$ touch Tugas-css.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-css)
$ git add Tugas-css.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-css)
$ git commit -m "commit tugas css"
[Tugas-css 2d59b7d] commit tugas css
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-css)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git merge Tugas-css
Updating f268afd..2d59b7d
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-js)
$ touch Tugas-js.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-js)
$


brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-js)
$

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-js)
$ git add Tugas-js.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-js)
$ git commit -m "commit tugas js"
[Tugas-js f5cfda7] commit tugas js
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-js)
$  git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git merge Tugas-js
Updating 2d59b7d..f5cfda7
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 528 bytes | 528.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/BrandonNathanael/belajarGIT.git
   f268afd..f5cfda7  main -> main

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-midProject)
$ touch Tugas-midProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-midProject)
$ git add Tugas-midProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-midProject)
$ git commit -m "commit tugas midProject"
[Tugas-midProject 33174b5] commit tugas midProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-midProject)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git merge Tugas-midProject
Updating f5cfda7..33174b5
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BrandonNathanael/belajarGIT.git
   f5cfda7..33174b5  main -> main

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-php)
$ touch Tugas-php.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-php)
$ git add Tugas-php.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-php)
$ git commit -m "commit tugas php"
[Tugas-php 888bab0] commit tugas php
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-php)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git merge Tugas-php
Updating 33174b5..888bab0
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BrandonNathanael/belajarGIT.git
   33174b5..888bab0  main -> main

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-finalProject)
$ git commit -m "commit tugas finalProject"
[Tugas-finalProject a64118a] commit tugas finalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (Tugas-finalProject)
$  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git merge Tugas-finalProject
Updating 888bab0..a64118a
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BrandonNathanael/belajarGIT.git
   888bab0..a64118a  main -> main

brand@Robosa MINGW64 /c/Github/belajarGiT (main)
$
