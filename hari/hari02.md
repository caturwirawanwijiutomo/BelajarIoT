## Komponen

Internet of things, bayangkan jika internet menghubungkan tidak hanya manusia dan informasi, internet juga menghubungkan mesin. segala sensor yg membaca fenomena fisik dan segala kapabilitas aktuator untuk mengubah fenomena fisik dari mesin yg kita akses & kontrol melalui internet. setiap mesin juga bisa bertukar informasi dan memutuskan suatu aksi berdasarkan informasi yg kita peroleh.

Sebelum IoT menjadi trend, komputer sudah digunakan untuk melakukan otomasi baik berupa pembacaan sensor atau mengubah suatu. misalkan di pabrik

Hal yang membedakan IoT dengan otomasi yg biasa sudah digunakan di pabrik adalah koneksi internet. otomasi hanya terbatas di tempat dan menggunakan proprietary connection 

Alur dari IoT adalah (Fenomena yg ingin ditangkap) -> sensor->  kapabilitas edge node -> Aktuator -> (fenomena yg ingin diubah) 

Dua rancangan 
Edge - Cloud - Apps
Edge - Gateway - Cloud - Apps

Edge - adalah komponen terluar dari IoT yg terdekat dengan fenomena, suatu blok yg terpasang sensor atau aktuator, maupun keduanya. Kapabilitas dari edge ditentukan dari fenomena apa yang ingin kita tangkap/baca dan kapabilitas aktuator apa yg ingin kita hasilkan. tentu saja hal yang diperlukan. edge sendiri perlu dispedikkan karena isitilah edge router juga dipakai di network. edge yang dimaksud adalah embedded system yang memiliki kemampuan komputasi dan berada dekat dengan site. salah satu contoh edge adalah perangkat seperti raspberry pi atau nvidia jetson.

Gateway - Jika komponen IoT yg akan kita letakkan dekat dengan fenomena dan tidak memiliki kapabilitas mikroprosesor atau koneksi yg memadai dan memerlukan light prosessor yg berdampak pada terbatasnya kapaibilitas koneksi seperti pada wireless sensor network maka dibutuhkan gateway untuk mengkoordinasi nodes. gateway akan menjadi jembatan antara contrained network seperti WSN atau Loran ke traditional TCP/IP network.

Cloud/infrastructure - merupakan tempat untuk komputasi dapat diakses dengan mudah tanpa harus mengeluarkan biaya untuk investarsi infrastruktur

Apps - merupakan interface untuk user, salah satunya ditampilakan konektivitas jika diinginkan kontrol atau pun visualisasi data.
