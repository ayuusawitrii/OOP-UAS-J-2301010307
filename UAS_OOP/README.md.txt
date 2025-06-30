# Project UAS Java GUI

Aplikasi CRUD Java menggunakan Swing, koneksi ke MySQL, dan export database.

## Struktur

- `src/uas/` → File source code
- `lib/` → MySQL Connector
- `database/uas.sql` → File database MySQL

## Koneksi

Edit file `koneksi.java` sesuai database :

```java
String url = "jdbc:mysql://localhost:3306/uas";
String user = "root";
String pass = "";
