# Tutorial Modul 8 - Subscriber
---
### Muhammad Yusuf Haikal
### 2206081490
### Pemrograman Lanjut A
---

## 1. What is **amqp**?
AMQP (_Advanced Message Queueing Protocol_) merupakan protokol open-source untuk mengatur antrian pesan (message queuing) di antara aplikasi atau komponen perangkat lunak.

pada file `main.rs`, _AMQP_ digunakan untuk menerima pesan dari sebuah antrian (queue) dengan menggunakan library `crosstown_bus`. _AMQP_ digunakan sebagai mekanisme untuk menerima dan menangani pesan dari sebuah _queue_ `user_created`. Ketika ada pesan baru di antrian, _handler_ (`UserCreatedHandler`) akan dipanggil untuk memproses pesan tersebut.

## 2. What it means? `guest:guest@localhost:5672` , what is the first **guest**, and what is the second **guest**, and what is `localhost:5672` is for?
`guest` pertama pada kode tersebut merupakan username yang digunakan untuk mengakses server _AMQP_ _RabbitMQ_. 

`guest` kedua merupakan password dari username, yang dimana pada kode tersebut merupakan `guest`. 

`localhost:5672` merujuk pada tempat kode ini dijalankan,yaitu pada mesin lokal itu sendiri, yang mendengar pada port `5672`. 



