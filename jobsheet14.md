## Jobsheet 14
Muhammad Zuhdi Yudadharma <br>
244107020017 <br>
TI - 2F

## JOBSHEET – Implementasi Relation pada Filament (HasMany)

## langkah-langkah

1. Implementasi Relationship pada Form <br>
![alt text](imgjobsheet14/relation1.png)

2. Membuat Dropdown Searchable<br>
![alt text](imgjobsheet14/relation1.png)
![alt text](imgjobsheet14/relation2.png)

3. Relationship pada Model<br>
Model Post <br>
![alt text](imgjobsheet14/relation3.png)<br>
Model Category<br>
![alt text](imgjobsheet14/relation4.png)

4. Menampilkan Data Relasi pada Table <br>
![alt text](imgjobsheet14/relation5.png)

5. Membuat Relationship Manager<br>
![alt text](imgjobsheet14/relation6.png)

6. Menghubungkan Relationship Manager<br>
![alt text](imgjobsheet14/relation7.png)
![alt text](imgjobsheet14/relation8.png)

7. Hasil Relationship Manager<br>
![alt text](imgjobsheet14/relation9.png)

8. Menambahkan Kolom pada Relationship Table<br>
![alt text](imgjobsheet14/relation10.png)<br>
hasil<br>
![alt text](imgjobsheet14/relation11.png)

9. Membuat Form Create Post pada Relationship<br>
![alt text](imgjobsheet14/relation12.png)
![alt text](imgjobsheet14/relation13.png)

## Analisis & Diskusi
1. Apa perbedaan relationship() dengan options()?<Br>
relationship() mengambil data dinamis langsung dari database, sedangkan options() menggunakan data array statis yang dibuat manual.<br>

2. Mengapa searchable penting untuk dataset besar?<br>
Mencegah browser lambat atau crash. Data tidak dimuat semua sekaligus, melainkan dicari ke server hanya sesuai teks yang diketik pengguna.<br>

3. Apa fungsi Relationship Manager pada Filament?<br>
Mengelola (tambah/edit/hapus) data anak (child) langsung dari dalam halaman data induknya (parent), tanpa perlu pindah menu.<br>

4. Kapan menggunakan HasMany dan BelongsTo?<br>
BelongsTo pada model yang tabelnya menyimpan foreign key (contoh: tabel punya category_id). Gunakan HasMany pada model induk yang memiliki banyak data anak tersebut.<br>