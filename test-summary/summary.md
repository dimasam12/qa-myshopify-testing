📊 Test Summary – Sauce Demo Shopify
📌 Informasi Pengujian
Project: https://sauce-demo.myshopify.com
Tester: Dimas Akbar Maulana
Tools: Manual Testing
Jenis Testing: Functional Testing (Positive & Negative)

📊 Hasil Eksekusi
Total Test Case: 41
Passed: 34
Failed: 7
Pass Rate: 82.9%

🐞 Ringkasan Bug
Ditemukan 7 bug selama pengujian, dengan rincian:

Severity High (3 bug)

TC.FP_02 – Email tidak terdaftar tetap diproses di forget password

TC.CART_16 – Add cart tanpa login berhasil

TC.CART_17 – Checkout tanpa login berhasil

Severity Medium (1 bug)

TC.reg_03 – Validasi nama depan/belakang dengan angka/simbol tidak berjalan

Severity Low (3 bug)

TC.Log_03 – Pesan error tidak sesuai saat email tidak terdaftar

TC.Log_05 – Pesan error tidak sesuai saat login kosong

TC.Log_07 – Pesan error tidak sesuai saat password tanpa email

📈 Analisis
Modul Registrasi memiliki pass rate 88.9% dengan 1 bug Medium.
Modul Login memiliki pass rate 57.1% dengan 3 bug Low pada pesan error yang tidak spesifik, namun secara fungsional sistem tetap aman.
Modul Forget Password memiliki pass rate 85.7% dengan 1 bug High.
Modul Cart memiliki pass rate 88.9% dengan 2 bug High.

✅ Kesimpulan
Sistem secara umum cukup stabil dengan pass rate 82.9%, namun terdapat 3 bug dengan severity High yang perlu segera diperbaiki karena berdampak pada keamanan dan logika bisnis, terutama pada modul Cart dan Forget Password.

Terdapat 1 bug dengan severity Medium pada modul Registrasi terkait validasi input nama yang perlu diperbaiki.

Modul Login memiliki 3 bug dengan severity Low yang perlu perbaikan pada pesan error agar lebih informatif, meskipun secara fungsional sudah aman
