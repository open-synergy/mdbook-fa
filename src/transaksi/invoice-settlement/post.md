# Post Invoice Settlement

## A. INPUT

* Data *invoice settlement* yang akan di-*post* harus memiliki status **Ready To Process**, atau **Proforma**.

![](../../img/invoice-settlement/status-ready-to-process.png)

![](../../img/invoice-settlement/status-proforma.png)

* User yang akan memposting harus memiliki akses untuk memposting *invoice settlement*.

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Settlement -> Invoice Settlement**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data *invoice settlement* yang akan di-*posting*. Abaikan jika data sudah dibuka.
3. Klik tombol **Post** pada bagian atas-kiri form. Pop-up form berjudul **Post Voucher** akan muncul.

![](../../img/invoice-settlement/tombol-post.png)


4. Isi **Date** pada pop-up form **Post Voucher**

![](../../img/invoice-settlement/pop-up-post-voucher.png)

5. Klik tombol **Post** pada bagian bawah-kiri pop-up form **Post Voucher**

![](../../img/invoice-settlement/tombol-post-voucher.png)

## C. OUTPUT

* Status dari *invoice settlement* akan berubah menjadi **Posted**

![](../../img/invoice-settlement/status-posted.png)

* Penjurnalan *invoice settlement* akan secara otomatis dibuat. Penjurnalan dapat dilihat pada tab **Accounting Information**. Isian **Accounting Entry** akan berisi journal entry yang dihasilkan. Sementara di bawah isian **Accounting Entry** akan memperlihatkan journal item dari penjurnalan *invoice settlement*.

![](../../img/invoice-settlement/hasil-penjurnalan.png)

* Penjurnalan *invoice settlement* akan mengikuti pedoman sebagai berikut:

    * n buah *journal item* akan terbentuk dengan ketentuan sebagai berikut:

        * n sama dengan jumlah *debit line*.
        * Akun yang digunakan sama dengan isian **Account** pada tiap *debit line*
        * *Debit line* dengan isian **Amount** yang bernilai positif akan didebit sejumlah nilai **Amount In Company Currency At Voucher Date**. *Debit line* dengan isian **Amount** yang bernilai negatif akan dikredit sejumlah nilai **Amount In Company Currency At Voucher Date**.

    * m buah *journal item* akan terbentuk dengan ketentuan sebagai berikut:

        * m sama dengan jumlah *credit line*.
        * Akun yang digunakan sama dengan isian **Account** pada tiap *credit line*
        * *Credit line* dengan isian **Amount** yang bernilai positif akan dikredit sejumlah nilai **Amount In Company Currency At Voucher Date**. *Credit line* dengan isian **Amount** yang bernilai negatif akan didebit sejumlah nilai **Amount In Company Currency At Voucher Date**.
