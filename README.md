# Kode-Tubes-STL-Selesai-dan-Sudah-Revisi
Kode sudah selesai untuk tes ketiga sensor keluarannya sudah bagus, terkoneksi ke blynk serta dapat mengirim notifikasi/peringatan ke smartphone dan email melalui tombol darurat. dalam kode terdapat 3 poin yang terpenuhi dari aturan tugas besar yaitu: task minimal 3 (di kode ada 5 task), ada perubahan prioritas task dan pengunaan semaphores sehingga terdapat 3 poin terpenuhi.

Untuk video Simulasi ada pada link berikut: https://youtube.com/shorts/NeSgrYi0e6s?feature=share dan https://www.youtube.com/shorts/QDf8dBfwlyM serta ini https://www.youtube.com/watch?v=lr3sS67JrXc

dari judul kami yaitu Sistem Monitoring Kualitas Udara dalam Ruangan dimana kami ingin memantau kadar asap, suhu dan kada debu di blynk tidak bisa dilakukan karena kemungkinan besar program yang kami buat sudah berat dan kami pun sudah mencoba untuk mengirim hasil baca sensor ke blynk menggunakan tambahan task, simpan di loop dan simpan dimasing masing task yang berakhir program crash dan bahkan sering reset terus untuk esp32. oleh karena itu ini adalah hasil koding terakhir dari kami. sekian terima kasih dan mohon maaf atas kekurangan kami.

Ada sedikit perubahan terkait masalah yang sebelumnya tidak bisa memantau kadar asap, suhu dan debu di blynk sekarang dapat dilakukan. masalah sebelumnya karena penambahan task dan metode queue masih bermasalah namun, untuk loop sekarang dapat dilakukan sehingga hasil baca sensor dapat terkirim. kesalah yang terjadi karena kode pengiriman data sensor ternyata ada di task MQ-135 tidak di loop oleh karena itu tidak ada yang terkirim. untuk kode akhir sudah saya tambahkan disini dengan judul "Kode_Selesai_Percobaan_2_Tambah_Pengirim_Hasil_Baca_Sensor_di_L" (yang terpotong L harusnya Loop). jadi mohon maaf bapak/ibu atas kesalahan kami, sekian terima kasih.

untuk video simulasi dan Foto saya tambahkan yang baru pada link berikut:

Link untuk memantau sensor terutama sensor debu ke kondisi normal: https://youtu.be/ZRlNxe1Gxb4 

Link untuk simulasi alat dari deteksi tiga sensor sampai kipas aktif: https://youtu.be/8c6MMYvQCD8

Link untuk memantau pengiriman hasil baca sensor ke blynk dan notifikasinya bila tombol darurat ditekan: https://youtu.be/nAx5kDcey64 

Link dokumentasi berupa foto simulasi: https://drive.google.com/file/d/1pfshQ76j7xB-HvCUzTb1Z4ZOC751-it0/view?usp=sharing
