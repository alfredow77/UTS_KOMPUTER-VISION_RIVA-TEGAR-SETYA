# UTS_KOMPUTER-VISION_RIVA-TEGAR-SETYA
UTS_ComputerVision


## Deskripsi Karakter
Karakter ini terinspirasi dari **Minion** dengan bentuk tubuh **kotak sederhana**.  
Dibuat menggunakan fungsi-fungsi dasar OpenCV seperti `cv2.rectangle`, `cv2.circle`, `cv2.line`, dan `cv2.putText`.

## Transformasi yang Digunakan
1. **Translasi (Translation):** Menggeser posisi karakter menggunakan `cv2.warpAffine`.
   <img width="600" height="600" alt="roket_geser" src="https://github.com/user-attachments/assets/e42e670c-4062-4c4c-909d-a47dea631c5e" />

3. **Rotasi (Rotation):** Memutar karakter 20 derajat dengan `cv2.getRotationMatrix2D`
4. **Resize:** Mengubah ukuran gambar menjadi 70% ukuran asli.
5. **Crop:** Memotong sebagian area wajah minion.
6. **AddWeighted:** Menggabungkan karakter dengan latar belakang berwarna lembut.
7. **Bitwise Not:** Membalik warna (efek negatif).

## Operasi yang Digunakan
- `cv2.addWeighted()` → menggabungkan dua gambar dengan bobot berbeda.
- `cv2.bitwise_not()` → operasi logika invers untuk menghasilkan efek negatif.



![Final Output](output/final.png)
