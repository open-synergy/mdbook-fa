# Post Giro Payment

## A. INPUT

* Data giro payment yang akan di-*post* harus memiliki status **Ready To Process**, atau **Proforma**.

![](../../img/giro-payment/status-ready-to-process.png)

![](../../img/giro-payment/status-proforma.png)

* User yang akan memposting harus memiliki akses untuk memposting giro payment.

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Bank & Cash -> Giro Payment**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data giro payment yang akan di-*posting*. Abaikan jika data sudah dibuka.
3. Klik tombol **Post** pada bagian atas-kiri form. Pop-up form berjudul **Post Voucher**
akan muncul

![](../../img/giro-payment/tombol-confirm.png)


4. Isi **Date** pada pop-up form **Post Voucher**
5. Klik tombol **Post** pada bagian bawah-kiri pop-up form **Post Voucher**

## C. OUTPUT

* Status dari giro payment akan berubah menjadi **Posted**

![](../../img/giro-payment/status-posted.png)

* Penjurnalan giro payment akan secara otomatis dibuat. Penjurnalan dapat dilihat pada tab **Accounting Information**. Isian **Accounting Entry** akan berisi journal entry yang dihasilkan. Sementara di bawah isian **Accounting Entry** akan memperlihatkan journal item dari penjurnalan giro payment.

![](../../img/giro-payment/hasil-penjurnalan.png)

* Penjurnalan giro payment akan mengikuti pedoman sebagai berikut:

    * Debit pada akun **Default Debit Account** yang dimiliki oleh **Journal** yang dipilih sejumlah **Total Voucher In Company Currency**
    * Untuk setiap voucher item, isian **Account** pada voucher item akan dikredit apabila isian **Amount In Company Currency At Voucher Date** bernilai positif. Apabila isian **Amount In Company Currency At Voucher Date** bernilai negatif pada isian **Account** pada voucher item akan didebit
