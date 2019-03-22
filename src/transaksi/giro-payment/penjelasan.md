# Penjelasan

Informasi pada Giro Payment dibagi menjadi beberapa area, diantaranya:

* [Header](#bagian-header)
* [Voucher Item](#bagian-detail)
* [Footer](#bagian-footer)
* [Tab Notes](#tab-notes)
* [Tab Accounting Information](#tab-accounting-information)
* [Tab Log](#tab-log)
* [Tab Policy](#tab-policy)

### <a name="bagian-header">HEADER</a>

![](../../img/giro-payment/penjelasan-header.png)

#### <a name="field-name"># Giro Payment</a>

Nomor giro yang dikeluarkan

#### <a name="field-company">Company</a>

Perusahaan pemilik dokumen giro payment

#### <a name="field-ou">Default Operating Unit</a>

Operating unit pemilik dokumen. Secara default terisi sesuai dengan operating unit pada Journal.

#### <a name="field-date">Date</a>

Tanggal diberikannya giro

#### <a name="field-date-issue">Date Issue</a>

Tanggal dikeluarkannya giro

#### <a name="field-due">Date Due</a>

Tanggal giro dapat dicairkan

#### <a name="field-period">Period</a>

Periode akuntansi dikeluarkannya giro

#### <a name="field-journal">Journal</a>

Buku jurnal yang akan digunakan untuk mencatat penjurnalan giro payment.


#### <a name="field-partner">Partner</a>

Pihak yang menerima giro. Field ini akan menentukan *partner* yang digunakan pada penjurnalan
giro payment. *Partner* yang digunakan pada penjurnalan giro payment adalah *commercial partner*
dari isian **Partner**. Diisi apabila pengeluaran terkait hanya dengan 1 pihak penerima. Jangan diisi
apabila pengeluaran terkait dengan lebih dari 1 pihak penerima.

#### <a name="field-source-account">Source Bank Account</a>

Rekening bank yang mengeluarkan giro

#### <a name="field-destination-account">Destination Bank Account</a>

Rekening bank yang menerima dana

#### <a name="field-description">Description</a>

Keterangan utama transaksi. Isi field ini akan digunakan sebagai deskripsi penjurnalan giro payment di
sisi kredit. Akan muncul di *general ledger*

### <a name="bagian-footer">FOOTER</a>

![](../../img/giro-payment/penjelasan-footer.png)

#### <a name="field-total-voucher">Total Voucher</a>

Total penerimaan dalam mata uang yang sesuai dengan buku jurnal

#### <a name="field-exchange-rate">Exchange Rate</a>

Spot rate kurs

#### <a name="field-total-voucher-company-currency">Total Voucher In Company Currency</a>

Total penerimaan dalam mata uang perusahaan. Nilai ini akan didebit pada penjurnalan
giro payment.

### <a name="bagian-detail">DETAIL</a>

![](../../img/giro-payment/penjelasan-detail.png)

#### <a name="field-detail-partner">Partner</a>

Pihak penerima. Apabila giro payment terkait hanya dengan satu pihak penerima, maka isian
ini harus sama dengan isian **Partner** pada bagian header.

#### <a name="field-detail-move-line">Move Line</a>

Journal item yang akan direkonsiliasi

#### <a name="field-detail-account">Account</a>

Akun yang akan didebit pada penjurnalan giro payment

#### <a name="field-detail-aa">Analytic Account</a>

Kode biaya

#### <a name="field-detail-amount">Amount</a>

Jumlah detail penerimaan.

#### <a name="field-detail-amount-move-date">Amount In Company Currency At Move Date</a>

Jumlah detail penerimaan sesuai dengan mata uang perusahaan dengan kurs tanggal **Move Line**


#### <a name="field-detail-amount-voucher-date">Amount In Company Currency At Voucher Date</a>

Jumlah detail penerimaan sesuai dengan mata uang perusahaan dengan kurs sesuai dengan spot rate. Nilai ini akan didebit pada penjurnalan giro payment jika bernilai positif. Nilai ini akan dikredit jika bernilai negatif.

#### <a name="field-detail-diff">Diff Amount In Company Currency</a>

Selisih antara **Amount In Company Currency At Move Date** dan **Amount In Company Currency At Voucher Date**. Nilai ini akan dijurnal sebagai selisih kurs jika > 0.0

#### <a name="field-detail-description">Description</a>

Keterangan **Voucher Detail**.

### <a name="tab-notes">TAB NOTES</a>

![](../../img/giro-payment/tab-notes.png)

#### <a name="field-note">Note</a>

Catatan tambahan

### <a name="tab-accounting-information">TAB ACCOUNTING INFORMATION</a>

![](../../img/giro-payment/tab-accounting-information.png)

#### <a name="field-accounting-entry">Accounting Entry</a>

Penjurnalan (journal entry) yang dihasilkan ketika giro payment diposting

### <a name="tab-log">TAB LOG</a>

![](../../img/giro-payment/tab-log.png)

### <a name="tab-log">TAB POLICY</a>

![](../../img/giro-payment/tab-policy.png)
