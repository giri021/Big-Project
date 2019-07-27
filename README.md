# Big-Project
Migrasi Infrastruktur On Premises ke Cloud AWS

1.1. Penjelasan Project

1.1.1. Kondisi Environment Sekarang
1. Web aplikasi Sekolah Cilsy, Blog Cilsy, dan Aplikasi Cilsy masih belum berbentuk container, dan masih dalam 1 server dimana environment staging dan Production juga ada di dalam 1 server. 2. Seluruh sistem di  Cilsy belum ada sistem DevOps, CI/CD sama sekali.

1.1.2. Goal
Membuat sebuah infrastruktur dengan konsep CI/CD DevOps yang tepat dan lengkap untuk aplikasi web menggunakan Amazon Web Service. Apabila kalian dapat menyelesaikan project ini sesuai requirementnya, maka kalian bisa dinyatakan memiliki kemampuan untuk merancang infrastruktur devops yang cocok digunakan pada apikasi web yang menggunakan layanan Cloud AWS.

1.1.3. Requirement
Pada requirement ini kalian bebas untuk menggunakan tools yang menurut kalian handal dan cocok untuk diterapkan pada Environment yang dibutuhkan.
1. Memberikan desain topologi, sistem dan flow seperti apa yang sebaiknya dibangun. Kelebihan dan kekurangannya apa.
2. Local development (laptop programmer masing-masing), 
3. Environment Staging untuk memastikan bahwa benar-benar sudah siap dan tanpa cacat sebelum masuk ke production, 
4. Dan environment Production environment yang tampil ke user. 
5. Seluruh sistem harus berbasis Container dan saling berkesinambungan proses development dan deploynya dari sisi programmer. mulai dari development di lokal, masuk ke environment staging, hingga production.
6. Environment berbasis di Cloud AWS dan berbasis infrastructure as a code (jadi bisa dibuat ulang dengan mudah infrastrukturnya).
7. Diterapkannya sistem CI/CD (Jenkins atau semacamnya)
8. Terdapat sistem sentral monitoring untuk seluruh container dan server (TIG atau semacamnya)
9. Terdapat sistem sentral logging untuk seluruh container dan server (ELK atau semacamnya)
10.Code-code terkait environment (docker, dll) yang dibuat harus scalable dan bisa digunakan ulang secara bersama-sama oleh tim lain dengan mudah. Misalnya ada programmer baru yang masuk, maka programmer itu tinggal pull seluruh code dari github tanpa ubah apapun, dia sudah bisa langsung start kerja.
11.Biaya environment seefisien mungkin.
12.Sistem harus High availability 24x7x365.
**Note : Semua web dan aplikasi diarahkan ke domain yang sudah diberikan

1.1.4. Mekanisme Big Project
1. Peserta mengerjakan Big Project Selama 14 Hari awal setelah moderator ataupun instruktur menyatakan untuk memulai mengerjakan.
2. Peserta mengerjakan Big Project sesuai dengan requirement yang tertulis pada panduan yang tersedia.
3. Peserta diharuskan melakukan presentasi, untuk membuktikan hasil yang dikerjakan setelah waktu pengerjaan habis. Presentasi berlangsung selama 180 menit, dimana setiap peserta diberikan waktu selama 30 Menit.
4. Selama Presentasi Small Project peserta harus meyakinkan instruktur bahwa sistem yang mereka buat sangat tepat untuk digunakan.

1.1.5. Tips & Trik
1. Pelajari kembali modul yang sudah diberikan, begitupun dengan rekaman pembelajaran yang ada untuk memperkuat ilmu yang dimiliki agar Big Project bisa terselesaikan sesuai dengan yang diinginkan.
2. Apabila terdapat hal yang membingungkan dapat ditanyakan pada instruktur langsung di group slack
3. Terus mencoba dan pantang mengerah saat mengerjakannya.

1.2. Reward
Khusu bagi kalian yang berhasil menyelesaikan Big Project ini akan mendapatkan reward tambahan berupa :
1. Kenang-kenangan dari Sekolah Devops Cilsy
2. Surat keterangan menyelesaikan project a.n PT. Cilsy Fiolution Indonesia yang berguna untuk melengkapi portofolio di CV kalian.
