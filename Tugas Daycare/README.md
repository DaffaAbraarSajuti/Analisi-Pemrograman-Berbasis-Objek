# TUGAS ANALISIS DAN PERANCANGAN BERORRIENTASI OBJEK
---
## Nama : Daffa Abraar Sajuti
## NPM  : 4522210040
---
# SISTEM DAYCARE
## 1. Aktor 
- Orang Tua
- Staf
- Admin
---
## 2. Usecase Diagram
![alt text](https://github.com/DaffaAbraarSajuti/Analisis-dan-Perancangan-Berorientasi-Objek/blob/main/Tugas%20Daycare/Usecase%20Daycare.png?raw=true)

----
## 3. Class Diagram
![alt text](https://github.com/DaffaAbraarSajuti/Analisis-dan-Perancangan-Berorientasi-Objek/blob/main/Tugas%20Daycare/ClassDiagram%20Daycare.png?raw=true)

---
## 4. ERD 
![alt text](https://github.com/DaffaAbraarSajuti/Analisis-dan-Perancangan-Berorientasi-Objek/blob/main/Tugas%20Daycare/ERD%20Daycare.png?raw=true)
### Penjelasan Mengenai ERD :
- Anak
  - Beberapa anak dapat memiliki satu orang tua
  - Satu anak memiliki satu kehadiran
  - Satu anak memilik satu jadwal
  - Satu anak mempunyai satu laporan keseluruhan
- Orang Tua
  - Orang tua bisa memiliki beberapa anak
  - Orang tua bisa melihat beberapa jadwal
  - Oang tua dapat melihat kehadiran (anaknya)
  - Orang tua dapat melihat laporan (anaknya)
- Staf
  - staf dapat mencatat satu kehadiran anak
  - staf dapat melihat beberapa jadwal
  - staf membuat satu laporan anak
- Jadwal
  - Jadwal dapat dilihat oleh orang tua
  - Jadwal dapat dilihat oleh staf
  - satu jadwal dimiliki oleh satu anak
- Kehadiran
  - Kehadiran dapat dilihat oleh orang tua
  - Kehadiran di catat oleh staf
  - satu kehadiran dimiliki oleh satu anak
- Laporan
  - satu laporan dipunyai oleh satu anak
  - laporan dapat dilihat oleh orang tua
  - laporan dibuat oleh staf
----
