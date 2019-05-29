# Memodifikasi Cash Receipt

## A. INPUT

* Data cash receipt yang akan dimodifikasi harus memiliki status **Draft**.

![](../../img/cash-receipt/status-draft.png)

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Bank & Cash -> Cash Receipt**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data cash receipt yang akan dimodifikasi. Abaikan jika data sudah dibuka.
3. Klik tombol **Edit** pada bagian atas-kiri form.

![](../../img/cash-receipt/tombol-edit.png)

4. Ubah **[# Cash Receipt](./penjelasan.md#field-name)** dengan penomeran yang dikehendaki. Biarkan berisi **/**
apabila menghendaki penomeran otomatis.
5. Ubah **[Company](./penjelasan.md#field-company)** jika dibutuhkan. Hanya terlihat pada implementasi multi-company. Harus diisi.
6. Isi dan sesuaikan **[Date](./penjelasan.md#field-date)**. Harus diisi.
7. Biarkan isian **[Period](./penjelasan.md#field-period)**.
8. Pilih dan sesuaikan **[Journal](./penjelasan.md#field-journal)**. Harus diisi.
9. Pilih dan sesuaikan **[Partner](./penjelasan.md#field-partner)** Tidak harus diisi.
10. Isi dan sesuaikan **[Total Voucher](./penjelasan.md#field-total-voucher)**. Harus diisi.
11. Isi dan sesuaikan **[Exchange Rate](./penjelasan.md#field-exchange-rate)**. Harus diisi.
12. <a name="l12">[Import](./membuat-detail-import.md)/[Tambah](./membuat-detail-manual.md)/[Modifikasi](./line-modifikasi.md)/[Hapus](./line-hapus.md) **Voucher Lines**</a>. Ulangi langkah ini sampai **Voucher Lines** sesuai dengan keinginan.
13. <a name="langkah-12">Isi</a> **[Write-Off Account](./penjelasan.md#field-writeoff-account)** apabila nilai **[Amount Diff](./penjelasan.md#field-amount-diff)** tidak sama dengan 0.0 dan nominal tersebut ingin di-*write-off* ke akun tertentu.
14. Klik tombol **Save** pada bagian atas-kiri form.

![](../../img/cash-receipt/tombol-save.png)

## C. OUTPUT

* Data cash receipt akan berubah sesuai dengan perubahan yang dilakukan.
