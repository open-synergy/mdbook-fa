# Post Bank Receipt

## A. INPUT

* Data bank receipt yang akan di-*post* harus memiliki status **Ready To Process**, atau **Proforma**.

![](../../img/bank-receipt/status-ready-to-process.png)

![](../../img/bank-receipt/status-proforma.png)

* User yang akan memposting harus memiliki akses untuk memposting bank receipt.

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Bank & Cash -> Bank Receipt**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data bank receipt yang akan di-*posting*. Abaikan jika data sudah dibuka.
3. Klik tombol **Post** pada bagian atas-kiri form. Pop-up form berjudul **Post Voucher**
akan muncul

![](../../img/bank-receipt/tombol-confirm.png)


4. Isi **Date** pada pop-up form **Post Voucher**
5. Klik tombol **Post** pada bagian bawah-kiri pop-up form **Post Voucher**

## C. OUTPUT

* Status dari bank receipt akan berubah menjadi **Posted**

![](../../img/bank-receipt/status-posted.png)

* Penjurnalan bank receipt akan secara otomatis dibuat. Penjurnalan dapat dilihat pada tab **Accounting Information**. Isian **Accounting Entry** akan berisi journal entry yang dihasilkan. Sementara di bawah isian **Accounting Entry** akan memperlihatkan journal item dari penjurnalan bank receipt.

![](../../img/bank-receipt/hasil-penjurnalan.png)

* Penjurnalan bank receipt akan mengikuti pedoman sebagai berikut:

    * Debit pada akun **Default Debit Account** yang dimiliki oleh **Journal** yang dipilih sejumlah **Total Voucher In Company Currency**
    * Untuk setiap voucher item, isian **Account** pada voucher item akan dikredit apabila isian **Amount In Company Currency At Voucher Date** bernilai positif. Apabila isian **Amount In Company Currency At Voucher Date** bernilai negatif pada isian **Account** pada voucher item akan didebit
