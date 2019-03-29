# Membatalkan Supplier Invoice

## A. INPUT

* Data *supplier invoice* yang akan divalidasi harus memiliki status **Draft**. *Supplier invoice* dengan status **Open** juga dapat dibatalkan selama *supplier invoice* belum ada pembayaran.

![](../../img/supplier-invoice/status-draft.png)

![](../../img/supplier-invoice/status-open.png)

* User yang akan membatalkan harus memiliki akses untuk membatalkan *supplier invoice*.

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Supplier -> Supplier Invoice**. Abaikan jika sudah berada
pada menu yang dimaksud.
2. Buka data *supplier invoice* yang akan dibatalkan. Abaikan jika data sudah dibuka.
3. Klik tombol **Cancel Invoice** pada bagian atas-kiri form.

![](../../img/supplier-invoice/tombol-cancel.png)

## C. OUTPUT

* Status dari *supplier invoice* akan berubah menjadi **Cancelled**

![](../../img/supplier-invoice/status-cancel.png)
