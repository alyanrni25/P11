# NO 2
## code cpp

```
#include <iostream>
#include <string>

class Mahasiswa {
private:
    std::string nama;
    int umur;
    std::string prodi;
    std::string fakultas;

public:
    Mahasiswa(std::string n, int u, std::string p, std::string f) {
        nama = n;
        umur = u;
        prodi = p;
        fakultas = f;
    }

    void setNama(std::string n) {
        nama = n;
    }

    std::string getNama() {
        return nama;
    }

    void setUmur(int u) {
        umur = u;
    }

    int getUmur() {
        return umur;
    }

    void setProdi(std::string p) {
        prodi = p;
    }

    std::string getProdi() {
        return prodi;
    }

    void setFakultas(std::string f) {
        fakultas = f;
    }

    std::string getFakultas() {
        return fakultas;
    }

    void tampilkanInfo() {
        std::cout << "Nama: " << nama << std::endl;
        std::cout << "Umur: " << umur << std::endl;
        std::cout << "Prodi: " << prodi << std::endl;
        std::cout << "Fakultas: " << fakultas << std::endl;
    }
};

int main() {
    Mahasiswa mhs("Alya", 19, "Agribisnis", "Fakultas Sains Dan Teknologi");

    std::cout << "Nama: " << mhs.getNama() << std::endl;
    std::cout << "Umur: " << mhs.getUmur() << std::endl;
    std::cout << "Prodi: " << mhs.getProdi() << std::endl;
    std::cout << "Fakultas: " << mhs.getFakultas() << std::endl;

    return 0;
}

```

### Capture Hasil Running
![Screenshot 2024-05-27 085139](https://github.com/alyanrni25/P11/assets/156888432/cba60e7a-1245-4116-a371-14d6e3f1df4c) 
