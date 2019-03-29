# Settlement Dengan Uang Muka Penjualan

## A. INPUT

* Data *customer invoice* yang akan di-*settlement* harus memiliki status **Open**.

![](../../img/customer-invoice/status-open.png)

## B. LANGKAH KERJA

Buat dan proses [Sale Advance Settlement](../sale-advance-settlement.md) untuk melakukan settlement dengan uang muka penjualan.

## C. OUTPUT

* Nilai **[Balance](./penjelasan.md#field-balance)** akan bertambah sejumlah settlement yang dilakukan.
* Status dari *customer invoice* akan berubah menjadi **Paid**. Apabila nilai **[Balance](./penjelasan.md#field-balance)** sama dengan nilai **[Total](./penjelasan.md#field-total)**

![](../../img/customer-invoice/status-paid.png)
