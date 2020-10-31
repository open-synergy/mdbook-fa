# Membatalkan Invoice Settlement

## A. INPUT

* Data *invoice settlement* yang akan dibatalkan dapat memiliki status **Draft**, atau **Waiting for Approval**, atau **Ready To Process**, atau **Proforma**, atau **Posted**

![](../../img/invoice-settlement/status-draft-posted.png)

* User yang akan membatalkan harus memiliki akses untuk membatalkan *invoice settlement*.

## B. LANGKAH KERJA

1. Buka menu **Accounting -> Settlement -> Invoice Settlement**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data *invoice settlement* yang akan dibatalkan. Abaikan jika data sudah dibuka.
3. Klik tombol **Cancel** pada bagian atas-kiri form.

![](../../img/invoice-settlement/tombol-cancel.png)

4. Klik tombol **Ok** pada *pop-up* konfirmasi pembatalan yang muncul.

![](../../img/invoice-settlement/pop-up-konfirmasi-cancel.png)

5. Pilih **Reason** pada *pop-up* **Cancellation Reason** yang muncul.

![](../../img/invoice-settlement/pilihan-cancellation-reason.png)

6. Klik tombol **Confirm** pada *pop-up* Cancellation Reason.

![](../../img/invoice-settlement/tombol-confirm-cancel-reason.png)

7. Klik tombol **Ok** pada *pop-up* konfirmasi pembatalan yang muncul.

![](../../img/invoice-settlement/tombol-ok-confirm-cancel.png)

## C. OUTPUT

* Status dari *invoice settlement* akan berubah menjadi **Cancel**

![](../../img/invoice-settlement/status-cancel.png)

* Penjurnalan yang dihasilkan akan dihapus.
