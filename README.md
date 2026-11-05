## Profil Lengan Pemain — Classic & Slim

Source package ini sekarang sudah mencatat dua tipe model lengan bawaan Minecraft (vanilla). File ini berisi data profil untuk membedakan model lengan Classic dan Slim :
- Classic / Steve: lebar lengan 4 pixel.
- Slim / Alex: lebar lengan 3 pixel.

## Status pengerjaan proyek
- <badge color="success">Tersedia</badge> Kerangka awal source Fabric.
- <badge color="success">Tersedia</badge> Referensi JSON model humanoid.
- <badge color="success">Tersedia</badge> Data profil Classic dan Slim.
- <badge color="warning">Belum</badge> Custom Player Renderer.
- <badge color="warning">Belum</badge> Deteksi otomatis tipe model skin di dalam game.
- <badge color="warning">Belum</badge> Build berhasil dan file JAR.
- <badge color="warning">Belum</badge> Pengujian langsung di Minecraft.

## Catatan penting
File profil tersebut masih sebatas data konfigurasi atau referensi. Jadi, file ini belum bisa mengubah sistem rendering karakter Minecraft secara otomatis.
Supaya kedua tipe lengan benar-benar bisa diterapkan di dalam game, masih perlu dibuat sistem Custom Player Renderer dan fitur deteksi otomatis model skin.
Untuk melanjutkan implementasi dan proses build, dibutuhkan Java 25 serta environment pengembangan Fabric Minecraft 26.1.2 yang sudah terverifikasi.
Kesimpulan: Data profil Steve dan Alex sudah siap, tetapi sistem yang membuatnya bekerja langsung di dalam game masih dalam tahap pengembangan.
