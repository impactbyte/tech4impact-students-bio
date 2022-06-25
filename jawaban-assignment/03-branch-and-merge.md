# Answers:
1.	**What does git clean do?**
Perintah "git clean" membersihkan struktur pohon kerja dengan menghapus file yang tidak berada di bawah version control secara rekursif. Pembersihannya dimulai dari direktori saat ini.
2.	**What do the -d and -f flags for git clean do?**
Opsi -d memberi daftar direktori yang akan dihapus, sedangkan opsi -f menghapus file tanpa termasuk direktorinya. 
3.	**What git command creates a branch?**
git branch <new_branch>
4.	**What is the difference between a fast-forward and recursive merge?**
Fast forward merge dapat dilakukan ketika ada jalur linier langsung dari sumber branch ke target branch. Dalam merge ini, git cukup memindahkan penunjuk sumber branch ke target branch tanpa membuat commit gabungan tambahan. Sedangkan recursive merge adalah kebalikannya. Setelah seseorang melakukan branch dan membuat beberapa commit, ada beberapa commit baru di 'master'. Jadi, ketika saatnya untuk menggabungkan, git akan rekursif ke branch dan membuat commit gabungan baru.
5.	**What git command changes to another branch?**
git checkout
6.	**How do you remove modified or deleted files from the working directory?**
Menggunakan git rm command supaya file yang dihapus tidak terdeteksi sebagai file tidak terlacak kedepannya.
7.	**What git command deletes a branch?**
git branch -d
8.	**What does the git diff command do?**
Mereview perubahan yang sudah dilakukan pada proyek.
9.	**How do you remove files from the staging area?**
git rm --cached <nama file>
10.	**How do merge conflicts happen?**
Merge conflicts muncul ketika baris kode yang sama telah dimodifikasi di commit yang berbeda. Conflicts umumnya muncul ketika dua orang telah mengubah baris yang sama dalam file, atau jika satu developer menghapus file sementara developer lain memodifikasinya. Dalam kasus ini, Git tidak dapat secara otomatis menentukan apa yang benar. 

