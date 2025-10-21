---
layout: center
---

## Record Sebagai Parameter Fungsi
Misal kita punya record:
```cpp
struct NilaiMahasiswa {
    string nama;
    double kuis, uts, uas;
};
```
Sekarang kita mau bikin fungsi buat ngitung rata-rata nilai mahasiswa.
Kita tinggal kirim satu `NilaiMahasiswa` ke fungsi itu:
```cpp
double hitungRata(NilaiMahasiswa mhs) {
    return (mhs.kuis + mhs.uts + mhs.uas) / 3.0;
}
```
Pemanggilannya kayak gini:
```cpp
int main() {
    NilaiMahasiswa dicky = {"Dicky", 80, 75, 90};
    cout << "Rata-rata: " << hitungRata(dicky);
}
```
<div style="position: absolute; bottom: 20px; right: 40px; font-size: 0.8em; opacity: 0.7;">
Fungsi dan Record
</div>
