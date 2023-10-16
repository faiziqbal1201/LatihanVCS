# LatihanVCS

# Tutorial Menggunakan Git

# Instalasi GIT
<ul><li>pertama download terlebih dahulu git nya di (git-scm.com)</li>
<li>Sesuaikan komputer anda tapi saya saran kan memakai yg 64bit jika kalian bisa</li>
<li>Selamat kalian sudah selesai menginstal git</li></ul>

# Menambahkan config
<ul><li>pada saat pertama kali menggunakan git,perlu dilakukan konfigurasi username dan email
konfigurasi ini bisa dilakukan untuk global repository atau individual repository.
jika kalian tidak konfigurasi terlebih dahulu maka akan terjadi error saat menjalan kan perintah git init commit</li>
<li>CONFIG GLOBAL REPO
<ol type="1"><li>$ git config --global user.name “nama_user”</li>
<li>$ git config --global user.email “nama_user”</li></ol>
</li></ul>

# Membuat repository lokal
<ul><li>Buka direktory aktif, misal: c:/bahasa_pemrograman (buka menggunakan Windows Explorer)</li>
<li>buka lalu klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash command</li>
<li>Buat direktory project praktikum pertama dengan nama praktikum1</li>
<li>$ mkdir latihan1 $ cd latihan1</li>
<li>Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)</li>
direktory aktif menjadi: c:\bahasa_pemrograman\praktikum1</li>
<li>repolokal File README.md berhasil dibuat.</li>
<li>$ echo "# Latihan1" >> README.md</li>
<li>$ git add README.md</li>
<li>File README.md berhasil ditambahkan ke repolokal</li></ul>

# Push file README.md ke repository Github
<ul><li>$ git push -u origin main</li>
<li>Login akun Github untuk pertama kali</li>
<li>Login berhasil dan file telah berhasil diupload ke Github</li>
<li>Jika tidak bisa pastikan untuk Commit file yang ingin diupload</li>
<li>Pastikan remote dan buat branch Git terlebih dahulu menggunakan
<ol type="1"><li>$ git remote add origin [URL]</li>
<li>$ git branch -m main</li></ol></li>
<li>Jika belum bisa pastikan konfigurasi Config Global Repo sama dengan Akun Github </li></ul>
# LatihanVCS
