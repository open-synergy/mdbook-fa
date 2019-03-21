# Post Cash Payment

## A. INPUT

* Data cash payment yang akan di-*post* harus memiliki status **Ready To Process**, atau **Proforma**.

![](../../img/cash-payment/status-ready-to-process.png)

![](../../img/cash-payment/status-proforma.png)

* User yang akan memposting harus memiliki akses untuk memposting cash payment.

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Bank & Cash -> Cash Payment**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data cash payment yang akan di-*posting*. Abaikan jika data sudah dibuka.
3. Klik tombol **Post** pada bagian atas-kiri form. Pop-up form berjudul **Post Voucher**
akan muncul

![](../../img/cash-payment/tombol-confirm.png)


4. Isi **Date** pada pop-up form **Post Voucher**
5. Klik tombol **Post** pada bagian bawah-kiri pop-up form **Post Voucher**

## C. OUTPUT

* Status dari cash payment akan berubah menjadi **Posted**

![](../../img/cash-payment/status-posted.png)

* Penjurnalan cash payment akan secara otomatis dibuat. Penjurnalan dapat dilihat pada tab **Accounting Information**. Isian **Accounting Entry** akan berisi journal entry yang dihasilkan. Sementara di bawah isian **Accounting Entry** akan memperlihatkan journal item dari penjurnalan cash payment.

![](../../img/cash-payment/hasil-penjurnalan.png)

* Penjurnalan cash payment akan mengikuti pedoman sebagai berikut:

    * Debit pada akun **Default Debit Account** yang dimiliki oleh **Journal** yang dipilih sejumlah **Total Voucher In Company Currency**
    * Untuk setiap voucher item, isian **Account** pada voucher item akan dikredit apabila isian **Amount In Company Currency At Voucher Date** bernilai positif. Apabila isian **Amount In Company Currency At Voucher Date** bernilai negatif pada isian **Account** pada voucher item akan didebit
