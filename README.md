Sebagai seorang Big Data Analytics Intern di Kimia Farma, tugas Anda akan mencakup serangkaian tantangan yang memerlukan pemahaman mendalam tentang data dan kemampuan analisis. Salah satu proyek utama Anda adalah mengevaluasi kinerja bisnis Kimia
Farma dari tahun 2020 hingga 2023. Berikut ini adalah task yang harus anda lakukan:
➢ Importing Dataset to BigQuery
Pada proyek ini anda ditugaskan untuk mengimpor dataset yang telah disediakan:
    - kf_final_transaction.csv ([link](https://drive.google.com/file/d/1iDOBdKZ4-kkLhpklQWWrsFvACtI7MCz3/view)),
    - kf_inventory.csv ([link](https://drive.google.com/file/d/1ihtG2t0V1AO0IAGkGwQaqtba6AxDEKDI/view)),
    - kf_kantor_cabang.csv ([link](https://drive.google.com/file/d/1vzaasqIeXqqe_jI99dNLaa8nxnoe9OWW/view)),
    - kf_product.csv ([link](https://drive.google.com/file/d/1739wO7BwtVStHCA4Dcj9xGhlc_blBNbT/view)).
Anda harus mengimport keempat dataset tersebut untuk menjadi tabel pada BigQuery, nama tabelnya merupakan nama dari dataset, namun tanpa ".csv"

➢ Buat tabel analisa
Pada proyek ini, anda juga diminta untuk membuat tabel analisa berdasarkan hasil aggregasi dari ke-empat tabel yang sudah diimport sebelumnya. Berikut ini adalah kolom-kolom yang
mandatory pada tabel tersebut:
  ● transaction_id : kode id transaksi,
  ● date : tanggal transaksi dilakukan,
  ● branch_id : kode id cabang Kimia Farma,
  ● branch_name : nama cabang Kimia Farma,
  ● kota : kota cabang Kimia Farma,
  ● provinsi : provinsi cabang Kimia Farma,
  ● rating_cabang : penilaian konsumen terhadap cabang Kimia Farma
  ● customer_name : Nama customer yang melakukan transaksi,
  ● product_id : kode product obat,
  ● product_name : nama obat,
  ● actual_price : harga obat,
  ● discount_percentage : Persentase diskon yang diberikan pada obat,
  ● persentase_gross_laba : Persentase laba yang seharusnya diterima dari obat dengan ketentuan berikut:
      ■ Harga <= Rp 50.000 -> laba 10%
      ■ Harga > Rp 50.000 - 100.000 -> laba 15%
      ■ Harga > Rp 100.000 - 300.000 -> laba 20%
      ■ Harga > Rp 300.000 - 500.000 -> laba 25%
      ■ Harga > Rp 500.000 -> laba 30%,
  ● nett_sales : harga setelah diskon,
  ● nett_profit : keuntungan yang diperoleh Kimia Farma,
  ● rating_transaksi : penilaian konsumen terhadap transaksi yang dilakukan.
