# PT Tatiye Digital Solusindo — Website

Landing page korporat untuk **PT Tatiye Digital Solusindo** — perusahaan teknologi
yang membangun framework, produk, dan solusi digital; induk dari framework **tatiye**
dan ekosistem **NXDOM**.

## Struktur

```
index.html   landing page (hero, tentang, layanan, produk, kontak, footer)
style.css    tema gelap + aksen biru-cyan, responsif (nav mobile, grid adaptif)
index.js     i18n ID/EN (localStorage + deteksi bahasa browser) + navbar & menu
logo.svg     favicon / brand mark "T"
```

## Isi halaman

1. Hero — nama perusahaan + mockup kode `tatiyeNet` + CTA
2. Tentang — profil perusahaan + 3 sorotan (framework OSS, ekosistem produk, rekayasa perangkat lunak)
3. Layanan — 6 kartu (pengembangan software, framework/library, infrastruktur data, desktop & SDK, integrasi/otomasi, konsultasi)
4. Produk — kartu utama **tatiye / tatiyeNet** + grid **Ekosistem NXDOM** (7 produk: NxCode, NXC SDK, NxCode IDE, TeritipDB, NxDOM CLI, NxNode, NxSocket)
5. Kontak — web, email, GitHub
6. Footer

## Pratinjau lokal

Server dev sudah menyediakan folder ini di **http://localhost:8089/** (dengan livereload).

## Yang perlu dilengkapi

- **Kontak**: `info@tatiye.net` masih placeholder — ganti dengan email resmi, dan tambahkan
  alamat + nomor telepon di section Kontak (`index.html`).
- **Logo**: `logo.svg` saat ini brand mark "T" sederhana — ganti bila ada logo resmi.
- **Layanan**: deskripsi layanan generik; sesuaikan dengan penawaran nyata perusahaan.
- **Repositori**: tautan GitHub memakai `github.com/tatiye` (framework tatiye). Samakan bila
  organisasi resmi berbeda.

## Riwayat keputusan

- Situs dibuat dari nol di folder ini (sebelumnya `index.html`/`index.js`/`style.css`/`README.md`
  kosong). Mengikuti pola situs NXDOM: statis (HTML/CSS/JS tanpa build step), dwibahasa ID/EN
  via `data-i18n`, tema gelap, navbar + lang switch. ✅ SUDAH DIEKSEKUSI
- Fakta perusahaan bersumber dari materi yang ada: nama **PT. TATIYE DIGITAL SOLUSINDO**,
  situs `tatiye.net`, framework **tatiye/tatiyeNet** (`github.com/tatiye/Es6framework`), dan
  relasi induk–anak dengan ekosistem **NXDOM**. Data kontak disisakan sebagai placeholder untuk
  diisi manual (tidak menebak).
