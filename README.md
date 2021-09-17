# exercise-git
exercise-git

# Sebutkan step step dan command line saat menginisasi menggunakan git hingga sampai ke push ke github

git init
<br>
git add *
<br>
git status
<br>
git commit -m "perkembangan"
<br>
git remote add origin (isi repo)
<br>
git push -u origin (nama branch)


# perbedaan git reset dan git revert
Perintah git reset sering disebut sebagai perintah berbahaya yang dapat menghancurkan catatan sejarah perubahan.
Hati-hati! Perintah ini membuat kita tidak bisa kembali lagi ke masa depan. Mau tidak mau, kita harus menulis ulang sejarah.

Revert artinya mengembalikan. Perintah ini lebih aman daripada git reset, karena tidak akan menghapus catatan sejarah revisi.
Revert akan akan mengambil kondisi file yang ada di masa lalu, kemudian menggabungkannya dengan commit terakhir.

# perbedaan git dan github

git adalah cli yang didalamnya ada perintah linux untuk control 
<br>
github adalah sebuah layanan cloud untuk penyimpanan yang biasanya bernama repository
