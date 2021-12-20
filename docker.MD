1. Jelaskan apa yang dimaksud dengan container pada docker !
Container adalah sebuah wadah ringan seperti cloud yang berisi semua keperluan untuk menjalankan sebuah aplikasi.

2. Jelaskan apa perbedaan antara konsep container dengan virtual machine !
Pada virtualisasi konservatif, hypervisor menvisualisasi hardware fisik. Hal ini menyebabkan tiap mesin virtual memiliki guest OS,
virtual copy dari hardware yang OS harus jalankan, dan aplikasi beserta library dan dependenciesnya.
Kontainer menvisualisasi sistem operasi sehingga tiap kontainer sendiri terdiri hanya aplikasi serta library dan dependencies yang dibutuhkan. 
Kontainer tidak membutuhkan guest OS untuk setiap instansi dan dapat dengan mudah memanfaatkan fitur dan resource dari host OS. Kontainer juga 
yang membuat arsitektur mikroservis mungkin untuk dilakukan

3. Apa yang dimaksud dengan docker file ?
Dockerfile sendiri adalah merupakan skrip yang berisi atau terdiri dari serangkaian perintah, intruksi (argumen) 
yang akan dieksekusi secara otomatisasi dan berurutan untuk membangun sebuah image. 

4. Apa yang dimaksud dengan docker registery ?
Docker registry adalah aplikasi yang mengelola dan menyimpan docker images. Hal ini berguna untuk memudahkan developer/sysadmin 
dalam proses deploy karena tidak perlu lagi melakukan build image setiap ingin melakukan deploy.

5. Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung !
untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung dapat menggunakan Docker Compose dengan format docker-compose.yml . 
Docker-Compose adalah alat untuk mendefinisikan dan menjalankan satu atau beberapa container yang saling terkait dengan sebuah command. 
