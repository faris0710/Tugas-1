Nama : Muhammad Faris Zhafir Sambega
NIM : 09011382530157
Kelas : SKU3A
Mata Kuliah : Sistem Operasi

Tugas Pertemuan 1

1.	Buatlah laporan proses instalasi di komputer mahasiswa dan tampilkan screenshot-nya?
 
<img width="800" height="429" alt="image" src="https://github.com/user-attachments/assets/9947dcb1-374f-4354-b35b-9b86055b67f5" />



<img width="805" height="437" alt="image" src="https://github.com/user-attachments/assets/fe074cd6-c585-4bab-92f0-9105cbf674c3" />



<img width="844" height="603" alt="image" src="https://github.com/user-attachments/assets/b554746f-b56f-4ede-bfe8-eca9df0caad2" />



2.	Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point?
Mount Point “/”disebut sebagai root directory atau direktori utama pada sistem Linux. Saat instalasi Ubuntu, partisi yang diberi Mount Point “/” digunakan sebagai tempat utama sistem operasi menyimpan file-file penting, seperti program sistem, konfigurasi, library, dan direktori lainnya.
Pemilihan “/” diperlukan karena Linux menggunakan struktur direktori yang berawal dari root “/”. Tanpa adanya partisi yang dipasang sebagai “/”, sistem operasi tidak memiliki lokasi utama untuk menjalankan dan menyimpan komponen sistemnya. Oleh karena itu, pada proses instalasi Ubuntu perlu dibuat partisi dengan Mount Point “/” sebagai filesystem utama (root). Modul juga menunjukkan bahwa partisi root dibuat dengan format Ext4.


3.	Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !

ext4 : Filesystem Linux yang umum digunakan. Merupakan pengembangan dari Ext3 dan mendukung kapasitas penyimpanan besar serta performa yang baik. Pada modul, Ext4 digunakan untuk partisi /home dan /
ext3 : Filesystem Linux yang merupakan pengembangan dari Ext2 dan memiliki fitur journaling untuk membantu menjaga konsistensi data ketika terjadi gangguan sistem.
Swap : Ruang pada penyimpanan yang digunakan Linux sebagai tambahan memori ketika RAM membutuhkan ruang. Dalam modul, partisi swap dibuat dengan ukuran 1024 MB dan dipilih melalui opsi Use As → Swap Area.
Ntfs : Filesystem yang banyak digunakan oleh sistem operasi Windows. Mendukung file dan partisi berukuran besar serta memiliki fitur keamanan dan permission.
fat32 : Filesystem yang memiliki kompatibilitas luas dengan berbagai sistem operasi dan perangkat. Sering digunakan pada flashdisk, kartu memori, dan media penyimpanan yang perlu dibaca oleh banyak perangkat.
Btrfs : Filesystem Linux modern yang memiliki fitur seperti snapshot, subvolume, dan pengelolaan penyimpanan yang lebih fleksibel.
