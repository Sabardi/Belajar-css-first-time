Dalam pembuatan layout menggunakan tata letak flexbox, terdapat beberapa properti CSS yang sering digunakan untuk mengontrol tata letak elemen-elemen di dalam kontainer flex. Berikut adalah beberapa properti yang umum digunakan:

1. **display: flex;**
   - Mengubah elemen menjadi kontainer flex, sehingga elemen di dalamnya dapat diatur menggunakan properti flexbox.

2. **flex-direction:**
   - Menentukan arah sumbu utama (main axis) kontainer flex. Nilai yang umum digunakan adalah `row` (default), `row-reverse`, `column`, dan `column-reverse`.

3. **justify-content:**
   - Mengatur penyebaran atau penempatan elemen-elemen di sepanjang sumbu utama kontainer flex. Nilai yang umum digunakan adalah `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, dan `space-evenly`.

4. **align-items:**
   - Mengatur penempatan elemen-elemen di sepanjang sumbu silang (cross axis) kontainer flex. Nilai yang umum digunakan adalah `flex-start`, `flex-end`, `center`, `baseline`, dan `stretch`.

5. **align-self:**
   - Mengatur penempatan individual elemen di sepanjang sumbu silang kontainer flex. Nilai yang umum digunakan mirip dengan `align-items`.

6. **flex-grow:**
   - Mengatur seberapa besar elemen dapat memperluas dirinya di dalam kontainer flex jika ada ruang tambahan yang tersedia.

7. **flex-shrink:**
   - Mengatur seberapa besar elemen dapat menyusut jika ruang di dalam kontainer flex terbatas.

8. **flex-basis:**
   - Menentukan ukuran awal elemen sebelum fleksibilitas dari `flex-grow` atau `flex-shrink` diterapkan.

9. **flex:**
   - Singkatan untuk pengaturan `flex-grow`, `flex-shrink`, dan `flex-basis` sekaligus.

10. **order:**
    - Mengatur urutan tampilan elemen dalam kontainer flex.

11. **margin, padding, width, height:**
    - Properti umum untuk mengatur margin, padding, lebar, dan tinggi elemen dalam layout flexbox.

Dengan kombinasi properti-properti di atas, Anda dapat membuat berbagai jenis tata letak yang fleksibel dan responsif menggunakan tata letak flexbox.