# Settlement Dengan Uang Muka Pembelian

## A. INPUT

* Data *supplier invoice* yang akan di-*settlement* harus memiliki status **Open**.

![](../../img/supplier-invoice/status-open.png)

* Data pembayaran uang muka pembelian sudah dibuat

## B. LANGKAH KERJA

Buat dan proses [Purchase Advance Settlement](../purchase-advance-settlement.md) untuk melakukan settlement dengan uang muka pembelian.

## C. OUTPUT

* Nilai **[Balance](./penjelasan.md#field-balance)** akan bertambah sejumlah settlement yang dilakukan.
* Status dari *supplier invoice* akan berubah menjadi **Paid**. Apabila nilai **[Balance](./penjelasan.md#field-balance)** sama dengan nilai **[Total](./penjelasan.md#field-total)**

![](../../img/supplier-invoice/status-paid.png)
