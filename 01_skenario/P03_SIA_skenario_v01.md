<!-- deskripsi skenario -->
Mahasiswa mengajukan KRS dengan memilih mata kuliah. Setiap 
pengajuan menjalankan validasi KRS yang memeriksa kelengkapan, 
prasyarat mata kuliah, dan benturan jadwal. Jika validasi berhasil, 
sistem menyimpan pengajuan berstatus menunggu persetujuan dosen 
wali. Pada konfirmasi penyimpanan, mahasiswa dapat memilih 
mengunduh bukti pengajuan. Dosen wali menyetujui atau menolak KRS 
dan memberikan catatan keputusan.

<!-- tabel kebutuhan -->
|ID     |                             Kebutuhan tugas                             |
|-------|-------------------------------------------------------------------------|
|SIA-R01|                  Mahasiswa dapat melihat jadwal kuliah                  |
|SIA-R02|              Admin akademik dapat mengelola jadwal kuliah               |
|SIA-R03|                     Mahasiswa dapat mengajukan KRS                      |
|SIA-R04|             Sistem memvalidasi KRS sebagai bagian pengajuan             |
|SIA-R05|Mahasiswa dapat mengunduh bukti jika memilihnya pada konfirmasi pengajuan|
|SIA-R06|        Dosen wali dapat memproses persetujuan atau penolakan KRS        |


<!-- batas sistem dan aturan -->
• Pengguna telah terautentikasi. 
• Data mata kuliah, prasyarat, dan jadwal tersedia. 
• Validasi gagal menyebabkan pengajuan belum berhasil tersimpan. 
• Unduh bukti tidak menjadi syarat keberhasilan pengajuan. 
• KRS tersimpan belum berarti disetujui. 
• Pembayaran, pengisian nilai, dan implementasi basis data berada di luar 
tugas.

<!-- tabel identifikasi aktor -->

|  Aktor        |        Tujuan terhadap sistem                                                                   |
|-----------------------------------------------------------------------------------------------------------------|
|Mahasiswa      |  Mengajukan KRS,memilih mata kuliah,memilih mengunduh bukti pengajuan                           |
|Dosen wali     |  menyetujui atau menolak KRS dan memberikan catatan keputusan                                   |
|Admin_akademik | validasi KRS,memeriksa kelengkapan,prasyarat mata kuliah,benturan jadwal dan menyimpan pengajuan|



<!-- tabel susunan katalog use case -->

|   ID   |Namausecase|                  Peran dalam model                 |
|--------|-----------|----------------------------------------------------|
|SIA-UC01|   Li   |   ketersediaan peralatan Fungsi utama mahasiswa    |
|SIA-UC02|  Kelola   |        data peralatan Fungsi utama petugas         |
|SIA-UC03|  Ajukan   |         peminjaman Fungsi utama mahasiswa          |
|SIA-UC04|  Periksa  |     ketersediaan Perilaku yang disertakan UC03     |
|SIA-UC05|   Cetak   |    bukti pengajuan Tambahan bersyarat pada UC03    |
|SIA-UC06|  Proses   |     keputusan peminjaman Fungsi utama petugas      |
|SIA-UC07|   Lihat   |laporan peminjaman Fungsi utama kepala laboratorium |


<!-- relasi include -->


<!-- relasi extend -->




