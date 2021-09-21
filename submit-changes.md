# Jawaban No 5 Technical Assessment Skilvul - Git & Github
1. Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu <br>
![image](https://user-images.githubusercontent.com/72689610/134130393-a1e753bf-de22-49f1-8d28-dab5efd2b3b9.png)

2. Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.
![image](https://user-images.githubusercontent.com/72689610/134130749-4bc5784c-1ba4-4c9a-a580-30ba92dd169f.png) <br>
```git clone https://github.com/LevraGav/tech4impact-students-bio```

3. Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.
![image](https://user-images.githubusercontent.com/72689610/134130975-4f741c51-d910-4c9a-87ca-48d597a68dc2.png) <br>
```git branch arvel-gavrilla-raissananda```

4. Checkout ke dalam branch tersebut yang telah kamu buat
![image](https://user-images.githubusercontent.com/72689610/134131225-69e927ca-46ac-4c4a-8902-0460a8ab3b2b.png) <br>
```git checkout arvel-gavrilla-raissananda```

5. Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md
![image](https://user-images.githubusercontent.com/72689610/134131367-c9223b69-4273-4ddb-8155-0803aaf03f4f.png) <br>
```touch arvelgavrillaraissananda.md```

6. Isi file tersebut ```davidwinalda.md``` dengan konten di bawah ini:
![image](https://user-images.githubusercontent.com/72689610/134131748-7c053b85-7c7b-40c2-ae4a-b20fec7e5c59.png)

7. Masukkan file .md tersebut ke dalam staging area
![image](https://user-images.githubusercontent.com/72689610/134131966-113da321-98a5-4107-b1d9-9173d2b86e64.png) <br>
```git add arvelgavrillaraissananda.md```

8. Commit dengan memberikan pesan nama file ```.md``` kamu
![image](https://user-images.githubusercontent.com/72689610/134132237-3193913b-4b97-48a8-9658-7ac0d8cf75b1.png) <br>
```git commit -m "arvelgavrillaraissananda.md"```

9. Merge branch yang telah kamu buat ke dalam branch ```master```
![image](https://user-images.githubusercontent.com/72689610/134132488-76e30f07-93a8-4fa3-b8a1-5e2441ff27ca.png) <br>
```git checkout master``` <br>
```git merge arvel-gavrilla-raissananda```

10. Push ke dalam branch ```master```
![image](https://user-images.githubusercontent.com/72689610/134132778-6e4323a4-2cc6-432c-8325-9241b5eb508f.png) <br>
```git push```

11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch ```master``` pada GitHub Repository aslinya.
![image](https://user-images.githubusercontent.com/72689610/134133238-64b14b83-2133-43a7-a6a4-9e5bf8b1e3f9.png) <br>
Link pull : <a target="_blank" href="https://github.com/impactbyte/tech4impact-students-bio/pull/33">Pull Request<a/>





