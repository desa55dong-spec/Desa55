DESA55 WEBSITE — SIAP DEPLOY KE NETLIFY

Isi:
- index.html: halaman utama, SEO dasar, canonical, Open Graph, schema.org, dan Google Search Console verification.
- styles.css, script.js: tampilan responsif dan navigasi mobile.
- assets/: seluruh 9 gambar yang Anda berikan, dioptimalkan ke WebP.
- robots.txt dan sitemap.xml: petunjuk crawling mesin pencari.
- _headers: cache aset statis agar kunjungan berikutnya lebih cepat.

CARA DEPLOY:
1. Ekstrak ZIP ini.
2. Buka https://app.netlify.com/drop
3. Seret folder desa55-website (folder yang berisi index.html) ke halaman Netlify Drop.
4. Jika ingin memakai alamat desa55alam.netlify.app yang sudah ada, deploy ke site Netlify yang sama melalui dashboard Netlify > Deploys. Jangan membuat site baru bila ingin mempertahankan subdomain.
5. Setelah terbit, buka https://desa55alam.netlify.app/ dan pastikan halaman tampil.
6. Di Google Search Console, pilih properti URL-prefix https://desa55alam.netlify.app/ lalu gunakan verifikasi HTML tag. Tag verifikasi sudah dipasang di <head> index.html.
7. Kirim sitemap: https://desa55alam.netlify.app/sitemap.xml

CATATAN:
- Semua tombol ajakan (MASUK / KUNJUNGI DESA55) diarahkan ke https://jali.me/desa55.
- Situs dibuat statis tanpa framework, database, maupun permintaan font eksternal; gambar dikonversi ke WebP dan gambar non-utama memakai lazy loading.
- SEO membantu mesin pencari memahami situs, tetapi tidak menjamin posisi/ranking tertentu. Setelah deploy, verifikasi domain dan minta pengindeksan di Search Console.
- Google Fonts dimuat dari CDN; jika ingin performa paling konsisten, font fallback sistem tetap tersedia.
