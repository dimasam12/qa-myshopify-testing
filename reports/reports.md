📁 LAPORAN 1 – SEVERITY HIGH
Laporan Hasil Pengujian (Test Report)
Item	Detail
Project Name	https://sauce-demo.myshopify.com
Tester	Dimas Akbar Maulana
Tanggal Pengujian	20 April 2026
Case ID	TC.FP_02
Scenario ID	TS.FP_02
Test Scenario	Validasi forget password
Type	Negative
Test Case	Validasi email tidak terdaftar
Status	FAIL
Severity	HIGH
Deskripsi
User memasukkan email yang tidak terdaftar pada halaman forget password, namun sistem tetap memproses dan mengirimkan tautan reset password.

Pre Condition
User sudah berada di halaman forget password.

Langkah Uji
Step	Deskripsi
1	Masukkan email yang tidak terdaftar: anga@gmail.com
Expected Result
Sistem menampilkan pesan error "Masukkan email yang terdaftar".

Actual Result
Sistem tetap mengirimkan tautan reset password ke email yang tidak terdaftar dan redirect ke halaman Home tanpa pesan validasi.

Bukti
https://drive.google.com/drive/folders/1WMvQhxUcbMkjI0kFuowmsZVR3lmvWGMP?usp=sharing





📁 LAPORAN 2 – SEVERITY MEDIUM
Laporan Hasil Pengujian (Test Report)
Item	Detail
Project Name	https://sauce-demo.myshopify.com
Tester	Dimas Akbar Maulana
Tanggal Pengujian	20 April 2026
Case ID	TC.reg_03
Scenario ID	TS.Reg_03
Test Scenario	Check Validasi registrasi
Type	Negative
Test Case	Validasi Format nama depan dan nama belakang dengan angka atau simbol
Status	FAIL
Severity	MEDIUM
Deskripsi
User memasukkan nama depan dan belakang yang mengandung angka dan simbol (dimas123@ / akbar123), namun sistem tetap menerima registrasi.

Pre Condition
User sudah berada pada halaman Sign Up.

Langkah Uji
Step	Deskripsi
1	Masukkan nama depan: dimas123@
2	Masukkan nama belakang: akbar123
3	Isi email dan password valid
4	Tap Create Account
Expected Result
Sistem menampilkan pesan error: "Nama depan tidak boleh mengandung angka atau simbol". User tetap di halaman Sign Up.

Actual Result
User berhasil create account dan masuk ke halaman Home yang sudah login.

Bukti
Link Drive 
https://drive.google.com/drive/u/1/folders/1UvKXQRx0Pu79s1OOGahvWHibO6bK0PxT
1.png dan 2.png 


📁 LAPORAN 3 – SEVERITY LOW
Laporan Hasil Pengujian (Test Report)
Item	Detail
Project Name	https://sauce-demo.myshopify.com
Tester	Dimas Akbar Maulana
Tanggal Pengujian	20 April 2026
Case ID	TC.Log_03
Scenario ID	TS.Log_03
Test Scenario	Check validasi Login
Type	Negative
Test Case	Email tidak terdaftar
Status	PASS (dengan bug minor)
Severity	LOW
Deskripsi
User login dengan email yang tidak terdaftar, sistem menolak akses (sudah benar), namun pesan error tidak sesuai dengan kondisi sebenarnya.

Pre Condition
User sudah berada di halaman Login.

Langkah Uji
Step	Deskripsi
1	Masukkan email tidak terdaftar: anga@gmail.com
2	Masukkan password: angga123
3	Tap Login
Expected Result
Sistem menampilkan pesan error: "Email tidak terdaftar".

Actual Result
Sistem menampilkan pesan error: "incorrect email password" (pesan generik).

Bukti
[Link Drive](https://drive.google.com/drive/folders/1SVCw2idCwUUaG75Tku7E_qMdzMAs-yWm?usp=drive_link)
1.png dan 2.png 
