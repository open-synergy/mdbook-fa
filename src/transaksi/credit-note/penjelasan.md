# Penjelasan

* [Header](#bagian-header)
* [Tab Invoice Line](#bagian-invoice-line)
* [Tab Other Info](#bagian-other-info)
* [Tab Payments](#bagian-payment)
* [Tab Policy](#bagian-policy)
* [Tab Pickings](#bagian-picking)

### <a name="bagian-header">HEADER</a>

![](../../img/credit-note/penjelasan-header.png)

#### <a name="field-partner">Customer</a>

Konsumen

#### <a name="field-fiscal-position">Fiscal Position</a>

#TODO

#### <a name="field-invoice-date">Invoice Date</a>

Tanggal terbitnya invoice. Tanggal ini akan menjadi tanggal penjurnalan *credit note*

#### <a name="field-force-number">Force Number</a>

Nomor invoice. Biarkan kosong agar penomeran invoice dibuat secara otomatis.

#### <a name="field-ou">Operating Unit</a>

Operating unit

#### <a name="field-journal">Journal</a>

Buku jurnal yang digunakan untuk mencatat penjurnalan *credit note*

#### <a name="field-account">Account</a>

Akun piutang yang akan digunakan dalam penjurnalan *credit note*. Secara otomatis akan mengambil nilai **_Receivable Account_** pada **_Customer_**.

#### <a name="field-sale-type">Sale Type</a>

Tipe penjualan

#### <a name="field-currency">Currency</a>

Mata uang invoice. Akan mengikuti nilai **_Currency_** pada **_Journal_**.

### <a name="bagian-invoice-line">TAB INVOICE LINE</a>

![](../../img/credit-note/penjelasan-tab-invoice-line.png)

#### <a name="field-product">Product</a>

Produk yang dijual.

#### <a name="field-description">Description</a>

Deskripsi item yang dijual. Secara default akan bernilai sesuai dengan nama **_Product_**.

#### <a name="field-account-line">Account</a>

Akun pendapatan yang akan digunakan dalam penjurnalan *credit note*.

#### <a name="field-aa">Analytic Account</a>

Kode biaya

#### <a name="field-asset">Asset</a>

#TODO

#### <a name="field-start-date">Start Date</a>

Tanggal mulai masa manfaat. Diisi apabila isian **_Account_** merupakan akun pendapatan diterima dimuka.

#### <a name="field-end-date">End Date</a>

Tanggal selesai masa manfaat. Diisi apabila isian **_Account_** merupakan akun pendapatan diterima dimuka.

#### <a name="field-qty">Quantity</a>

Kuantitas item yang dijual

#### <a name="field-uom">Unit of Measure</a>

Satuan item yang dijual

#### <a name="field-asset">Unit Price</a>

Harga satuan item yang dijual

#### <a name="field-discount">Discount</a>

Diskon penjualan. Ditulis dalam persen.

#### <a name="field-taxes">Taxes</a>

Pajak-pajak yang dikenakan kepada item yang dijual.

#### <a name="field-amount-gross">Amount Gross</a>

Subtotal sebelum pajak

#### <a name="field-subtotal">Subtotal</a>

Subtotal penjualan sebelum pajak

#### <a name="field-tax">Tax</a>

Total pajak yang dikenakan

#### <a name="field-total">Total</a>

**_Subtotal_** + **_Tax_**

#### <a name="field-balance">Balance</a>

Sisa invoice yang belum terbayar.

#### <a name="field-payment-term">Payment Term</a>

Term jatuh tempo pembayaran

#### <a name="field-info">Additional Information</a>

Informasi tambahan

### <a name="bagian-other-info">TAB OTHER INFO</a>

![](../../img/credit-note/penjelasan-tab-other-info.png)

#### <a name="field-salesperson">Salesperson</a>

Karyawan yang bertanggung jawab merilis invoice

#### <a name="field-sales-team">Sales Team</a>

Tim penjualan yang melakukan invoice

#### <a name="field-bank-acc">Bank Account</a>

Rekening tujuan penerimaan pembayaran

#### <a name="field-due-date">Due Date</a>

Tanggal jatuh tempo. Jika isian **_Payment Term_** diisi, maka nilai **_Due Date_** akan mengikuti ketentuan **_Payment Term_**.

#### <a name="field-source-document">Source Document</a>

Dokumen sumber

#### <a name="field-reference">Reference/Description</a>

Deskripi singkat terkait invoice. Isian ini akan menjadi keterangan pada *general ledger*.

#### <a name="field-accrual-journal-entry">Accrual Journal Entry</a>

#TODO

#### <a name="field-journal-entry">Journal Entry</a>

Penjurnalan yang dihasilkan oleh *credit note*

#### <a name="field-tax-description">Tax Description</a>

Keterangan item pajak

#### <a name="field-tax-account">Tax Account</a>

Kode akun pajak

#### <a name="field-base">Base</a>

Dasar penggenaan pajak

#### <a name="field-tax-amount">Amount</a>

Pajak

### <a name="bagian-payment">TAB PAYMENT</a>

![](../../img/credit-note/penjelasan-tab-payment.png)

Tabel payment akan berisi *journal item* yang merekonsiliasi *credit note*

### <a name="bagian-policy">TAB POLICY</a>

![](../../img/credit-note/penjelasan-tab-policy.png)

### <a name="bagian-picking">TAB PICKING</a>

![](../../img/credit-note/penjelasan-tab-picking.png)

Tabel picking akan berisi data *picking* yang mengotomasi pembuatan *credit note*
