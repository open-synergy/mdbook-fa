# Menerima Pembayaran Supplier Invoice

## A. INPUT

* Data *supplier invoice* yang akan diterima pembayarannya harus memiliki status **Open**.

![](../../img/supplier-invoice/status-open.png)

## B. LANGKAH KERJA

*Supplier invoice* dapat diterima pembayarannya dengan menggunakan salah satu fitur berikut:

* [Bank Payment](../bank-payment.md)
* [Cash Payment](../cash-payment.md)
* [Giro Payment](../giro-payment.md)
* [Cheque Payment](../cheque-payment.md)

Lakukan prosedur yang sesuai dengan pembayaran yang terjadi.

## C. OUTPUT

* Nilai **[Balance](./penjelasan.md#field-balance)** akan bertambah sejumlah pembayaran yang dilakukan.
* Status dari *supplier invoice* akan berubah menjadi **Paid**. Apabila nilai **[Balance](./penjelasan.md#field-balance)** sama dengan nilai **[Total](./penjelasan.md#field-total)**

![](../../img/supplier-invoice/status-paid.png)
