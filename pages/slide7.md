### Array Sebagai Member Record
Sebuah record dapat memiliki array sebagai membernya.
```cpp twoslash
struct Mahasiswa {
    string nama;
    int nilaiTugas[5];
};
```

Untuk mengakses salah satu indeks dari array tersebut, pertama digunakan dot operator untuk mengakses member array yang diinginkan, kemudian kurung siku untuk mengakses indeks tersebut.

```cpp twoslash
int main() {
    Mahasiswa mhsAmbis;
    
    cin >> mhsAmbis.nama;
    
    for (int i = 0; i < 5; i++) {
        cin >> mhsAmbis.nilaiTugas[i];
    }
}
```
<div style="position: absolute; bottom: 20px; left: 40px; font-size: 0.8em; opacity: 0.7;">
Array and Record
</div>