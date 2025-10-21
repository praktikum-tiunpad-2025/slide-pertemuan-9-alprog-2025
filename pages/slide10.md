---
layout: center
---

## Record Sebagai Nilai Balik (Return Value)
Kadang kamu mau fungsi yang menghasilkan record baru.
Contohnya fungsi buat bikin record mahasiswa:
```cpp
NilaiMahasiswa buatMahasiswa(string nama, double kuis, double uts, double uas) {
    NilaiMahasiswa temp;
    temp.nama = nama;
    temp.kuis = kuis;
    temp.uts = uts;
    temp.uas = uas;
    return temp;
}
```
Lalu di main:
```cpp
int main() {
    NilaiMahasiswa mhsBaru = buatMahasiswa("Andi", 90, 85, 88);
    cout << mhsBaru.nama << " punya nilai UAS " << mhsBaru.uas;
}

```
Dengan begitu, fungsi bisa “membangun” record baru dan mengembalikannya, mirip kayak bikin objek baru.

<div style="position: absolute; bottom: 20px; right: 40px; font-size: 0.8em; opacity: 0.7;">
Fungsi dan Record
</div>
