# Website Prodi DIII Keperawatan Langsa

Website statis siap deploy ke Netlify dengan Decap CMS.

## Deploy
1. Upload folder ini ke repository GitHub.
2. Di Netlify pilih Add new project > Import an existing project.
3. Pilih repository GitHub.
4. Build command dikosongkan.
5. Publish directory: `.`
6. Deploy.

## Mengaktifkan CMS
Di Netlify buka Project configuration > Identity dan aktifkan Identity, lalu aktifkan Git Gateway bila tersedia pada konfigurasi Netlify Anda. Setelah itu buka `/admin/`.

## Catatan
- Ganti logo "PKA" dengan logo resmi melalui `index.html`/CSS.
- Ganti tautan website resmi dan data kontak dengan data institusi.
- Supabase belum diperlukan untuk website berita sederhana; dapat ditambahkan saat membutuhkan database/login khusus.
