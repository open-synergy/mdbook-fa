# Settlement dengan Customer Invoice

## A. INPUT

* Data *credit note* yang akan di-*settlement* harus memiliki status **Open**.

![](../../img/credit-note/status-open.png)

* Data *customer invoice* yang ingin di-*settle* sudah dibuat

## B. LANGKAH KERJA

Buat dan proses [Sale Refund Settlement](../sale-refund-settlement.md) untuk melakukan settlement dengan *customer invoice*.

## C. OUTPUT

* Nilai **[Balance](./penjelasan.md#field-balance)** akan bertambah sejumlah settlement yang dilakukan.
* Status dari *credit note* akan berubah menjadi **Paid**. Apabila nilai **[Balance](./penjelasan.md#field-balance)** sama dengan nilai **[Total](./penjelasan.md#field-total)**

![](../../img/credit-note/status-paid.png)
