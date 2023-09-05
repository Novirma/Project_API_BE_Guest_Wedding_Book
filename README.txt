Catatan :

1. Ini merupakan sebuah API dengan menggunakan frame work NestJS.
2. Setelah Men Clone Soal nomor 2 yaitu folder "project-name"  harap di lakukan penginstalan node modules terlebih dahalu dengan perintah di terminal "npm install"
3. Untuk menjalankan server dapat dengan perintah "npm run start:dev"
4. Sebelum menjalankan Back End di harapkan Importlah database ke dalam aplikasi database PostgreSQL yaitu file "backup_db_merkle_innovation.sql"
5. Tampunglah database di atas ke dalam database baru yang di beri nama database "db_merkle_innovation" agar tidak terjadi error
6. Harap database di masukkan ke dalam default postgreSQL yaitu dengan -user postgres -host localhost -port 5432
7. Untuk Function API membuat Guest Form dan API mendapatkan Note Gallery terdapat dalam src/guest_form/entities/guest_form.service.ts
8. Untuk Controller Url API membuat Guest Form dan API mendapatkan Note Gallery terdapat dalam src/guest_form/entities/guest_form.controller.ts
9. Untuk Function API membuat API Create User Tamu dan API mendapatkan data semua User tamu terdapat dalam src/user_tamu/user_tamu.service.ts
10. Untuk Controller Url API membuat API Create User Tamu dan API mendapatkan data semua User tamu terdapat dalam src/user_tamu/user_tamu.controller.ts
11. Untuk Function API Login dan Mendapatkan token terdapat dalam src/login/login.service.ts
12. Untuk Controller Url API Login dan Mendapatkan token terdapat dalam src/login/login.controller.ts
13. Untuk Function Pengaturan MiddleWare Token terdapat dalam src/token/token.middleware.ts
14. Sehingga Pengaturan Middleware Token di atas dapat di atur dalam src/app.module.ts pada bagian "export class AppModule implements NestModule" 
15. Untuk login Masukkan ke dalam Header dan beri key "authorization" dengan value Token hasil login
16. Akun yang dapat di gunakan untuk login adalah "username : admin" dan "password:12345"
17. Importlah Link API nya pada file "API_Wedding_Guest_Book.postman_collection.json"
