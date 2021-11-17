## Kuliah TM 12

Kebutuhan Perangkat Lunak

### Kebutuhan Perangkat Lunak

- Kebutuhan PL (SKPL/SRS) adalah dokumentasi yang secara
  lengkap menjelaskan perilaku yang diperlukan PL sebelum
  dirancang dan diuji.
- Analis kebutuhan (atau analis bisnis) membangun spesifikasi
  kebutuhan perangkat lunak (SKPL) melalui pengumpulan kebutuhan
  (elisitasi kebutuhan).
- Wawancara dengan pengguna, pemangku kepentingan, dan siapa pun
  yang perspektifnya perlu diperhitungkan selama desain, pengembangan,
  dan pengujian perangkat lunak
- Pengamatan pengguna di tempat kerja
- Distribusi ringkasan diskusi untuk memverifikasi data yang dikumpulkan
  dalam wawancara

### Ringkasan Diskusi

- Analis kebutuhan dapat menggunakan
  ringkasan diskusi untuk meringkas
  informasi yang dikumpulkan selama
  perolehan dan memvalidasinya
  melalui forum review.
- Catatan yang dikumpulkan selama
  proses elisitasi harus sesuai dengan
  template ringkasan diskusi
- Garis besar ringkasan diskusi dapat
  berfungsi sebagai panduan bagi analis
  pemula dalam memimpin wawancara
  dan rapat

### Discussion Summary outline

1. Project background
   a. Purpose of project
   b. Scope of project
   c. Other background information
2. Perspectives
   a. Who will use the system?
   b. Who can provide input about the system?
3. Project Objectives
   a. Known business rules
   b. System information and/or diagrams
   c. Assumptions and dependencies
   d. Design and implementation constraints
4. Risks
5. Known future enhancements
6. References
7. Open, unresolved or TBD issues

### Kasus-kasus Penggunaan

- Kasus penggunaan (use case) adalah deskripsi dari interaksi
  spesifik yang mungkin dilakukan pengguna terhadap sistem.
- Dalam konteks MPPL, kasus penggunaan adalah alat sederhana
  yang ‘menipu’ dalam menjelaskan fungsionalitas PL.
- UC tidak menjelaskan cara kerja internal PL, serta tidak menjelaskan
  bagaimana PL tersebut akan diimplementasikan.
- UC hanya menunjukkan bagaimana langkah-langkah yang diikuti
  pengguna untuk menggunakan PL dalam melakukan pekerjaannya.
- Semua cara pengguna berinteraksi dengan PL dapat dijelaskan dengan
  cara ini.

### Kebutuhan Fungsional

- Kebutuhan fungsional menentukan perilaku eksternal
  yang diperlukan dari proyek PL.
- Tujuan dari kebutuhan tersebut adalah untuk mengkomunikasikan perilaku yang
  diperlukan dengan cara yang sejelas mungkin dan tidak ambigu.
- Perilaku dalam kebutuhan dapat berisi daftar, poin, persamaan, gambar, atau
  referensi ke dokumen eksternal, dan materi lain yang akan membantu pembaca
  memahami apa yang perlu diterapkan.

### Kebutuhan Non Fungsional

- Kebutuhan non fungsional menentukan karakteristik PL tanpa
  mengubah perilakunya.
- Pengguna memiliki ekspektasi implisit tentang seberapa baik PL akan
  bekerja.
- Karakteristik ini mencakup seberapa mudah PL digunakan, seberapa
  cepat dijalankan, seberapa andal, dan seberapa baik perilakunya ketika
  muncul kondisi yang tidak terduga.
- Kebutuhan non fungsional menentukan aspek-aspek tentang sistem ini.
- Kebutuhan non fungsional sering disebut sebagai “non-behavioral
  requirements " atau "atribut kualitas perangkat lunak“.

### Spesifikasi Kebutuhan PL (SKPL)

- SKPL merepresentasikan gambaran lengkap tentang perilaku
  PL yang akan dikembangkan.
- SRS meliputi:
  - <p style="color: #63a4ff">Serangkaian kasus penggunaan</p> yang menjelaskan semua interaksi
    yang akan dilakukan pengguna dengan PL.
  - <p style="color: #63a4ff">Semua kebutuhan fungsional</p> yang diperlukan untuk menentukan
    cara kerja internal perangkat lunak: kalkulasi, detail teknis,
    manipulasi dan pemrosesan data, dan fungsionalitas khusus lainnya
    yang menunjukkan bagaimana kasus penggunaan harus dipenuhi.
  - <p style="color: #63a4ff">Kebutuhan non fungsional</p>, yang memberikan batasan pada desain
    atau implementasi (seperti persyaratan kinerja, standar kualitas atau
    batasan desain lainnya).

### Kebutuhan PL vs Desain

- Sering terjadi kesulitan dalam memahami perbedaan
  antara ruang lingkup, kebutuhan PL, dan desain.
- <p style="color: #63a4ff">Ruang lingkup</p> (cakupan) menunjukkan kebutuhan organisasi, dan
  didokumentasikan dalam dokumen visi dan ruang lingkup
- <p style="color: #63a4ff">Kebutuhan PL</p> mendokumentasikan perilaku PL yang akan memenuhi kebutuhan
  tersebut
- <p style="color: #63a4ff">Desain</p> menunjukkan bagaimana persyaratan tersebut akan diterapkan secara
  teknis

### Pengendalian Perubahan

- Pengendalian perubahan adalah metode untuk <p style="color: #63a4ff">menerapkan
  perubahan yang layak</p> terhadap PL, dan untuk mencegah
  perubahan yang tidak perlu atau terlalu mahal agar tidak
  mengganggu proyek.
  - Pengendalian perubahan dilakukan berdasarkan kesepakatan antara
    tim proyek dan PM yang bertanggung jawab untuk pengambilan
    keputusan, untuk mengevaluasi dampak perubahan sebelum
    menerapkannya.
  - Banyak perubahan yang awalnya terdengar seperti ide bagus, namun
    akhirnya ditolak karena ternyata biayanya sangat besar.
- Dewan kendali perubahan (change control board/ CCB)
  terdiri dari pengambil keputusan, PM, perwakilan pemangku
  kepentingan atau pengguna, dan anggota tim terpilih.
  - CCB menganalisis dampak dari semua perubahan yang diminta pada
    perangkat lunak dan memiliki kewenangan untuk <p style="color: #63a4ff">menyetujui atau
    menolak</p> permintaan perubahan apapun setelah pengembangan
    sedang berlangsung.
  - Sebelum proyek dimulai, daftar anggota CCB harus ditulis dan
    disepakati, dan setiap anggota CCB harus memahami mengapa
    proses pengendalian perubahan diperlukan dan apa peran mereka di
    dalamnya.
- Setiap kali perubahan diperlukan, CCB mengikuti proses
  kontrol perubahan untuk mengevaluasi perubahan:
  - Manfaat potensial dari perubahan tersebut dituliskan, dan PM
    bekerja dengan tim untuk memperkirakan potensi dampak
    perubahan tersebut pada proyek.
  - Jika manfaat dari perubahan sebanding dengan biayanya, PM
    memperbarui rencana tersebut untuk mencerminkan perkiraan baru.
    Jika tidak, perubahan akan ditolak dan tim melanjutkan rencana
    awal.
  - CCB menerima atau menolak perubahan tersebut.
