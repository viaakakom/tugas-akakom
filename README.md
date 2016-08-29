# tugas-akakom

Apa itu

Sebuah garpu dari node.js chatting aplikasi dengan @orkj menggunakan socket.io, rethinkdb, paspor dan bcrypt pada sebuah aplikasi express.

catatan:

Ini adalah contoh aplikasi. Meskipun menunjukkan contoh bagaimana mengintegrasikan Paspor dan bcrypt, Anda tidak harus menganggap itu bebas dari kerentanan keamanan. Memiliki kode diaudit hati-hati oleh seorang ahli sebelum Anda memasukkan apa pun mencontoh ke dalam produksi.
lengkap tumpukan

node.js
socket.io
express dan jade
Paspor dan bcrypt
men-debug
RethinkDB
Instalasi

git clone git@github.com:rethinkdb/rethinkdb-example-nodejs-chat.git
cd rethinkdb-example-nodejs-chat && npm install
Catatan : Jika Anda tidak memiliki RethinkDB diinstal, Anda dapat mengikuti petunjuk ini untuk mendapatkannya dan berjalan .

Menjalankan aplikasi

Menjalankan aplikasi sederhana seperti:

node app
Kemudian buka browser: http: // localhost: 8000 .

Catatan : Jika Anda ingin mengganti rincian koneksi standar RethinkDB, Anda dapat menentukan mereka sebagai variabel lingkungan:

RDB_HOST: Host RethinkDB (default: localhost)
RDB_PORT: Port (default 28015)
RDB_DB: Database aplikasi (default: chat)
Jika Anda ingin mengaktifkan logging untuk query database (lihat docs men-debug untuk lebih banyak opsi konfigurasi:

DEBUG=rdb:* node app
Lisensi

Aplikasi demo ini dilisensikan di bawah lisensi MIT: http://opensource.org/licenses/mit-license.php
