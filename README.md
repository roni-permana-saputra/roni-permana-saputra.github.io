# Website pribadi Roni Permana Saputra

Website statis untuk repositori **roni-permana-saputra/roni-permana-saputra.github.io**. 

## Isi
- index.html: biodata, minat riset, kontak.
- cv.html: CV (posisi, pendidikan, daftar publikasi, paten, keahlian) dan tombol cetak/simpan PDF.
- research.html: fusi sensor dan lokalisasi, personal mobility (SEATER), robot inspeksi, ResQbot, Deep_GPPC, PythonMobileRobot.
- publications.html: 25 publikasi (jurnal, konferensi, pracetak) per tahun dengan tautan DOI, arXiv, dan kode.
- assets/site.css dan assets/site.js: tampilan responsif dan menu ponsel.
- images/ron.jpg: foto dari website Anda yang lama.
- .nojekyll: melewati pemrosesan Jekyll.

## Publikasi ke GitHub Pages
1. Ekstrak ZIP, lalu unggah isi folder ini ke akar repositori roni-permana-saputra.github.io (jangan unggah file ZIP-nya).
2. Simpan perubahan ke branch master yang sudah ada, atau branch publikasi yang Anda gunakan.
3. Buka Settings → Pages → Build and deployment.
4. Pilih Deploy from a branch, branch tempat file disimpan, dan /(root), kemudian Save.
5. Alamat website: https://roni-permana-saputra.github.io/

Repositori publik sudah ada. Pengunggahan harus dilakukan dengan akun yang memiliki akses tulis. Folder ini adalah versi lokal siap unggah; tersedianya folder tidak menandakan bahwa website sudah diterbitkan.

Panduan resmi: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Mengedit isi
Edit teks langsung pada halaman HTML terkait. Menu dan footer ada di setiap halaman; ubah pada semua halaman jika diperlukan. Tampilan (warna, font, jarak) diatur di assets/site.css; warna ada di bagian :root paling atas, termasuk versi mode gelap. Font Inter dan Source Serif 4 dimuat dari Google Fonts. Ganti foto dengan file images/ron.jpg. CV merupakan ringkasan berdasarkan informasi pada website lama, bukan riwayat pekerjaan lengkap. Publikasi sengaja diberi label Selected publications; ini bukan daftar lengkap hingga 2026.

## Sumber
Biodata, pendidikan, email, dan foto: repositori website Anda (snapshot b511748).
Referensi tampilan: https://digbychappell.github.io/
Publikasi:
- Implementation of Real-Time Lane Detection on Autonomous Mobile Robot (2024): https://arxiv.org/abs/2411.14873
- Autonomous Docking Method via Non-linear Model Predictive Control (2023): https://arxiv.org/abs/2312.16629
- Wheel Odometry-Based Localization for Autonomous Wheelchair (2023): https://arxiv.org/abs/2405.02290
- ResQbot 2.0: An Improved Design of a Mobile Rescue Robot with an Inflatable Neck Securing Device for Safe Casualty Extraction (2021): https://www.mdpi.com/2076-3417/11/12/5414
- Hierarchical Decomposed-Objective Model Predictive Control for Autonomous Casualty Extraction (2021): https://kormushev.com/papers/Saputra_ACCESS-2021.pdf
- Sim-to-Real Learning for Casualty Detection from Ground Projected Point Cloud Data (2019): https://arxiv.org/abs/1908.03057

File lama index_backup, gambar lain, dan folder deniro-tutorial dipertahankan dari repositori asal. Tidak ada analitik, formulir, atau pengumpulan data pengunjung yang ditambahkan.
