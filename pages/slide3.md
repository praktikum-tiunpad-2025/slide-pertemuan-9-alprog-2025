---
transition: slide-down
---
## Pendefinisian Record
Pada C++, kita mendefinisikan sebuah tipe data record menggunakan keyword struct.

```cpp twoslash
// 1          2
struct NilaiMahasiswa { 
    string namaMahasiswa; //3
    double nilaiKuis;
    double nilaiUTS;
    double nilaiUAS;
}; //4
```

Keterangan:

1. Keyword struct digunakan sebagai penanda.
2. NilaiMahasiswa merupakan nama dari tipe data record.
3. Didefinisikan variabel-variabel yang akan menjadi member record tersebut. Masing-masing member memiliki tipe data, sama seperti deklarasi variabel pada main.
4. Jangan lupa titik koma!

<div style="position: absolute; bottom: 20px; left: 40px; font-size: 0.8em; opacity: 0.7;">
Record
</div>