# Memodifikasi Cheque Payment

## A. INPUT

* Data cheque payment yang akan dimodifikasi harus memiliki status **Draft**.

![](../../img/cheque-payment/status-draft.png)

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Bank & Cash -> Cheque Payment**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data cheque payment yang akan dimodifikasi. Abaikan jika data sudah dibuka.
3. Klik tombol **Edit** pada bagian atas-kiri form.

![](../../img/cheque-payment/tombol-edit.png)

4. Ubah **[# Cheque](./penjelasan.md#field-name)** sesuai dengan nomor cek. Wajib diisi.
5. Ubah **[Company](./penjelasan.md#field-company)** jika dibutuhkan. Hanya terlihat pada implementasi multi-company. Harus diisi.
6. Isi dan sesuaikan **[Date](./penjelasan.md#field-date)**. Harus diisi.
7. Isi dan sesuaikan **[Date Issue](./penjelasan.md#field-date-issue)**. Harus diisi.
8. Biarkan isian **[Period](./penjelasan.md#field-period)**.
9. Pilih dan sesuaikan **[Journal](./penjelasan.md#field-journal)**. Harus diisi.
10. Pilih dan sesuaikan **[Partner](./penjelasan.md#field-partner)** Harus diisi.
11. Isi dan sesuaikan **[Payee](./penjelasan.md#field-payee)**. Harus diisi.
12. Pilih dan sesuaikan **[Source Bank Account](./penjelasan.md#field-source-account)**. Harus diisi.
13. Isi dan sesuaikan **[Total Voucher](./penjelasan.md#field-total-voucher)**. Harus diisi.
14. Isi dan sesuaikan **[Exchange Rate](./penjelasan.md#field-exchange-rate)**. Harus diisi.
15. <a name="l15">[Import](./membuat-detail-import.md)/[Tambah](./membuat-detail-manual.md)/[Modifikasi](./line-modifikasi.md)/[Hapus](./line-hapus.md) **Voucher Lines**</a>. Ulangi langkah ini sampai **Voucher Lines** sesuai dengan keinginan.
16. <a name="langkah-16">Isi</a> **[Write-Off Account](./penjelasan.md#field-writeoff-account)** apabila nilai **[Amount Diff](./penjelasan.md#field-amount-diff)** tidak sama dengan 0.0 dan nominal tersebut ingin di-*write-off* ke akun tertentu.
17. Klik tombol **Save** pada bagian atas-kiri form.

![](../../img/cheque-payment/tombol-edit-save.png)

## C. OUTPUT

* Data cheque payment akan berubah sesuai dengan perubahan yang dilakukan.
