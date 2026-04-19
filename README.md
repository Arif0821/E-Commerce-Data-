# Study Case Analisis Data CRM iFood 📊🛒
iFood adalah aplikasi pesan antar makanan terkemuka di Brasil, hadir di lebih dari seribu kota. Menjaga tingkat keterlibatan pelanggan yang tinggi adalah kunci untuk menumbuhkan dan mengkonsolidasikan posisi perusahaan sebagai pemimpin pasar.
Analis Data yang bekerja di dalam tim data terus-menerus ditantang untuk memberikan wawasan dan nilai tambah bagi perusahaan melalui proyek-proyek dengan ruang lingkup terbuka. Kasus ini bermaksud untuk menyimulasikan hal tersebut.
Dalam kasus ini, Anda disajikan sebuah contoh dataset, yang menyimulasikan informasi meta tentang pelanggan dan interaksi kampanye iFood dengan pelanggan tersebut. Tantangan Anda adalah untuk memahami data, menemukan peluang & wawasan bisnis, serta mengusulkan tindakan berbasis data apa pun untuk mengoptimalkan hasil kampanye & menghasilkan nilai bagi perusahaan.

**Tujuan Utama adalah:**
•	Eksplorasi data – jangan hanya memplot nilai rata-rata dan jumlah. Berikan wawasan, tentukan sebab dan akibat.
•	Memberikan pemahaman yang lebih baik tentang fitur karakteristik dari responden;
•	Mengusulkan dan mendeskripsikan segmentasi pelanggan berdasarkan perilaku pelanggan;
•	Membuat model prediktif yang memungkinkan perusahaan untuk memaksimalkan keuntungan dari kampanye pemasaran berikutnya.

**Latar Belakang**
Pertimbangkan sebuah perusahaan mapan yang beroperasi di sektor makanan ritel. Saat ini mereka memiliki sekitar beberapa ratus ribu pelanggan terdaftar dan melayani hampir satu juta konsumen setiap tahun. Mereka menjual produk dari 5 kategori utama: anggur, produk daging langka, buah-buahan eksotis, ikan yang diolah secara khusus, dan produk manis. Ini dapat dibagi lagi menjadi produk emas dan produk reguler. Pelanggan dapat memesan dan memperoleh produk melalui 3 saluran penjualan: toko fisik, katalog, dan situs web perusahaan.

Secara global, perusahaan memiliki pendapatan yang solid dan laba bersih yang sehat dalam 3 tahun terakhir, namun prospek pertumbuhan laba untuk 3 tahun ke depan tidak menjanjikan... Karena alasan ini, beberapa inisiatif strategis sedang dipertimbangkan untuk membalikkan situasi ini. Salah satunya adalah meningkatkan kinerja aktivitas pemasaran, dengan fokus khusus pada kampanye pemasaran.
Departemen pemasaran ditekan untuk membelanjakan anggaran tahunannya dengan lebih bijak. Chief Marketing Officer (CMO) menyadari pentingnya memiliki pendekatan kuantitatif dalam mengambil keputusan, yang menjadi alasan mengapa tim kecil ilmuwan data (data scientist) dipekerjakan dengan tujuan yang jelas: membangun model prediktif yang akan mendukung inisiatif pemasaran langsung. Diharapkan, keberhasilan dari aktivitas ini akan membuktikan nilai dari pendekatan tersebut dan meyakinkan pihak-pihak yang lebih skeptis di dalam perusahaan.

Tujuan dari tim ini adalah untuk membangun model prediktif yang akan menghasilkan keuntungan tertinggi untuk kampanye pemasaran langsung berikutnya, yang dijadwalkan pada bulan depan. Kampanye baru, yang keenam, bertujuan untuk menjual gawai (gadget) baru ke Basis Data Pelanggan.
Untuk membangun model tersebut, kampanye percontohan yang melibatkan 2.240 pelanggan telah dilaksanakan. Pelanggan dipilih secara acak dan dihubungi melalui telepon terkait akuisisi gawai tersebut. Selama bulan-bulan berikutnya, pelanggan yang membeli penawaran tersebut diberi label dengan benar. Total biaya kampanye sampel tersebut adalah 6.720 MU (Monetary Units) dan pendapatan yang dihasilkan oleh pelanggan yang menerima penawaran tersebut adalah 3.674 MU. Secara global kampanye tersebut menghasilkan keuntungan sebesar -3.046 MU. Tingkat keberhasilan kampanye tersebut adalah 15%.
Tujuan dari tim ini adalah mengembangkan model yang memprediksi perilaku pelanggan dan menerapkannya ke seluruh basis pelanggan lainnya. Diharapkan model tersebut akan memungkinkan perusahaan untuk memilih pelanggan yang paling mungkin membeli penawaran tersebut dan mengabaikan mereka yang tidak akan merespons, sehingga membuat kampanye berikutnya sangat menguntungkan. Selain itu, selain memaksimalkan keuntungan dari kampanye, CMO tertarik untuk memahami dan mempelajari fitur karakteristik dari pelanggan yang bersedia membeli gawai tersebut. Dataset ini berisi fitur sosio-demografis dan firmografis tentang 2.240 pelanggan yang dihubungi. Selain itu, dataset ini juga berisi tanda (flag) untuk pelanggan yang merespons kampanye tersebut dengan membeli produk.

**Deskripsi Meta data :**

AcceptedCmp1;	1 jika pelanggan menerima penawaran pada kampanye ke-1, 0 jika sebaliknya
AcceptedCmp2;	1 jika pelanggan menerima penawaran pada kampanye ke-2, 0 jika sebaliknya
AcceptedCmp3;	1 jika pelanggan menerima penawaran pada kampanye ke-3, 0 jika sebaliknya
AcceptedCmp4;	1 jika pelanggan menerima penawaran pada kampanye ke-4, 0 jika sebaliknya
AcceptedCmp5;	1 jika pelanggan menerima penawaran pada kampanye ke-5, 0 jika sebaliknya
Response (target);	1 jika pelanggan menerima penawaran pada kampanye terakhir, 0 jika sebaliknya
Complain;	1 jika pelanggan mengajukan keluhan dalam 2 tahun terakhir
DtCustomer;	tanggal pendaftaran pelanggan di perusahaan
Education;	tingkat pendidikan pelanggan
Marital;	status pernikahan pelanggan
Kidhome;	jumlah anak kecil di rumah tangga pelanggan
Teenhome;	jumlah remaja di rumah tangga pelanggan
Income;	pendapatan rumah tangga tahunan pelanggan
MntFishProducts;	jumlah yang dihabiskan untuk produk ikan dalam 2 tahun terakhir
MntMeatProducts;	jumlah yang dihabiskan untuk produk daging dalam 2 tahun terakhir
MntFruits;	jumlah yang dihabiskan untuk buah-buahan dalam 2 tahun terakhir
MntSweetProducts;	jumlah yang dihabiskan untuk produk manis dalam 2 tahun terakhir
MntWines;	jumlah yang dihabiskan untuk anggur dalam 2 tahun terakhir
MntGoldProds;	jumlah yang dihabiskan untuk produk emas dalam 2 tahun terakhir
NumDealsPurchases;	jumlah pembelian yang dilakukan dengan diskon
NumCatalogPurchases;	jumlah pembelian yang dilakukan menggunakan katalog
NumStorePurchases;	jumlah pembelian yang dilakukan secara langsung di toko
NumWebPurchases;	jumlah pembelian yang dilakukan melalui situs web perusahaan
NumWebVisitsMonth;	jumlah kunjungan ke situs web perusahaan pada bulan lalu
Recency;	jumlah hari sejak pembelian terakhir
