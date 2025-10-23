# DocumentationExample

Proyek ini dibuat untuk memenuhi **CODELAB 1** pada **Modul 3 Pemrograman Lanjut**.  
Tujuan proyek ini adalah mempraktikkan penggunaan **Git** dan **GitHub** dalam pembuatan serta pengelolaan proyek Java sederhana.

---

## 📖 Deskripsi Program
Program sederhana ini menampilkan dua kalimat (`kalimat1` dan `kalimat2`) yang digabung menjadi satu baris teks menggunakan `System.out.println()`.

Program ditulis dalam bahasa pemrograman **Java** dengan kelas utama bernama `DocumentationExample`.

---

## 💻 Kode Program
```java
public class DocumentationExample {
    public static void main(String[] args) {
        String kalimat1 = "saya bapak Budi"; // kalimat 1
        String kalimat2 = "saya ibu Budi";   // kalimat 2
        System.out.println("Berikut : " + kalimat1 + " " + kalimat2); // menampilkan semua kalimat
    }
}
