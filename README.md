# Customer-Personality-Analysis

# **Latar Belakang**

Seorang Data Scientis sebuah perusahaan Online Marketplace, ingin memahami perilaku pelanggan dengan menganalisis kepribadian/perilaku belanja dari para pelanggan. Tujuan analisis ini adalah agar perusahaan dapat melakukan campaign yang tepat berdasarkan analisis segmen pelanggan mana yang paling memungkinakan membeli suatu produk, sehingga promosi yang yang diberikan perusahaan tepat sasaran.


# **Pernyataan Masalah**

Perusahaan ingin mengetahui:
* **produk apa yang paling sering dibeli berdasarkan segmen usia**
* **produk apa yang paling sering dibeli berdasarkan segmen marital status dan jumlah anak yang dimiliki**
* **bulan apa yang mengalami penurunan pembelian**
* **tanggal berapa yang mengalami peningkatan dan penurunan pembelian**
* **penjualan mana yang paling sering dilakukan, baik melalui website, toko, maupun katalog**

Informasi berikut diharapkan dapat membantu perusahaan untuk mengurangi cost campaing dan meningkatkan penjualan dengan memberikan promo yang tepat.
 
Hal yang pertama kali dilakukan adalah mengetahui **Bagaimana karakteristik pembeli yang berdasarkan status keluarga dan usia**

### Keterangan Masing-Masing Kolom:
Terdapat 29 kolom yang masing-masing kolom berisikan informasi sebagai berikut:

**Data Pelanggan:**
* ID: - Kode Unik/ID Pelanggan
* Year_Birth: Tahun lahir pelanggan
* Education: Level edukasi pelanggan
* Marital_Status: Status pernikahan pelanggan
* Income: Penghasilan tahunan pelanggan
* Kidhome: Jumlah Anak dalam satu rumah
* Teenhome: Jumlah Anak dalam satu rumah
* Dt_Customer: Tanggal pelanggan pertama kali memakai aplikasi/situs belanja
* Recency: Jumlah hari setelah pembelian terakhir
* Complain: 1 apabila customer pernah complain selama 2 tahun terakhir, 0 tidak pernah

**Produk:**
* MntWines: Total pembelian Wine selama 2 tahun terakhir
* MntFruits: Total pembelian Buah selama 2 tahun terakhir
* MntMeatProducts: Total pembelian produk Daging selama 2 tahun terakhir
* MntFishProducts: Total pembelian Ikan selama 2 tahun terakhir
* MntSweetProducts: Total pembelian produk manis selama 2 tahun terakhir
* MntGoldProds: Total pembelian Emas selama 2 tahun terakhir

**Promosi**
* NumDealsPurchases: Pembelian yang dilakukan dengan diskon
* AcceptedCmp1: 1 apabila pelanggan menerima tawaran diskon pada campaign pertama, 0 tidak
* AcceptedCmp2: 1 apabila pelanggan menerima tawaran diskon pada campaign kedua, 0 tidak
* AcceptedCmp3: 1 apabila pelanggan menerima tawaran diskon pada campaign ketiga, 0 tidak
* AcceptedCmp4: 1 apabila pelanggan menerima tawaran diskon pada campaign keempat, 0 tidak
* AcceptedCmp5: 1 apabila pelanggan menerima tawaran diskon pada campaign kelima, 0 tidak
* Response: 1 apabila pelanggan menerima tawaran diskon pada campaign terakhir, 0 tidak

**Tempat Pembelian**
* NumWebPurchases: Jumlah pembelian yang dilakukan melalui website perusahaan
* NumCatalogPurchases: Jumlah pembelian yang dilakukan melalui Katalog
* NumStorePurchases: Jumlah pembelian yang dilakukan langsung di toko
* NumWebVisitsMonth: Jumlah kunjungan website yang dilakukan pelanggan satu bulan terakhir
