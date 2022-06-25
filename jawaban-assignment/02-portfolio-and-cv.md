# Steps:
1. mkdir nurultrisnaaulya
2. echo "Halo perkenalkan aku halaman utama" >> README.md
3. git init, git commit -m "Inisialisasi Git Repository"
4. git branch cv
5. git checkout cv, echo "Ini adalah file CV" >> cv.txt
6. git commit -m "Inisialisasi cv"
7. echo "1. Tokopedia" >> cv.txt, git commit -m "Menambahkan perusahaan kesatu", echo "2. Facebook" >> cv.txt, git commit -m "Menambahkan perusahaan kedua", echo "3. Gojek" >> cv.txt, git commit -m "Menambahkan perusahaan ketiga"
8. git checkout master
9. echo "Halo perkenalkan aku halaman utama. Ini adalah update pertama pada branch master" > README.md, commit -m "update master pertama"
10. git merge cv
11. git push
