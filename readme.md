# Git Flow Dokumentasi

## Git flow untuk new project

- set dulu akun global untuk github dengan:
git config --global user.name "Your name"
git config --global user.email “Your email” contoh: example@mail.com
- git init, digunakan untuk inisiasi github dengan folder local
- setelah itu di add, dengan menggunakan command "git add ." pada git add . artinya memasukkan seluruh file atau bisa juga dengan mengadd file tertentu dengan memasukkan nama file tersebut seperti ini "git add index.html
- setelah itu di commit, dengan menggunakan command "git commit -m "nama commit" dan jika sudah terlanjur mencommit dan tidak ingin menambah commit terlalu banyak bisa dengan flag "--amend"
- setelah itu setting remote akun githubnya, dengan remote git remote nama ssh atau https
contoh: git remote add origin git@github.com:prihuda/prihuda.github.io.git
- setelah itu push dengan command, "git push origin master"
- Lihat di akun github maka akan ada file baru di repository yang telah dibuat sebelumnya

## Membuat static website dengan github

- pertama-tama buat lah repository dan berikan tambahan github.io pada isian di repository sebagai contoh prihuda.github.io
- sama seperti diatas jika belum diinisiasi atau pertama kali maka dimulai dengan "git init"
- setelah itu add dengan "git add index.html", index.html telah dibuat sebelumnya index ini berisi tabel singkat tentang biodata
- setelah itu di commit, dengan command "git commit -m "nama commit"
- pastikan sudah diremote, diwindows akan ada terlihat sebuah tanda (master) yang berarti sudah melakukan remote repository secara benar
- setelah itu di push dengan command, "git push origin master"
- Hasil akan terlihat dengan mengetik "prihuda.github.io" pada browser

## Gitflow pada existing project

- 
