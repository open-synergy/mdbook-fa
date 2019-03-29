# Membayar Via Tunai atau Bank

## A. INPUT

* Data *debit note* yang akan diterima pembayarannya harus memiliki status **Open**.

![](../../img/debit-note/status-open.png)


## B. LANGKAH KERJA

*Debit note* dapat diterima pembayarannya dengan menggunakan salah satu fitur berikut:

* [Bank Receipt](../bank-receipt.md)
* [Cash Receipt](../cash-receipt.md)
* [Giro Receipt](../giro-receipt.md)
* [Cheque Receipt](../cheque-receipt.md)

Lakukan prosedur yang sesuai dengan penerimaan pembayaran yang terjadi.

## C. OUTPUT

* Nilai **[Balance](./penjelasan.md#field-balance)** akan bertambah sejumlah pembayaran yang dilakukan.
* Status dari *debit note* akan berubah menjadi **Paid**. Apabila nilai **[Balance](./penjelasan.md#field-balance)** sama dengan nilai **[Total](./penjelasan.md#field-total)**

![](../../img/debit-note/status-paid.png)
