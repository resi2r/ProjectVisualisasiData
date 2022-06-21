<h1 align='center'>Dashboard Sektor Perikanan Indonesia</h1>
<br></br>
<h2 align='center'>I.	PENDAHULUAN</h2>

## A.	Latar Belakang
<p align='justify'>&nbsp; &nbsp; &nbsp;Indonesia merupakan negara maritim yang sebagian wilayahnya merupakan perairan. Berdasarkan data KKP, sekitar lebih kurang 62% wilayah Indonesia merupakan laut dan perairan. Dengan wilayah perairan yang begitu luas, tentunya sangat memberikan keuntungan bagi Indonesia terutama dalam ketersediaan sumber daya alam.
<br/>&nbsp; &nbsp; &nbsp; Laut Indonesia yang begitu luas mengandung berbagai macam jenis sumber daya alam dengan nilai jual yang sangat tinggi. Perairan Indonesia dihuni oleh berbagai biota laut yang sangat beragam. Mulai dari berbagai jenis ikan, kerang, mollusca, hingga berbagai macam jenis terumbu karang dan masih banyak lagi. 
<br/>&nbsp; &nbsp; &nbsp; Dengan demikian, maka sektor perikanan merupakan salah satu sektor yang menjadi sumber pendapatan bagi sebagian besar masyarakat di Indonesia. Oleh karena itu, pada penelitian ini akan dibahas mengenai sektor perikanan di Indonesia yang meliputi produksi perikanan, nelayan, ekspor, PDB, dan jenis kapal yang digunakan. Agar lebih memudahkan dalam analisis, maka pada penelitian ini akan dibangun sebuah dashboard interaktif sehingga dapat menampilkan kondisi sektor perikanan di Indonesia secara grafis yang mudah dipahami oleh khalayak umum.</p>

## B.	Tujuan
<p align='justify'>&nbsp; &nbsp; &nbsp;Adapun tujuan dari penelitian ini sebagai berikut.
1.	Menghasilkan dashboard informatif data perikanan di Indonesia
2.	Menghasilkan sebuah peta interaktif untuk melihat sebaran  produksi perikanan di Indonesia berdasarkan provinsi dan  jenis usaha di sektor perikanan.
3.	Menghasilkan sebuah peta interaktif untuk melihat sebaran nelayan di Indonesia berdasarkan provinsi dan  jenis usaha di sektor perikanan.
4.	Menghasilkan visualisasi untuk melihat kondisi perikanan dari sisi ekonomi, dimana pada penelitian ini diambil dari dimensi ekspor dan PDB.
5.	Menghasilkan visualisasi untuk melihat gambaran mengenai sarana yang digunakan di sektor perikanan, dimana pada penelitian ini dilihat dari jenis kapal yang digunakan.</p>

## C.	Literatur yang Mendukung
<p align='justify'>&nbsp; &nbsp; &nbsp;Pada tahun 2013, M. Zulkarnain, Pudji Purwanti, dan Erlinda Indrayani telah melakukan penelitian dengan judul Analisis Pengaruh Nilai Produksi Perikanan Budidaya terhadap Produk Domestik Bruto Sektor Perikanan di Indonesia. Penelitian ini bertujuan untuk mengetahui pengaruh secara parsial dan simultan dominan dari nilai produksi perikanan budidaya terhadap Perikanan Produk Domestik sektor perikanan di Indonesia. Hasil penelitian ini menunjukkan bahwa nilai produksi perikanan budidaya secara bersama-sama mempengaruhi PDB sektor perikanan di Indonesia, nilai produksi perikanan sebagian mempengaruhi Produk Domestik Bruto sektor perikanan di Indonesia. Budidaya Laut memiliki efek paling dominan terhadap Produk Domestik Bruto dari sektor perikanan di Indonesia dan diikuti budidaya kolam dan budidaya tanggul. Adapun kolam budidaya memiliki nilai negatif.
<br/>&nbsp; &nbsp; &nbsp;Selanjutnya pada tahun 2016, Meili Musthathi’ah juga melakukan penelitian dengan judul Sistem Informasi Geografis Persebaran Potensi Perikanan Tangkap. Sistem dikembangkan sebagai sebuah aplikasi berbasis web dengan sejumlah fitur utama yang meliputi visualisasi data hasil tangkapan ikan laut dalam bentuk grafik yang mampu menunjukkan tren kenaikan maupun penurunan hasil tangkapan, komparasi hasil tangkapan ikan dari berbagai TPI, dan informasi harga jual terbaru berbagai jenis ikan laut setiap TPI. Selain itu, sistem juga mampu menampilkan peta potensi perikanan tiap TPI berdasarkan hasil tangkapan ikan dalam tiga kategori, yaitu kategori rendah, sedang, dan tinggi. Penelitian ini menunjukkan bahwa dengan pengolahan data dan metode visualisasi yang tepat maka informasi potensi perikanan tangkap dapat disebarluaskan untuk mendukung pengambilan keputusan oleh pihak-pihak yang berkepentingan
<br/>&nbsp; &nbsp; &nbsp;Pada tahun 2019, Kusdiantoro Kusdiantoro, Achmad Fahrudin, Sugeng Hari Wisudo, dan Bambang Juanda juga sudah melakukan penelitian dengan judul Perikanan Tangkap di Indonesia: Potret dan Tantangan Keberlanjutannya. Penelitian ini bertujuan untuk mengkaji kondisi pembangunan perikanan tangkap yang telah dilaksanakan di Indonesia, yang difokuskan pada pada dua aspek utama, yaitu komoditas utama perikanan tangkap tuna, tongkol dan cakalang (TTC) dan pelakunya serta bagaimana strategi keberlanjutannya. Hasil kajian memberikan gambaran bahwa manfaat dari perikanan tangkap di Indonesia belum merata dirasakan. Struktur perikanan tangkap di Indonesia masih didominasi nelayan skala kecil dan berpengaruh terhadap produksi komoditas utama (TTC), Illegal, Unreported and Unregulated Fishing (IUUF) menjadi ancaman terbesar bagi keberlanjutan perikanan tangkap.</p>

