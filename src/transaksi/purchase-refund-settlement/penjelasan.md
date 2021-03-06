# Penjelasan

Informasi pada *Purchase Refund Settlement* dibagi menjadi beberapa area, diantaranya:

* [Header](#bagian-header)
* [Debit Lines](#bagian-debit-line)
* [Credit Lines](#bagian-credit-line)
* [Footer](#bagian-footer)
* [Tab Notes](#tab-notes)
* [Tab Accounting Information](#tab-accounting-information)
* [Tab Log](#tab-log)
* [Tab Policy](#tab-policy)

### <a name="bagian-header">HEADER</a>

![](../../img/purchase-refund-settlement/penjelasan-header.png)

#### <a name="field-name"># Purchase Refund Settlement</a>

Nomor dokumen *purchase refund settlement*

#### <a name="field-company">Company</a>

Perusahaan pemilik dokumen *purchase refund settlement*

#### <a name="field-ou">Default Operating Unit</a>

Operating unit pemilik dokumen. Secara default terisi sesuai dengan operating unit pada
Journal.

#### <a name="field-date">Date</a>

Tanggal transaksi

#### <a name="field-period">Period</a>

Periode akuntansi terjadinya transaksi

#### <a name="field-journal">Journal</a>

Buku jurnal yang akan digunakan untuk mencatat penjurnalan *purchase refund settlement*.

#### <a name="field-partner">Partner</a>

Pihak yang memberikan *debit note*. Field ini akan menentukan *partner* yang digunakan pada penjurnalan *purchase refund settlement*. *Partner* yang digunakan pada penjurnalan *purchase refund settlement* adalah *commercial partner* dari isian **Partner**. Diisi apabila *settlement* terkait hanya dengan 1 pihak pemberi. Jangan diisi apabila *settlement* terkait dengan lebih dari 1 pihak pemberi.

#### <a name="field-description">Description</a>

Keterangan utama transaksi.

### <a name="bagian-footer">FOOTER</a>

![](../../img/purchase-refund-settlement/penjelasan-footer.png)

#### <a name="field-debit">Debit</a>

Total *supplier invoice* yang akan di-*settle*

#### <a name="field-debit">Credit</a>

Total *debit note* yang akan di-*settle*

#### <a name="field-exchange-rate">Exchange Rate</a>

Spot rate kurs

### <a name="bagian-debit-line">DEBIT LINES</a>

Tampilan tree:

![](../../img/purchase-refund-settlement/penjelasan-debit-line-tree.png)

Tampilan form:

![](../../img/purchase-refund-settlement/penjelasan-detail.png)

#### <a name="field-debit-line-partner">Partner</a>

Pihak yang mempunyai utang dagang. Apabila *purchase refund settlement* terkait hanya dengan satu pihak, maka isian ini harus sama dengan isian **Partner** pada bagian header.

#### <a name="field-debit-line-move-line">Move Line</a>

Journal item *supplier invoice* yang akan direkonsiliasi

#### <a name="field-debit-line-account">Account</a>

Akun yang akan didebit pada penjurnalan *purchase refund settlement*

#### <a name="field-debit-line-aa">Analytic Account</a>

Kode biaya

#### <a name="field-debit-line-amount">Amount</a>

Jumlah *supplier invoice* yang akan di-*settle*.

#### <a name="field-debit-line-amount-move-date">Amount In Company Currency At Move Date</a>

Jumlah detail *supplier invoice* yang akan di-*settle* sesuai dengan mata uang perusahaan dengan kurs tanggal **Move Line**


#### <a name="field-debit-line-amount-voucher-date">Amount In Company Currency At Voucher Date</a>

Jumlah *supplier invoice* yang akan di-*settle* sesuai dengan mata uang perusahaan dengan kurs sesuai dengan spot rate. Nilai ini akan didebit pada penjurnalan *purchase refund settlement* jika bernilai positif. Nilai ini akan dikredit jika bernilai negatif.

#### <a name="field-debit-line-diff">Diff Amount In Company Currency</a>

Selisih antara **Amount In Company Currency At Move Date** dan **Amount In Company Currency At Voucher Date**. Nilai ini akan dijurnal sebagai selisih kurs jika > 0.0

#### <a name="field-debit-line-description">Description</a>

Keterangan **Debit Lines**.

### <a name="bagian-credit-line">CREDIT LINES</a>

Tampilan tree:

![](../../img/purchase-refund-settlement/penjelasan-credit-line-tree.png)

Tampilan form:

![](../../img/purchase-refund-settlement/penjelasan-detail.png)

#### <a name="field-credit-line-partner">Partner</a>

Pihak yang memberikan *debit note*. Apabila isian **Partner** pada bagian header diisi, maka isian ini harus sama dengan isian **Partner** pada bagian header.

#### <a name="field-credit-line-move-line">Move Line</a>

Journal item *debit note* yang akan direkonsiliasi

#### <a name="field-credit-line-account">Account</a>

Akun yang akan dikredit pada penjurnalan *purchase refund settlement*

#### <a name="field-credit-line-aa">Analytic Account</a>

Kode biaya

#### <a name="field-credit-line-amount">Amount</a>

Jumlah *debit note* yang akan di-*settle*.

#### <a name="field-credit-line-amount-move-date">Amount In Company Currency At Move Date</a>

Jumlah *debit note* yang akan di-*settle* sesuai dengan mata uang perusahaan dengan kurs tanggal **Move Line**


#### <a name="field-credit-line-amount-voucher-date">Amount In Company Currency At Voucher Date</a>

Jumlah *debit note* yang akan di-*settle* sesuai dengan mata uang perusahaan dengan kurs sesuai dengan spot rate. Nilai ini akan dikredit pada penjurnalan *purchase refund settlement* jika bernilai positif. Nilai ini akan didebit jika bernilai negatif.

#### <a name="field-credit-line-diff">Diff Amount In Company Currency</a>

Selisih antara **Amount In Company Currency At Move Date** dan **Amount In Company Currency At Voucher Date**. Nilai ini akan dijurnal sebagai selisih kurs jika > 0.0

#### <a name="field-credit-line-description">Description</a>

Keterangan **Credit Lines**.

### <a name="tab-notes">TAB NOTES</a>

![](../../img/purchase-refund-settlement/tab-notes.png)

#### <a name="field-note">Note</a>

Catatan tambahan

### <a name="tab-accounting-information">TAB ACCOUNTING INFORMATION</a>

![](../../img/purchase-refund-settlement/tab-accounting-information.png)

#### <a name="field-accounting-entry">Accounting Entry</a>

Penjurnalan (journal entry) yang dihasilkan ketika *purchase refund settlement* diposting

### <a name="tab-log">TAB LOG</a>

![](../../img/purchase-refund-settlement/tab-log.png)

### <a name="tab-log">TAB POLICY</a>

![](../../img/purchase-refund-settlement/tab-policy.png)
