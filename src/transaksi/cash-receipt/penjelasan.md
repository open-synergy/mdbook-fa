# Penjelasan

Informasi pada Cash Receipt dibagi menjadi beberapa area, diantaranya:

* [Header](#bagian-header)
* [Voucher Item](#bagian-detail)
* [Footer](#bagian-footer)
* [Tab Notes](#tab-notes)
* [Tab Accounting Information](#tab-accounting-information)
* [Tab Log](#tab-log)
* [Tab Policy](#tab-policy)

### <a name="bagian-header">HEADER</a>

![](../../img/cash-receipt/penjelasan-header.png)

#### <a name="field-name"># Cash Receipt</a>

Nomor dokumen cash receipt

#### <a name="field-company">Company</a>

Perusahaan pemilik dokumen cash receipt

#### <a name="field-ou">Default Operating Unit</a>

Operating unit pemilik dokumen. Secara default terisi sesuai dengan operating unit pada
Journal.

#### <a name="field-date">Date</a>

Tanggal transaksi

#### <a name="field-period">Period</a>

Periode akuntansi terjadinya transaksi

#### <a name="field-journal">Journal</a>

Buku jurnal yang akan digunakan untuk mencatat penjurnalan cash receipt.

#### <a name="field-partner">Partner</a>

Pihak yang memberikan. Field ini akan menentukan *partner* yang digunakan pada penjurnalan
cash receipt. *Partner* yang digunakan pada penjurnalan cash receipt adalah *commercial partner*
dari isian **Partner**. Diisi apabila penerimaan terkait hanya dengan 1 pihak pemberi. Jangan diisi
apabila penerimaan terkait dengan lebih dari 1 pihak pemberi.

#### <a name="field-description">Description</a>

Keterangan utama transaksi. Isi field ini akan digunakan sebagai deskripsi penjurnalan cash receipt di
sisi debit. Akan muncul di *general ledger*

### <a name="bagian-footer">FOOTER</a>

![](../../img/cash-receipt/penjelasan-footer.png)

#### <a name="field-total-voucher">Total Voucher</a>

Total penerimaan dalam mata uang yang sesuai dengan buku jurnal

#### <a name="field-exchange-rate">Exchange Rate</a>

Spot rate kurs

#### <a name="field-total-voucher-company-currency">Total Voucher In Company Currency</a>

Total penerimaan dalam mata uang perusahaan. Nilai ini akan didebit pada penjurnalan
cash receipt.

### <a name="bagian-detail">DETAIL</a>

![](../../img/cash-receipt/penjelasan-detail.png)

#### <a name="field-detail-partner">Partner</a>

Pihak penerima. Apabila cash receipt terkait hanya dengan satu pihak penerima, maka isian
ini harus sama dengan isian **Partner** pada bagian header.

#### <a name="field-detail-move-line">Move Line</a>

Journal item yang akan direkonsiliasi

#### <a name="field-detail-account">Account</a>

Akun yang akan dikredit pada penjurnalan cash receipt

#### <a name="field-detail-aa">Analytic Account</a>

Kode biaya

#### <a name="field-detail-amount">Amount</a>

Jumlah detail penerimaan.

#### <a name="field-detail-amount-move-date">Amount In Company Currency At Move Date</a>

Jumlah detail penerimaan sesuai dengan mata uang perusahaan dengan kurs tanggal **Move Line**


#### <a name="field-detail-amount-voucher-date">Amount In Company Currency At Voucher Date</a>

Jumlah detail penerimaan sesuai dengan mata uang perusahaan dengan kurs sesuai dengan spot rate. Nilai ini akan dikredit pada penjurnalan cash receipt jika bernilai positif. Nilai ini akan didebit jika bernilai negatif.

#### <a name="field-detail-diff">Diff Amount In Company Currency</a>

Selisih antara **Amount In Company Currency At Move Date** dan **Amount In Company Currency At Voucher Date**. Nilai ini akan dijurnal sebagai selisih kurs jika > 0.0

#### <a name="field-detail-description">Description</a>

Keterangan **Voucher Detail**.

### <a name="tab-notes">TAB NOTES</a>

![](../../img/cash-receipt/tab-notes.png)

#### <a name="field-note">Note</a>

Catatan tambahan

### <a name="tab-accounting-information">TAB ACCOUNTING INFORMATION</a>

![](../../img/cash-receipt/tab-accounting-information.png)

#### <a name="field-accounting-entry">Accounting Entry</a>

Penjurnalan (journal entry) yang dihasilkan ketika cash receipt diposting

### <a name="tab-log">TAB LOG</a>

![](../../img/cash-receipt/tab-log.png)

### <a name="tab-log">TAB POLICY</a>

![](../../img/cash-receipt/tab-policy.png)
