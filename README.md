# Robo Beat

Drum machine sederhana dengan suara sintesis khas 80an, terinspirasi seri Roland "Human Rhythm Composer" (R-5/R-8). Teman ROBO/SOLO untuk Robo Galaktika. Jalan di browser HP, tanpa install dari store.

## Fitur

- **Grid 16 langkah, 8 instrumen**: kick, snare, clap, hat, open hat, tom hi, tom lo, cowbell. Semua suara disintesis (bergaya 808 dan Simmons).
- **Ketuk kotak**: mati → pukul → aksen → mati.
- **Pola A dan B**: berganti di akhir bar, jadi tidak pernah meleset. **FILL** main satu bar lalu kembali.
- **HUMAN**: variasi kecil timing dan dinamika supaya beat tidak kaku, idenya dari R-5.
- **Swing**, **tempo** dengan tombol tap, dan **mute** per instrumen (ketuk nama instrumen).
- **Pad besar** untuk dimainkan langsung.
- **7 pola siap pakai**: Synth Pop, New Wave, Disco 80an, Electro 808, Simmons 80an, Ballad, Kosong.
- **Penyimpanan otomatis** di perangkat, dengan tombol Urungkan saat memuat pola atau mengosongkan bagian.
- **Keyboard**: spasi untuk play/stop.

## Online-kan dengan GitHub Pages

1. Buat repo baru di GitHub, misalnya `robo-beat`.
2. Upload semua file di folder ini (**Add file → Upload files**).
3. Buka **Settings → Pages**, lalu pada *Source* pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, dan simpan.
4. Tunggu 1–2 menit. Aplikasinya ada di `https://<username>.github.io/robo-beat/`.

## Pasang di HP

Buka alamat tadi di Chrome atau Safari, lalu pilih **Tambahkan ke layar utama**.

## File

| File | Fungsi |
|---|---|
| `index.html` | Seluruh aplikasi |
| `manifest.webmanifest` | Data untuk "Tambahkan ke layar utama" |
| `icon-192.png`, `icon-512.png` | Ikon aplikasi |
| `.nojekyll` | Supaya GitHub Pages menyajikan file apa adanya |
