# Reflection

### What is amqp?
- amqp simpelnya adalah protokol standar yang dipakai untuk komunikasi asynchronous antar service


### What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?
- amqp ini adalah protol message parsing dimana amqp ini menjamin agar pesan tidak hilang ditengah jalan. URL tersebut adalah sebuah URL koneksi yang digunakan untuk terhubung dengan message broker atau RabbitMQ yang sedang kita pakai di tutorial ini. guest pertama menyatakan username default user untuk mengakses RabbitMQ. guest kedua adalah password default untuk username yang kita gunakan. `localhost:5672` untuk menyatakan RabbitMQ sedang menggunakan di port mana untuk listen koneksi yang masuk dari 