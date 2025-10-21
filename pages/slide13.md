---
layout: center
---

## Contoh
```cpp
#include <iostream>
using namespace std;

struct NilaiMahasiswa {
    string nama;
    double kuis, uts, uas;
};

double hitungRata(const NilaiMahasiswa &mhs) {
    return (mhs.kuis + mhs.uts + mhs.uas) / 3.0;
}

NilaiMahasiswa inputData() {
    NilaiMahasiswa temp;
    cout << "Masukkan nama: ";
    getline(cin, temp.nama);
    cout << "Nilai kuis, UTS, UAS: ";
    cin >> temp.kuis >> temp.uts >> temp.uas;
    return temp;
}

int main() {
    NilaiMahasiswa mahasiswa = inputData();
    cout << mahasiswa.nama << " memiliki rata-rata " << hitungRata(mahasiswa);
}

```

<div style="position: absolute; bottom: 20px; right: 40px; font-size: 0.8em; opacity: 0.7;">
Fungsi dan Record
</div>