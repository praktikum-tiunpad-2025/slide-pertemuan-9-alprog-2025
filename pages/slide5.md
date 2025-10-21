---
layout: center
---
````md magic-move {lines: true}
```cpp {*|1-6|9-14|16-22|*} twoslash
struct NilaiMahasiswa { 
    string nama;
    double nilaiKuis;
    double nilaiUTS;
    double nilaiUAS;
};

int main() {
    NilaiMahasiswa mhsAmbis;
    
    mhsAmbis.nama = "Dicky Rahma Hermawan";
    mhsAmbis.nilaiKuis = 75.25;
    mhsAmbis.nilaiUTS = 70.50;
    mhsAmbis.nilaiUAS = 100.0;
    
    cout << mhsAmbis.nilaiUAS; // 100.0
    
    if (mhsAmbis.nilaiUTS <= 80) {
        cout << mhsAmbis.nama 
             << " perlu melakukan remedial UTS!";
        // Dicky Rahma Hermawan perlu melakukan remedial UTS!
    }   
}
```
````
<div style="position: absolute; bottom: 20px; left: 40px; font-size: 0.8em; opacity: 0.7;">
Record
</div>