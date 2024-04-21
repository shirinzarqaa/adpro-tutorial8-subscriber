a. **What is amqp?**

AMQP (Advanced Message Queuing Protocol) adalah protokol standar aplikasi lapisan atas yang terbuka untuk middleware berorientasi pada pesan, dengan fokus pada antrian, routing, keandalan, dan keamanan.

b. **what it means? guest:guest@localhost:5672, what is the first `quest`, and what is the second `guest` and what is `localhost:5672` is for?**

- `guest:guest`: nama pengguna dan kata sandi untuk server. Dalam contoh ini nama pengguna maupun kata sandi adalah `guest`.
  
- `localhost`: nama host dari server.Dalam hal ini, server berjalan pada mesin yang sama dengan `client`.

- `5672`: nomor port tempat server berjalan. Hal ini, adalah port default untuk AMQP