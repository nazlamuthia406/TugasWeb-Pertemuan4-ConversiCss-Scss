
# Tugas Web Pertemuan 4 - Konversi CSS ke SCSS (7-1 Pattern)

**Nama:** Nazla Muthia
**NIM:** 4253250052
**Judul:** Landing Page Pribadi - Konversi CSS ke SCSS

## Link Live Demo

https://nazlamuthia406.github.io/TugasWeb-Pertemuan4-ConversiCss-Scss/

## Deskripsi Tugas

Konversi CSS existing dari Pertemuan 2 ke SCSS dengan struktur modular 7-1 pattern.

## Requirements Terpenuhi

1. ✅ Konversi CSS existing ke SCSS
2. ✅ Nesting max 3 level (di _header.scss, _card.scss, dll)
3. ✅ Struktur 7-1 pattern (abstracts, components, main.scss)
4. ✅ Variables untuk colors & spacing (di _variables.scss)
5. ✅ Minimal 3 mixins reusable (flex-center, card, responsive)
6. ✅ Menggunakan @use (bukan @import)
7. ✅ Minimal 1 @each / @for loop (untuk generate utility spacing)
8. ✅ Compile dengan Dart SASS (Live Sass Compiler)

## Struktur Folder

SCSS/
├── abstracts/
│   ├── _variables.scss
│   └── _mixins.scss
├── components/
│   ├── _header.scss
│   ├── _card.scss
│   └── ...
├── main.scss
└── main.css (hasil compile)

## Cara Compile

Pakai extension Live Sass Compiler -> Watch Sass -> otomatis jadi main.css
