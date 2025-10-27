# UTS_KOMPUTER-VISION_RIVA-TEGAR-SETYA
UTS_ComputerVision


## Deskripsi Karakter
Karakter ini terinspirasi dari **Minion** dengan bentuk tubuh **kotak sederhana**.  
Dibuat menggunakan fungsi-fungsi dasar OpenCV seperti `cv2.rectangle`, `cv2.circle`, `cv2.line`, dan `cv2.putText`.

## Transformasi yang Digunakan
1. **Translasi (Translation):** Menggeser posisi karakter menggunakan `cv2.warpAffine`.
   <img width="600" height="600" alt="roket_geser" src="https://github.com/user-attachments/assets/e42e670c-4062-4c4c-909d-a47dea631c5e" />

3. **Rotasi (Rotation):** Memutar karakter 45 derajat dengan `cv2.getRotationMatrix2D`
4. <img width="600" height="600" alt="roket_diputar_-45" src="https://github.com/user-attachments/assets/f0c545d7-364f-4d73-be96-9a50db83e3ea" />

5. **Resize:** Mengubah ukuran gambar menjadi 70% ukuran asli.
6. **Crop:** Memotong sebagian area wajah minion.

## Operasi yang Digunakan
- `cv2.addWeighted()` → menggabungkan dua gambar dengan bobot berbeda.
- `cv2.bitwise_not()` → operasi logika invers untuk menghasilkan efek negatif.



![Final Output](output/final.png)
