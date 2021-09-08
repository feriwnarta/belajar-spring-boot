#  belajar sping boot lewat tutorial youtube, dengan case projek invoice management #

akan menggunakan invoice dengan berbagai jenis pembayaran :

* Virtual Account

      * BCA Virtual Account
      * BNI Virtual Account
      * CIMB NIAGA Virtual Account

* e-wallet

    * OVO
    * GOPAY
    * LINK AJA

* QR Payment

    * QRis#  belajar sping boot lewat tutorial youtube, dengan case projek invoice management #

akan menggunakan invoice dengan berbagai jenis pembayaran :

* Virtual Account

      * BCA Virtual Account
      * BNI Virtual Account
      * CIMB NIAGA Virtual Account

* e-wallet

    * OVO
    * GOPAY
    * LINK AJA

* QR Payment

    * QRis

# Setup Database #

'menjalankan postgree di docker'

docker run --rm \
--name invoice-db \
-e POSTGRES_DB=invoicedb \
-e POSTGRES_USER=invoice \
-e POSTGRES_PASSWORD=hYfeMEFkOJ \
-e PGDATA=/var/lib/postgresql/data/pgdata \
-v "$PWD/invoicedb-data:/var/lib/postgresql/data" \
-p 5432:5432 \
postgres:13