1.Jelaskan apa yang dimaksud dengan container pada docker !
Jawaban :
 Docker Container menjadi wadah bagi instance Docker image. Membuat dan menjalankan Image menghasilkan Docker container. Image menyediakan template yang digunakan dalam pembuatan container. Di dalam image, terdapat informasi yang dibutuhkan untuk membuat container. 

2.Jelaskan apa perbedaan antara konsep container dengan virtual machine !
Jawaban :  
-Walaupun keduanya sama-sama berjalan pada virtualisasi, namun VM dan Container ini memiliki beberapa perbedaan. Diantaranya yaitu:
-Container lebih efektif dan ringan dibandingkan dengan VM (Virtual Machine)
Mengapa Container bisa lebih efektif dan lebih ringan dibanding dengan VM (Virtual Machine)? Jawabannya karena container hanya mengisolasi library dan aplikasi yang akan dijalankan saja. Berbeda dengan Virtual Machine yang mengharuskan untuk mengisolasi seluruh komponen seperti, perangkat keras, kernel, sistem operasi, dan lain - lain. 
-Container dapat melakukan efisiensi resource dengan sebaik – baiknya pada system
Berbeda dengan VM, Container ini dapat melakukan efisiensi penggunaan resource dengan sangat baik. Sehingga, ketika salah satu container sedang siap, maka container yang satunya bisa menggunakan resource milik container yang sedang iddle, begitupun sebaliknya.
-VM (Virtual Machine) menggunakan seluruh resource yang ada pada host, sedangkan Container hanya menggunakan sedikit resource dari host
 -VM (Virtual Machine) menggunakan kernel tersendiri yang kemungkinan akan diproses langsung pada host
-Container tidak diizinkan untuk mengakses kernel, sedangkan Virtuam Machine dapat menggunakan kernel tersendiri
 
3.Apa yang dimaksud dengan docker file ?
Jawaban : 
Dockerfile adalah file teks yang berisi semua perintah yang bisa dijalankan user pada baris perintah untuk membuat image. Ini mencakup semua instruksi yang diperlukan oleh docker untuk membangun image.

4.Apa yang dimaksud dengan docker registery ?
Jawaban :
Repositori untuk Docker images. Docker clients terhubung ke registries untuk mendownload (“pull”) images atau untuk upload (“push”) images yang telah dibuat. dapat bersifat public atau private. Dua public registries utama adalah Docker Hub dan Docker Cloud.

5.Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung !
Jawaban :
Menggunakan Docker-Compose 
langkahnya dengan membuat konfigurasi di satu file docker-compose.yml,berfungsi untuk menjadikan 1 container yang sama dan dapat terhubung.