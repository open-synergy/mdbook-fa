# Memodifikasi Purchase Advance Settlement

## A. INPUT

* Data purchase advance settlement yang akan dimodifikasi harus memiliki status **Draft**.

![](../../img/purchase-advance-settlement/status-draft.png)

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Settlement -> Purchase Advance Settlement**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data purchase advance settlement yang akan dimodifikasi. Abaikan jika data sudah dibuka.
3. Klik tombol **Edit** pada bagian atas-kiri form.

![](../../img/purchase-advance-settlement/tombol-edit.png)

4. Ubah dan sesuaikan **[# Purchase Advance Settlement](./penjelasan.md#field-name)** dengan penomeran yang dikehendaki.
5. Ubah dan sesuaikan **[Company](./penjelasan.md#field-company)** jika dibutuhkan. Hanya terlihat pada implementasi multi-company. Harus diisi.
6. Isi dan sesuaikan **[Date](./penjelasan.md#field-date)**. Harus diisi.
7. Biarkan isian **[Period](./penjelasan.md#field-period)**.
8. Pilih **[Journal](./penjelasan.md#field-journal)**. Harus diisi.
9. Pilih **[Partner](./penjelasan.md#field-partner)** Tidak harus diisi.
10. Isi dan sesuaikan **[Exchange Rate](./penjelasan.md#field-exchange-rate)**. Harus diisi.
11. <a name="langkah-11">Untuk</a> setiap *credit note* yang akan di-*settle*, [import](./import-debit-line.md)/[modifikasi](./memodifikasi-debit-line.md)/[hapus](./menghapus-debit-line.md) debit lines. Ulangi langkah ini sampai **Debit Lines** sesuai dengan keinginan.
12. <a name="langkah-12">Untuk</a> setiap *customer invoice* yang akan di-*settle*, [import](./import-credit-line.md)/[modifikasi](./memodifikasi-credit-line.md)/[hapus](./menghapus-credit-line.md) credit lines. Ulangi langkah ini sampai **Credit Lines** sesuai dengan keinginan.
13. <a name="langkah-13">Klik</a> tombol **Save** pada bagian atas-kiri form.

![](../../img/purchase-advance-settlement/tombol-edit-save.png)

## C. OUTPUT

* Data Purchase Advance Settlement akan berubah sesuai dengan perubahan yang dilakukan.
