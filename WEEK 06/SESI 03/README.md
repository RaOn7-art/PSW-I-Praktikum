1. GAMBAR FLEKSIBEL
    Tindakan: menambahkan img { max-width: 100%; height: auto; } di CSS.
    Hasil:  Gambar tidak 404 dan gambar menyusut sesuai max-width dan height auto.

2. KANDIDAT RESOLUSI
    Tindakan: menambahkan <img src="foto-640.jpg"
 srcset="foto-320.jpg 320w, foto-640.jpg 640w"
 sizes="(min-width: 48rem) 50vw, 92vw"
 width="640" height="360" alt="Kegiatan diskusi mahasiswa"> dalam CSS.
    Hasil: Gambar mengikuti besar 640w jika layar besar dan 320w jika layar dikecilkan. currentSrc di Console dan Elements tersedia.

3. FLUID FONT DAN CONTAINER QUERY
    Tindakan: cek Font-Size 375px: 28px
              cek Font-Size 1440px: 48px
              Perbedaan query dari perubahan lebar container(tanpa mengubah viewport): 400px tidak terjadi overflow, 600px terjadi overflow

4. REDUCED MOTION DAN AUDIT
    Tindakan: Mengaktifkan reduced motion
    Hasil: tidak ada pengurangan gerakan karena tidak menggunakan transisi atau animasi