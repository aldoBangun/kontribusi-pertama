# BELAJAR KONTRIBUSI KE GITHUB

> Repository untuk belajar kontribusi ke github. Repository ini terispirasi dari salah satu repository yang digunakan untuk belajar juga yaitu [first-contribution](https://github.com/firstcontributions/first-contributions) dan saya kemas lagi dengan tujuan untuk mempermudah proses belajar kontribusi ke open source baik untuk saya pribadi ataupun untuk umum.

## Cara Kontribusi

1. Lakukan `fork` pada repository ini

   ![Fork Repository](images/fork.png)


2. `create fork` ke repository mu

   ![Create Fork](images/create-fork.png)


3. Copy url repository yang sudah di `fork` untuk proses clone. Pastikan sudah di repo mu seperti di kotak biru <nama-kamu>/kontribusi-pertama

   ![Copy Url](images/copy-git-url.png)


4. Lakukan `clone` pada repo yang sudah di fork menggunakan terminal atau dapat langsung menggunakan VSCode.

```
git clone https://github.com/<username-kamu>/kontribusi-pertama.git
```

   ![Clone Repo](images/clone-repo.png)


5. Masuk ke directory repository yang baru saja di clone menggunakan perintah

```
cd kontribusi-pertama
```

   ![Change Directory](images/change-directory.png)


6. Buat branch baru untuk menambahkan data mu

   ```
   git branch <nama-mu>
   ```

   ![Add New Branch](images/create-new-branch.png)


7. Pindah ke branch yang baru dibuat

   ```
   git switch <nama-mu>
   ```

   ![Switch branch](images/switch-branch.png)


8. Buka `index.js`

   ![Open Index.js](images/open-index.js.png)


9. Tambahkan data mu kedalam variabel `people` dan jangan lupa untuk di `save` setelah menambahkan data mu

   ![Add new data](images/add-new-object.png)


10. Tambahkan perubahan menggunakan 

   ```
   git add index.js
   ```

   ![Add Change](images/git-add.png)


11. Lakukan `commit` pada perubahan yang baru saja dibuat

   ```
   git commit -m "<pesan-mu>"
   ```

   ![Commit Changes](images/commit-change.png)


12. Push perubahan yang baru saja dibuat ke branch yang sudah dibuat di step 6.

   ```
   git push origin <branch-mu>
   ```

   ![Push Changes](images/push-branch.png)


13. Kembali ke `github` untuk melakukan proses `Pull Request`

   ![Compare and Pull Request](images/pull-request.png)


14. Langkah terakhir adalah submit `Pull Request` mu dengan menekan tombol `Create pull request`

   ![Create Pull Request](images/create-pull-request.png)


15. Selesai.


### Catatan

Setelah melakukan proses `pull request`, perubahan yang sudah ditambahkan kamu akan direview dan akan ditambahkan oleh pemilik asli repository. Setelah di review dan ditambakan oleh pemilik asli repository maka perubahan sudah dapat dilihat di repository aslinya. 


### Ucapan Selamat

Selamat kamu sudah berhasil untuk melakukan kontribusi ke github. Terima kasih sudah mau berkontribusi untuk repository ini. Semoga bermanfaat.

---

<font size="2"> ❤️ [Aldo Bangun](https://github.com/aldobangun) </font>