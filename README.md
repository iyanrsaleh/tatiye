# PT Tatiye Digital Solusindo — Website

Landing page korporat untuk **PT Tatiye Digital Solusindo** — perusahaan teknologi
yang membangun framework, produk, dan solusi digital; induk dari framework **tatiye**
dan ekosistem **NXDOM**.

## Struktur

```
index.html   landing page (hero, tentang, layanan, produk, kontak, footer)
style.css    tema terang profesional + aksen brand #F2470B, responsif (nav mobile, grid adaptif)
index.js     i18n ID/EN (localStorage + deteksi bahasa browser) + navbar & menu
logo.png     logo perusahaan (header/footer + favicon)
logo.svg     brand mark "T" (cadangan/awal, tidak dipakai lagi)
```

## Isi halaman

1. Hero — nama perusahaan + mockup kode `NXUI.Tatiye` + CTA
2. Tentang — profil perusahaan + 3 sorotan (framework OSS, ekosistem produk, rekayasa perangkat lunak)
3. Layanan — 6 kartu (pengembangan software, framework/library, infrastruktur data, desktop & SDK, integrasi/otomasi, konsultasi)
4. Produk — kartu utama **NXUI.Tatiye** + blok penjelasan **NXDOM** (organisasi open source Nusantara yang digagas Tatiye) + grid **Ekosistem NXDOM** (7 produk: NxCode, NXC SDK, NxCode IDE, TeritipDB, NxDOM CLI, NxNode, NxSocket)
5. Kontak — web, email, GitHub
6. Footer

## Pratinjau lokal

Server dev sudah menyediakan folder ini di **http://localhost:8089/** (dengan livereload).

## Yang perlu dilengkapi

- **Kontak**: `info@tatiye.net` masih placeholder — ganti dengan email resmi, dan tambahkan
  alamat + nomor telepon di section Kontak (`index.html`).
- **Logo**: `logo.png` dipakai di header/footer + favicon (warna dominan **#F2470B**).
  `logo.svg` (brand mark "T" versi awal) disimpan sebagai cadangan, tidak dipakai lagi.
- **Layanan**: deskripsi layanan generik; sesuaikan dengan penawaran nyata perusahaan.
- **Repositori**: tautan GitHub memakai `github.com/tatiye` (framework tatiye). Samakan bila
  organisasi resmi berbeda.

## Riwayat keputusan

- Situs dibuat dari nol di folder ini (sebelumnya `index.html`/`index.js`/`style.css`/`README.md`
  kosong). Mengikuti pola situs NXDOM: statis (HTML/CSS/JS tanpa build step), dwibahasa ID/EN
  via `data-i18n`, tema gelap, navbar + lang switch. ✅ SUDAH DIEKSEKUSI
- Fakta perusahaan bersumber dari materi yang ada: nama **PT. TATIYE DIGITAL SOLUSINDO**,
  situs `tatiye.net`, framework **NXUI.Tatiye** (`github.com/tatiye/Es6framework`), dan
  relasi induk–anak dengan ekosistem **NXDOM**. Data kontak disisakan sebagai placeholder untuk
  diisi manual (tidak menebak).
- Tema diubah dari gelap ke **terang/profesional** dengan warna brand **#F2470B** (dominan pada
  `logo.png`); header/footer/favicon memakai `logo.png`. ✅ SUDAH DIEKSEKUSI
- Snippet kode hero & produk dikoreksi dari API lama `tatiyeNet`/`objectStorage` → **NXUI.Tatiye**
  (`new NXUI.Tatiye({ ... }).run()` + `templates/<route>.js`), mengacu pada referensi framework di
  `D:\eksplorasi` (`Runtime.md` + `statik/App.js` + `statik/templates/beranda.js`). ✅ SUDAH DIEKSEKUSI
- Menambah blok penjelasan **NXDOM**: organisasi open source Nusantara yang **digagas oleh PT Tatiye
  Digital Solusindo**, dengan tautan ke web NXDOM (`https://iyanrsaleh.github.io/nxdom/`, lokal
  `D:\CLI\nxdom\`). ✅ SUDAH DIEKSEKUSI
- Emoji ikon diganti **Lucide** (line icons, CDN `unpkg.com/lucide`) — kartu layanan, sorotan
  tentang, dan kontak memakai `<i data-lucide="...">` lalu `lucide.createIcons()` di `index.js`;
  ukuran/stroke diatur di `style.css`. ✅ SUDAH DIEKSEKUSI
- **Sementara** semua tautan situs `https://tatiye.net/` diarahkan ke
  `https://iyanrsaleh.github.io/tatiye/` (navbar, kartu produk, kontak, footer). Email
  `info@tatiye.net` masih placeholder (belum diubah). ✅ SUDAH DIEKSEKUSI
- Menambah tautan **Sponsor** (`https://github.com/sponsors/iyanrsaleh`) di navbar (tombol pink
  dengan ikon heart) dan footer. ✅ SUDAH DIEKSEKUSI
- Ikon **GitHub** tidak tampil karena Lucide tak lagi menyediakan ikon brand → diganti **SVG logo
  GitHub inline** (selalu tampil tanpa ketergantungan). ✅ SUDAH DIEKSEKUSI
