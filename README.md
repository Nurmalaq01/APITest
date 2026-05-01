Ade Nisa Nurmala Sari

Project test untuk API testing dengan menggunakan public API : https://jsonplaceholder.typicode.com Dimana tools yang dipakai adalah Spreadsheet untuk membuat test scenario nya dan Postman untuk melakukan automation testnya

Cara untuk run test nya :

1. Download file yang ada pada repository ini
2. Buka aplikasi postman
3. Import file ke dalam Postman
4. Buka setiap request dan klik button "Send" untuk melihat hasil dari masing-masing request

Ada beberapa test di dalam project Postman ini:
- Response type id is passed -> adalah respons test yang harus dikeluarkan disaat request mengirim tipe data "id" sebagai number
- Response type id is failed -> adalah respons test yang harus dikeluarkan disaat request mengirim tipe data yang salah
- Get all data -> untuk display semua data yang bisa diakses pada penyimpanan database
- Return request 200 ->adalah respons test yang harus dikeluarkan disaat program dapat menjalankan Get/ambil data dengan benar
- Return data with id 18 -> adalah display data yang memiliki id dengan nomor "18"
- Return data with userId 5 -> adalah display data yang memili userId dengan nomor "5"
- Input new data -> adalah menambahkan data baru pada database
- Return request 201 -> adalah respons test yang harus dikeluarkan disaat program dapat menjalankan Post/create data dengan benar
- Input with empty data -> adalah respons yang dikeluarkan disaat salah satu field tidak diisi saat input data
