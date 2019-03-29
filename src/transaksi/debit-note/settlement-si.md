# Settlement dengan Supplier Invoice

## A. INPUT

* Data *debit note* yang akan di-*settlement* harus memiliki status **Open**.

![](../../img/debit-note/status-open.png)

* Data *supplier invoice* yang ingin di-*settle* sudah dibuat

## B. LANGKAH KERJA

Buat dan proses [Purchase Refund Settlement](../purchase-refund-settlement.md) untuk melakukan settlement dengan *supplier invoice*.

## C. OUTPUT

* Nilai **[Balance](./penjelasan.md#field-balance)** akan bertambah sejumlah settlement yang dilakukan.
* Status dari *debit note* akan berubah menjadi **Paid**. Apabila nilai **[Balance](./penjelasan.md#field-balance)** sama dengan nilai **[Total](./penjelasan.md#field-total)**

![](../../img/debit-note/status-paid.png)
