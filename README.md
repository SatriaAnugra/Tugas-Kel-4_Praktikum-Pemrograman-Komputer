# Tugas-Kel-4_Praktikum-Pemrograman-Komputer
# Nama Kelompok 4
# 1. Satria Anugra
# 2. Reno
# 3. Muhammad Rio Perdana
# 4. Muhammad Raihan Maulana Zaqi
# 5. Muhammad Raffli Renaldi


nomor 3
Buat metode pengembalian nilai, isVowel yang mengembalikan nilai benar jika karakter tertentu adalah vokal, dan sebaliknya mengembalikan nilai salah. Dalam metode main(), terima string dari pengguna dan hitung jumlah vokal dalam string itu.                                                                                                                                                           

public class Main {
    public static boolean isEven(int angka) {
        return angka % 2 == 0;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Masukkan bilangan bulat: ");
        int bilangan = scanner.nextInt();

        if (isEven(bilangan)) {
            System.out.println(bilangan + " adalah bilangan genap.");
        } else {
            System.out.println(bilangan + " adalah bilangan ganjil.");
        }
    }
}
keluaraan nya : Masukkan bilangan bulat: 10
10 adalah bilangan genap.

jawaban :  dengan menggunakan metode is even bertipe int disebut angka untuk memeriksa angka habis dibagi 2 jika hasilnya 0 maka "true" jika hasil bukan 0 maka angka ganjil "false" mencetak hasil genap atau ganjil denagan scanner
import java.util.Scanner;
mport java.util.Scanner;
