# Latihan-2

## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Dendi Permana |
| **NIM** | 312310694 |
| **Kelas** | TI.23.A.6 |
| **Mata Kuliah** | Pemrograman Orientasi Objek |

### Latihan
Buatlah kode program java untuk:
- Mendeklarasikan class **Person**, dengan atribut `Nama`, `JenisKelamin`, `Umur` dan lengkapi dengan `access modifier`.
- Buatlah dua buah objek dari class **Person** bernama Anton dan Riko dan panggil method `setter` dan `getter`.
``` javascript
// Deklarasi class Person
public class Person {
    private String Nama;
    private String JenisKelamin;
    private int Umur;

    // Setter untuk atribut Nama, JenisKelamin, dan Umur
    public void setNama(String Nama) {
        this.Nama = Nama;
    }

    public void setJenisKelamin(String JenisKelamin) {
        this.JenisKelamin = JenisKelamin;
    }

    public void setUmur(int Umur) {
        this.Umur = Umur;
    }

    // Getter untuk atribut Nama, JenisKelamin, dan Umur
    public String getNama() {
        return this.Nama;
    }

    public String getJenisKelamin() {
        return this.JenisKelamin;
    }

    public int getUmur() {
        return this.Umur;
    }

    // Main method
    public static void main(String[] args) {
        // Membuat objek Anton dari class Person
        Person Anton = new Person();

        // Memanggil setter untuk mengisi nilai atribut Anton
        Anton.setNama("Anton");
        Anton.setJenisKelamin("Laki-laki");
        Anton.setUmur(25);

        // Menampilkan informasi Anton menggunakan getter
        System.out.println("Informasi Anton:");
        System.out.println("Nama: " + Anton.getNama());
        System.out.println("Jenis Kelamin: " + Anton.getJenisKelamin());
        System.out.println("Umur: " + Anton.getUmur());

        // Membuat objek Riko dari class Person
        Person Riko = new Person();

        // Memanggil setter untuk mengisi nilai atribut Riko
        Riko.setNama("Riko");
        Riko.setJenisKelamin("Perempuan");
        Riko.setUmur(30);

        // Menampilkan informasi Riko menggunakan getter
        System.out.println("\nInformasi Riko:");
        System.out.println("Nama: " + Riko.getNama());
        System.out.println("Jenis Kelamin: " + Riko.getJenisKelamin());
        System.out.println("Umur: " + Riko.getUmur());
    }
}
```
### Penjelasan


#### Tampilan Output
