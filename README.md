
#include <stdio.h>

int main() {
    // Deklarasi variabel
    float harga_awal = 150000;
    float diskon_persen = 12.5;
    float diskon, harga_bersih;

    // Menghitung diskon
    diskon = (diskon_persen / 100) * harga_awal;

    // Menghitung harga bersih setelah diskon
    harga_bersih = harga_awal - diskon;

    // Menampilkan hasil
    printf("Harga awal : Rp %.2f\n", harga_awal);
    printf("Diskon : Rp %.2f (%.1f%%)\n", diskon, diskon_persen);
    printf("Harga setelah diskon : Rp %.2f\n", harga_bersih);

    return 0;
}