<h2 align='center'> II.	METODE</h2>
## A.	Lokasi Penelitian
<p align='justify'>&nbsp; &nbsp; &nbsp;Pada penelitian ini akan menggunakan data yang mencakup seluruh provinsi di Indonesia. Hal ini dilatarbelakangi oleh wilayah Indonesia yang sebagian besar merupakan perairan. Oleh karena itu, sudah dapat dipastikan di setiap provinsi di Indonesia terdapat masyarakat yang  berprofesi di sektor perikanan. </p>

## B.	Alat dan Bahan
<p align='justify'>&nbsp; &nbsp; &nbsp;Pada penelitian ini, untuk membuat visualisasi berupa dashboard menggunakan Tableau. Sementara, untuk publikasi menggunakan Tableau Public. Untuk dokumentasi, peneliti juga mengupload project ini ke Github. </p>

## C.	Teori
<p align='justify'>1.	Produksi ikan adalah seluruh hasil yang diperoleh dari kegiatan penangkapan atau budidaya ikan/binatang air lainnya/tanaman air yang ditangkap atau dipanen dari sumber perikanan alami atau dari tempat pemeliharaan, baik yang diusahakan oleh perusahaan perikanan maupun rumah tangga perikanan.
<br/>2.	Volume produksi dihitung dalam bentuk berat basah ikan hasil tangkapan/budidaya.
<br/>3.	Penangkapan ikan adalah kegiatan menangkap atau mengumpulkan ikan/binatang air lainnya/tanaman air yang hidup di laut/perairan umum secara bebas dan bukan milik perseorangan.
<br/>4.	Budidaya ikan adalah kegiatan memelihara ikan/binatang air lainnya/tanaman air dengan menggunakan fasilitas buatan. Termasuk juga kegiatan pembenihan ikan.
<br/>5.	Kapal penangkap ikan adalah perahu/kapal yang langsung dipergunakan dalam operasi penangkapan ikan/binatang air lainnya/tanaman air. Perahu/kapal yang digunakan untuk mengangkut nelayan, alat-alat penangkap dan hasil penangkapan dalam kegiatan penangkapan ikan dengan menggunakan bagan, sero dan kelong juga termasuk kapal penangkap ikan.
<br/>6.	Produk Domestik Bruto merupakan suatu indikator penting untuk mengetahui kondisi ekonomi suatu lapangan usaha/sektor/subsektor pada suatu periode waktu tertentu.</p>

## D.	Cara Analisis Data
<p align='justify'>&nbsp; &nbsp; &nbsp;Analisis data dapat dilakukan berdasarkan visualisasi data interaktif yang dibangun. Dari visualisasi tersebut dilakukan interpretasi. Analisis data yang digunakan dalam penelitian ini ialah analisis deskriptif. </p>

## E.	Variabel, Data, dan Sumber Data
<p align='justify'>&nbsp; &nbsp; &nbsp;Menurut Rony Megawanto, dkk dalam penelitiannya yang berjudul “Variabel-Variabel yang Berperan Penting dalam Sistem Perikanan Tangkap Nasional” mengatakan terdapat 28 variabel yang berperan penting dalam sistem perikanan tangkap nasional. 
<br/>&nbsp; &nbsp; &nbsp;Namun, karena keterbatasan dalam hal ketersediaan data dan juga kemampuan peneliti, maka hanya diambil lima variabel yaitu produksi ikan, jumlah nelayan, ekspor perikanan, PDB, dan  jumlah kapal penangkap ikan. Data tersebut diperoleh dari website statistik-KKP. Data yang digunakan merupakan data tahun 2020 karena pada website tersebut data yang tersedia untuk kelima variabel tersebut yang terbaru ialah tahun 2020. </p>

<h2 align='center'>III.	HASIL DAN PEMBAHASAN </h2>
<p align='justify'>&nbsp; &nbsp; &nbsp;Sektor perikanan termasuk salah satu sektor yang sangat berperan penting dalam perekonomian nasional. Sebagian besar wilayah Indonesia terdiri dari perairan. Hal ini menyebabkan sebagian besar penduduk bekerja di sektor perikanan. Produk yang diperoleh dari sektor ini tidak hanya untuk dikonsumsi di dalam negeri, tetapi juga di ekspor ke negara lain. 
<br/>&nbsp; &nbsp; &nbsp;Pembahasan mengenai sektor perikanan tidak hanya mencakup produksi ikan dan juga jumlah nelayan, tetapi juga ada variabel-variabel lain seperti ekspor-impor, jumlah kapal, dan lain sebagianya. Karena cakupannya yang cukup luas, maka pada penelitian ini dibangun sebuah dashboard informasi dengan tujuan untuk memudahkan pengguna dalam mendapatkan informasi di sektor perikanan. Dengan adanya dashboard ini, informasi dapat tersampaikan hanya secara visual tanpa perlu membaca teks yang tentunya cukup panjang. Tampilan dashboardnya sebagai berikut.</p>
 ![[Dashboard Sektor Perikanan Indonesia](/Picture/Dashboard Sektor Perikanan Indonesia.png)](https://github.com/resi2r/ProjectVisualisasiData/blob/e2a181f2a52b09e60b99d6b3dbf50ba208e8e650/Picture/Dashboard%20Sektor%20Perikanan%20Indonesia.png)
 

