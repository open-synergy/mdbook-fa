# Memodifikasi Cash Payment

## A. INPUT

* Data cash payment yang akan dimodifikasi harus memiliki status **Draft**.

![](../../img/cash-payment/status-draft.png)

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Bank & Cash -> Cash Payment**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data cash payment yang akan dimodifikasi. Abaikan jika data sudah dibuka.
3. Klik tombol **Edit** pada bagian atas-kiri form.

![](../../img/cash-payment/tombol-edit.png)

4. Ubah **[# Cash Payment](./penjelasan.md#field-name)** dengan penomeran yang dikehendaki. Biarkan berisi **/**
apabila menghendaki penomeran otomatis.
5. Ubah **[Company](./penjelasan.md#field-company)** jika dibutuhkan. Hanya terlihat pada implementasi multi-company. Harus diisi.
6. Isi dan sesuaikan**[Date](./penjelasan.md#field-date)**. Harus diisi.
7. Biarkan isian **[Period](./penjelasan.md#field-period)**.
8. Pilih dan sesuaikan **[Journal](./penjelasan.md#field-journal)**. Harus diisi.
9. Pilih dan sesuaikan **[Payment Mode](./penjelasan.md#field-payment-mode)**. Tidak harus diisi.
10. Pilih dan sesuaikan **[Partner](./penjelasan.md#field-partner)** Tidak harus diisi.
11. Isi dan sesuaikan **[Exchange Rate](./penjelasan.md#field-exchange-rate)**. Harus diisi.
12. <a name="l12">[Import](./membuat-detail-import.md)/[Tambah](./membuat-detail-manual.md)/[Modifikasi](./line-modifikasi.md)/[Hapus](./line-hapus.md) **Voucher Lines**</a>. Ulangi langkah ini sampai **Voucher Lines** sesuai dengan keinginan.
13. <a name="langkah-13">Isi</a> **[Write-Off Account](./penjelasan.md#field-writeoff-account)** apabila nilai **[Amount Diff](./penjelasan.md#field-amount-diff)** tidak sama dengan 0.0 dan nominal tersebut ingin di-*write-off* ke akun tertentu.
14. Klik tombol **Save** pada bagian atas-kiri form.

![](../../img/cash-payment/tombol-save.png)

## C. OUTPUT

* Data cash payment akan berubah sesuai dengan perubahan yang dilakukan.
