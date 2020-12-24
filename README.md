# vbnetoracle
Oracle 10g 64 Bit

Setelah selesai instalasi maka untuk mengelola database Oracle bisa lewat Broser dengan alamat :

http://127.0.0.1:8080/apex/


user : sys

pwd : {sesuai password yg diisi saat instalasi}

Tambahlah seorang user baru dgn previlege full lewat menu
Administration > Manage User > Create
Pastikan hak aksesnya semua di ceklist
setelah itu logout dan login dgn user yang baru

Di express Edition Anda tidak dapat membuat database dimana database yg anda dapat
secara otomatis bernama xe dgn user dan password sebagaimana Anda seting diatas tadi.

Yang bisa dilakukan adalah membuat tabel lewat menu :
Object Browser > Create > Table

File System.Data.OracleClient.dll dan System.Data.OracleClient.xml merupakan library yang diperlukan untuk mengakses database Oracle 10g tersebut dari aplikasi VB Net
