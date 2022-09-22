# Git-Example

Catatan Pembelajaran Git WPU
Catatan LARAVEL

-> ketika tidak ada vendor
Akun :
username : ZekarioRPL
pw : sefdanny12

=> composer update

# GIT
---
+ git bash
+ git init -> untuk membuat repo (master)
+ git status
+ git add <file(s)> -> $ git add index.html -> menambahkan ke git
+ git commit
+ git confiq
+ git branch
+ git help
+ git log / $ git log -3 (3 commit terakhir) / $ git log -- style.css (SPESIFIK MELIHAT COMMIT MANA DARI FILE TERTENTU)
+ git checkout
---
# GIT COMMAND

+$ pwd
+$ ls

+$ git commit

	$ git confiq --global user.email "your@xample.com"
	
	$ git confiq --global user.name "yourname"
	
+ketika commitnya sedikit / satu baris

+$ git commit -m "menambahkan file index.html"

+untuk menambahkan semua di git add
+$ git add .

+ketika berada di vim cara keluar : esc -> ":q!"

+$ git checkout ***** (5 digit pertama dari commit hashnya) -- style.css(nama filenya)

+cara cepat untuk file modifited
+$ git commit -am "modif file index.html"

------
+git branch
+$ git branch
+$ git branch <nama branch>

+membuat menduplikat branch tapi di commit yang sama
+$ git branch dosen(nama)

+melihat log seperti fi github
+$ git log --all --decorate --oneline --graph

+membuat alias atau singkatan di sini
+alias graph(nama)="git log --all --decorate --oneline --graph(codenya)"

+pindah ke branch lain
+$ git checkout dosen(nama)
+cek branch
+$ git branch

+untuk merge
+$ git merge dosen(nama)

+cara hapus branch setelah di merge
+$ git branch -d dosen(nama)
+menghapus branch tanpa merge
+$ git branch -D dosen(nama)

+melihat branch yang sudah di merge
+$ git branch --merged

+three-way merge = ketika cabangnya tidak bersinambungan di commitnya
+$ git merge dosen2(nama) -> ini akan menggabungkan 2 branch (dosen,dosen2) yang tidak bersinambungan dan membuat commit baru (gabung)

+ketika masuk ke vim pas $ git merge dosen2(nama) -> esc -> :wq!

----

+untuk head di commit yang ditentukan
+$ git checkout *******(7 digit kode commit)

+$ git clone https://****************

+$ git remote
+$ git remote -v

+$ git push

+chek akun github  di git bash
+$ git config --list
+keluarnya = :q

+ganti dengan akun github yang ditentukan // --local artinya digunakan untuk repo yang itu saja yang lain akan ke --global
+$ git config (--local / --global) user.name "**********"
+$ git config --global user.email "**************"

+untuk mengecek repo di remote(github) sudah sampai mana
+$ git fetch 

+ambil repo di github(remote)
+$ git pull

------
+push dengan branch lain 
+git push -u origin(nama remote) Dashboard1(nama branch)

+membuat mutilple remote
+git remote add ZidanFikriAditya https://github.com/ZidanFikriAditya/project-akhir.git...

+mutilpe remote
+$ git merge asli(nama remote)/master(nama branch)
+git merge asli/main

+$ git push -u origin(nama remote) master(branch)
---

+.gitignore
+https://gitignore.io

+$ git rebase

----
