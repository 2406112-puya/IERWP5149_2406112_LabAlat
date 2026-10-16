Mahasiswa melihat jadwal kuliah melalui Sistem Informasi Akademik. Admin akademik mengelola jadwal kuliah. Dalam latihan ini, mahasiswa tidak mengelola jadwal dan admin tidak dihubungkan dengan fungsi melihat jadwal sebagai pengguna mahasiswa.


|ID kebutuhan|    Aktor           |          Nama fungsi       |
|------------|--------------------|----------------------------|
|SIA-R01     |Mahasiswa           |Lihat jadwal kuliah         |
|SIA-R02     |Admin               |Kelola jadwal kuliah        |

|No.|Temuan                                                    |Perbaikan yang diperlukan                      |Alasan                                                     |
|---|----------------------------------------------------------|--------------------------------------------|-----------------------------------------------------------|
| 1 | Nama batas sistem tertulis “sistem laboratorium”.     Ubah menjadi Sistem Informasi Akademik.        nama batas sistem harus sesuai dengan skenario pengelolaan jadwal kuliah.    
	  
2    Use case “lihat jadwal kuliah” berbentuk persegi panjang        Ubah menjadi elips.                            Dalam UML, use case digambarkan dengan bentuk elips.
3    Aktor Mahasiswa terhubung dengan use case yang tidak sesuai atau tidak lengkap        Hubungkan Mahasiswa dengan “Lihat Jadwal Kuliah”     Mahasiswa menggunakan sistem untuk melihat jadwal kuliah.
4    Aktor Admin belum terhubung secara benar dengan fungsi pengelolaan jadwal     Hubungkan Admin Akademik dengan “Kelola Jadwal Kuliah”       Admin Akademik bertugas mengelola jadwal kuliah.

	



	
