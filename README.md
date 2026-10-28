# Lab4Web - Praktikum 4: CSS Layout

**Nama:** (Nazril Muzaky)  
**NIM:** (312510081)  
**Kelas:** (I253B)

## Struktur Folder
```
Lab4Web/
├── lab4_box.html
├── README.md
└── lab4_layout/
    ├── home.html
    ├── artikel.html
    ├── about.html
    ├── kontak.html
    └── style.css
```

## 1. Box Element & CSS Float (`lab4_box.html`)
Tiga `div` (`div1`, `div2`, `div3`) dibuat sejajar menggunakan `float: left` dan `padding: 10px`.

> Screenshot: `screenshots/01-float.png`

## 2. Clearfix (`lab4_box.html`)
`div4` ditambahkan setelah `div3` dengan `clear: left` dan `float: none` agar tampil di baris baru. Eksperimen nilai `left`, `right`, `both`:

| Nilai | Hasil pengamatan |
|-------|------------------|
| left  | (isi hasil pengamatan) |
| right | (isi hasil pengamatan) |
| both  | (isi hasil pengamatan) |

> Screenshot: `screenshots/02-clearfix.png`

## 3. Layout Sederhana (`lab4_layout/`)
| Langkah | Penjelasan | Screenshot |
|---------|------------|------------|
| Kerangka layout | Struktur `header`, `nav`, `section#hero`, `section#wrapper` (`#main` + `aside#sidebar`), `footer` | `screenshots/03-kerangka.png` |
| Header | `#container` lebar 980px, `margin: 0 auto`, `box-shadow`; header berpadding 20px | `screenshots/04-header.png` |
| Navigasi | `nav` berlatar biru, link `inline-block`, efek `:hover` & `.active` | `screenshots/05-nav.png` |
| Hero Panel | Latar abu-abu, judul, paragraf, tombol "Learn more" | `screenshots/06-hero.png` |
| Main & Sidebar | `#main` (640px) dan `#sidebar` (260px) dengan `float: left` | `screenshots/07-main-sidebar.png` |
| Sidebar Widget | `.widget-box` berisi daftar link dan teks | `screenshots/08-widget.png` |
| Footer | `clear: both`, latar gelap | `screenshots/09-footer.png` |
| Main Content (box) | 3 kolom `.box` (33.33%) dengan gambar bulat | `screenshots/10-box.png` |
| Content Artikel | `article.entry` dengan gambar float kiri dan kanan | `screenshots/11-artikel.png` |

## 4. Tugas
1. **About** (`about.html`): single layout berisi deskripsi/profil, keahlian, dan portfolio. > `screenshots/12-about.png`
2. **Contact** (`kontak.html`): form nama, email, telepon, subjek, message. > `screenshots/13-kontak.png`

## Validasi
Semua dokumen divalidasi melalui https://validator.w3.org
