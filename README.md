1. client akan masuk ke website yang akan di arahkan ke route S3, fungsi route s3 sendiri adalah mengarahkan lalu lintas pengguna ke aplikasi internet dengan menerjemahkan nama domain menjadi alamat IP
2. lalu route 53 akan mengarahkan ke elastic load balancing yang akan mendistribusikan lalu lintas ke beberapa instance EC2 dan membantu meningkatkan ketersediaan aplikasi, kinerja, dan skalabilitas.
3. setelah itu ELB akan mengarah ke ke EC2 dan ASG dimana di dalam ec2 sudah memiliki layanan aplikasi e-commerce.
4. untuk s3 sendiri untuk meyimpan atau menampilkan data, foto produk dan dan backup.
5. AWS elastic Cache berfungsi untuk meningkatkan kinerja aplikasi dengan menyimpan data yang sering diakses dalam memory.
6. lalu untuk memonitoring menggunakan AWS Cloud Watch.
<img>[[Screenshot 2024-06-20 133126.png](https://github.com/AbelJasen15/Scalable-and-E-commerce-Platform-Architecture-Design/blob/main/Screenshot%202024-06-20%20133126.png)](https://github.com/AbelJasen15/Scalable-and-E-commerce-Platform-Architecture-Design/blob/main/Screenshot%202024-06-20%20133126.png?raw=true)](https://github.com/AbelJasen15/Scalable-and-E-commerce-Platform-Architecture-Design/blob/main/Screenshot%202024-06-20%20133126.png?raw=true)</img>
