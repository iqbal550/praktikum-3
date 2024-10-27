#praktikum
#praktikum tugas bahasa pemrograman pertemuan ke 5 
# Input nilai a, b, dan c
a = float(input("Masukkan nilai a: "))
b = float(input("Masukkan nilai b: "))
c = float(input("Masukkan nilai c: "))

# Proses menentukan nilai terbesar
if a >= b and a >= c:
    terbesar = a
elif b >= a and b >= c:
    terbesar = b
else:
    terbesar = c

# Output hasil
print("Bilangan terbesar adalah:", terbesar)
Masukkan nilai a: 
97
Masukkan nilai b: 
56
Masukkan nilai c: 
36
Bilangan terbesar adalah: 97.0

max_value = 0

while True:
    n = int(input("Input N (masukkan 0 untuk berhenti): "))
    
    if n == 0:
        break
        
    if n > max_value:
        max_value = n

print("Nilai maksimum adalah:", max_value)
Input N (masukkan 0 untuk berhenti): 
3
Input N (masukkan 0 untuk berhenti): 
5
Input N (masukkan 0 untuk berhenti): 
2
Input N (masukkan 0 untuk berhenti): 
8
Input N (masukkan 0 untuk berhenti): 
0
Nilai maksimum adalah: 8
Kode Python di atas digunakan untuk mencari nilai maksimum dari sekumpulan angka yang dimasukkan oleh pengguna. Berikut adalah penjelasan tiap barisnya:

max_value = 0: Variabel max_value diinisialisasi dengan nilai 0, yang akan menyimpan nilai terbesar dari angka yang dimasukkan.

while True:: Memulai loop while yang berjalan terus-menerus (infinite loop) hingga mencapai perintah break di dalamnya.

n = int(input("Input N (masukkan 0 untuk berhenti): ")): Pengguna diminta memasukkan angka n. Jika pengguna memasukkan 0, loop akan berhenti. Jika pengguna memasukkan angka selain 0, program akan terus berjalan dan memproses angka tersebut.

if n == 0:: Mengecek apakah n bernilai 0. Jika benar, maka program keluar dari loop dengan perintah break.

if n > max_value:: Jika n lebih besar dari max_value, maka max_value diperbarui dengan nilai n. Dengan demikian, max_value selalu menyimpan angka terbesar yang dimasukkan sejauh ini.

print("Nilai maksimum adalah:", max_value): Setelah loop selesai (ketika pengguna memasukkan 0), program mencetak nilai terbesar yang ditemukan.

Contoh Jalannya Program:

Jika pengguna memasukkan angka secara berurutan: 3,5,2,8,0 maka program akan menampilkan "Nilai maksimum adalah: 8".

