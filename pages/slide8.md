---
layout: center
---
<div style="max-width: 800px; ; margin: 0 auto;">

# Nested Record

Sebuah record dapat memiliki member yang merupakan record lain seperti contoh berikut.

```cpp
struct Alamat {
    int nomorBangunan;
    string namaJalan;
};

struct Ktp {
    string nama;
    int tahunLahir;
    Alamat alamatRumah;
};
```
Untuk mengakses member pada nested record, dilakukan operator dot berkali-kali.
```cpp
int main() {
    Ktp dataSaya;
    
    dataSaya.alamatRumah.nomorBangunan = 165;
    dataSaya.alamatRumah.namaJalan = "Hegarmanah";
}
```
Tidak ada batasan mengenai seberapa dalam nesting dapat dilakukan. Namun, pada C++, sebuah record tidak dapat memiliki diri sendiri sebagai membernya.




</div>

<div style="position: absolute; bottom: 20px; right: 40px; font-size: 0.8em; opacity: 0.7;">
Nested Record
</div>
