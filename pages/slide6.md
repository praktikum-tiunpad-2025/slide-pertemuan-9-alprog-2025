# Array dan Record
Ada dua bentuk interaksi antara array dan record, yaitu array of records dan array sebagai member record
### Array of Record
Untuk mengumpulkan banyak variabel record di satu tempat, dapat digunakan array.
Untuk mengakses member dari salah satu variabel record pada array, pertama digunakan kurung siku untuk mengakses elemen tertentu dari variabel array, kemudian operator dot untuk mengakses suatu member dari elemen struct tersebut.

```cpp twoslash
struct Ktp {
    string nama;
    int tahunLahir;
};

int main() {
    Ktp kumpulanKtp[10];
    
    for (int i = 0; i < 10; i++) {
        cin >> kumpulanKtp[i].nama >> kumpulanKtp[i].tahunLahir;
    }
}
```

<div style="position: absolute; bottom: 20px; left: 40px; font-size: 0.8em; opacity: 0.7;">
Array and Record
</div>