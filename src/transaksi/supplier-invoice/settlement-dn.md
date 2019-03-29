# Settlement Dengan Debit Note

## A. INPUT

* Data *supplier invoice* yang akan di-*settlement* harus memiliki status **Open**.

![](../../img/supplier-invoice/status-open.png)

* Data *debit note* sudah dibuat

## B. LANGKAH KERJA

Buat dan proses [Purchase Refund Settlement](../purchase-refund-settlement.md) untuk melakukan settlement dengan *debit note*.

## C. OUTPUT

* Nilai **[Balance](./penjelasan.md#field-balance)** akan bertambah sejumlah settlement yang dilakukan.
* Status dari *supplier invoice* akan berubah menjadi **Paid**. Apabila nilai **[Balance](./penjelasan.md#field-balance)** sama dengan nilai **[Total](./penjelasan.md#field-total)**

![](../../img/supplier-invoice/status-paid.png)
