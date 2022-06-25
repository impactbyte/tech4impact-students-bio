# Answers:
1.	**What is the difference between git reset and git revert. When would you use one over the other?**
Keduanya hampir sama tapi penggunaanya tergantung skenario development. git reset bisa digunakan untuk memodifikasi index, mengubah arah commit branch head, dan merubah riwayat yang ada. Sebaliknya, git revert sifatnya seperti undo. git revert mencari cara untuk membalikan perubahan yang dilakukan oleh commit dan menambahkan commit baru dengan menghasilkan konten terbalik.
2.	**What is the difference between git merge and git rebase. When would you use one over the other?**
Perbedaannya terletak pada bagaimana keduanya digunakan. Git rebase memindahkan cabang fitur menjadi master dan git merge menambahkan commit baru. Git rebase digunakan jika ingin meluruskan riwayat yang kemungkinan kompleks, menghindari merge dari commit di branch dan repo yang sibuk, kemudian membersihkan commit perantara menjadi commit tunggal. Git merge digunakan jika menjaga riwayat dalam urutan kronologis dan sederhana.
3.	**What is the difference between git stash pop and git stash apply. When would you use one over the other?**
Git stash pop membuang elemen stash paling atas secara default setelah menerapkannya, sedangkan git stash apply meninggalkan stash di daftar stash untuk kemungkinan digunakan kembali nanti. Git stash digunakan ketika ingin merekam status direktori kerja dan indeks saat ini, tetapi ingin kembali ke direktori kerja yang bersih.
4.	**What kinds of things can you do in interactive mode when rebasing?**
Interactive rebasing bisa digunakan dalam perubahan commit seperti edit, delete, dan stash. Dibanding mengabaikan semua commit karena commit mengandung kesalahan, mode interactive dapat diterapkan lagi dan dapat menganalisis dampak dari riwayat yang diubah oleh commit.

