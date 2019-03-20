# Penjelasan

Informasi pada Bank Receipt dibagi menjadi beberapa area, diantaranya:

* [Header](#bagian-header)
* [Voucher Item](#bagian-detail)
* [Footer](#bagian-footer)
* Tab Notes
* Tab Accounting Information
* Tab Log
* Tab Policy

### <a name="bagian-header">HEADER</a>

![](../../img/bank-receipt/penjelasan-header.png)

#### <a name="field-name"># Bank Receipt</a>

Nomor dokumen bank receipt

#### <a name="field-company">Company</a>

Perusahaan pemilik dokumen bank receipt

#### <a name="field-ou">Default Operating Unit</a>

Operating unit pemilik dokumen. Secara default terisi sesuai dengan operating unit pada
Journal.

#### <a name="field-date">Date</a>

Tanggal transaksi

#### <a name="field-period">Period</a>

Periode akuntansi terjadinya transaksi

#### <a name="field-journal">Journal</a>

Buku jurnal yang akan digunakan untuk mencatat penjurnalan bank receipt.

#### Payment Mode

Metode penerimaan. Contoh: Pemindahbukuan, EDC, dll.

#### Partner

Pihak penerima. Field ini akan menentukan *partner* yang digunakan pada penjurnalan
bank receipt. *Partner* yang digunakan pada penjurnalan bank receipt adalah *commercial partner*
dari isian **Partner**. Diisi apabila penerimaan terkait hanya dengan 1 pihak penerima. Jangan diisi
apabila penerimaan terkait dengan lebih dari 1 pihak penerima.

#### Description

Keterangan utama transaksi. Isi field ini akan digunakan sebagai deskripsi penjurnalan bank receipt di
sisi debit. Akan muncul di *general ledger*

#### Note

Catatan tambahan

### <a name="bagian-footer">FOOTER</a>

![](../../img/bank-receipt/penjelasan-footer.png)

#### Total Voucher

Total penerimaan dalam mata uang yang sesuai dengan buku jurnal

#### Exchange Rate

Spot rate kurs

#### Total Voucher In Company Currency

Total penerimaan dalam mata uang perusahaan. Nilai ini akan didebit pada penjurnalan
bank receipt.

### <a name="bagian-detail">DETAIL</a>

![](../../img/bank-receipt/penjelasan-detail.png)

#### Partner

Pihak penerima. Apabila bank receipt terkait hanya dengan satu pihak penerima, maka isian
ini harus sama dengan isian **Partner** pada bagian header.

#### Move Line

Journal item yang akan direkonsiliasi

#### Account

Akun yang akan dikredit pada penjurnalan bank receipt

#### Analytic Account

Kode biaya

#### Amount

Jumlah detail penerimaan.

#### Amount In Company Currency At Move Date

Jumlah detail penerimaan sesuai dengan mata uang perusahaan dengan kurs tanggal **Move Line**


#### Amount In Company Currency At Voucher Date

Jumlah detail penerimaan sesuai dengan mata uang perusahaan dengan kurs sesuai dengan spot rate. Nilai ini akan dikredit pada penjurnalan bank receipt jika bernilai positif. Nilai ini akan didebit jika bernilai negatif.

#### Diff Amount In Company Currency

Selisih antara **Amount In Company Currency At Move Date** dan **Amount In Company Currency At Voucher Date**. Nilai ini akan dijurnal sebagai selisih kurs jika > 0.0

#### Description

Keterangan **Voucher Detail**.
