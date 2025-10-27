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
6. <img width="800" height="800" alt="roket_diubah_ukuran_800x800" src="https://github.com/user-attachments/assets/34854373-b2b6-4e3d-97e1-1be58ce26456" />

7. **Crop:** Memotong sebagian badan roket.
8. <img width="100" height="200" alt="roket_dipotong_badan" src="https://github.com/user-attachments/assets/963b9154-0ed2-49be-9581-e232d31ae1a1" />

operasi yang digunakan : 
np.full (NumPy)
cv2.line
cv2.circle
cv2.fillPoly
cv2.polylines
cv2.ellipse

![Final Output](output/final.png)
