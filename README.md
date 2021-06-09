# Template LaTeX Buku Tugas Akhir ITS

[![latest version](https://img.shields.io/github/v/release/b201lab/template-buku-ta-its)](https://github.com/b201lab/template-buku-ta-its/releases/)
[![commits since latest version](https://img.shields.io/github/commits-since/b201lab/template-buku-ta-its/latest)](https://github.com/b201lab/template-buku-ta-its/commits/master)
[![repo size](https://img.shields.io/github/repo-size/b201lab/template-buku-ta-its)](https://github.com/b201lab/template-buku-ta-its)
[![license](https://img.shields.io/github/license/b201lab/template-buku-ta-its)](./LICENSE)
[![build document status](https://img.shields.io/github/workflow/status/b201lab/template-buku-ta-its/Build%20Document)](https://github.com/b201lab/template-buku-ta-its/actions)

Repositori ini berisi template [LaTeX](https://www.latex-project.org/) dari buku tugas akhir yang disesuaikan dengan format yang diberlakukan oleh [Institut Teknologi Sepuluh Nopember](https://www.its.ac.id/) (ITS).
Template ini terinspirasi dari repositori [rohwid/id-thesis-book-min-electics-its](https://github.com/rohwid/id-thesis-book-min-electics-its) dengan perubahan yang menyesuaikan kebutuhan pembukuan tugas akhir strata sarjana serta dengan pemangkasan isi.
Template yang dibuat saat ini baru mengikuti aturan yang diberlakukan oleh [Departemen Teknik Komputer](https://www.its.ac.id/komputer/) FTEIC - ITS dengan sedikit penyesuaian.
Sehingga, secara penuh template ini belum mewakili aturan yang berlaku secara umum di setiap departemen yang ada di ITS.

> Perlu diketahui, template ini bukanlah template resmi yang dikeluarkan oleh ITS maupun departemen-departemen yang ada di bawah naungan ITS.

> Lihat halaman [Release](https://github.com/b201lab/template-buku-ta-its/releases) untuk hasil PDF dari template ini, atau klik di [sini](https://github.com/b201lab/template-buku-ta-its/releases/download/v1.1/main.pdf).

## Fitur

- Format ukuran halaman, margin, dan font yang disesuaikan dengan aturan yang berlaku di ITS.
- Disertai halaman-halaman yang diperlukan seperti sampul, lembar pengesahan, kata pengantar, dsb.
- Pembuatan daftar isi, daftar gambar, daftar tabel, dan daftar pustaka secara otomatis.
- Penomoran halaman, gambar, tabel, dan referensi secara otomatis.
- Penambahan gambar, persamaan ilmiah, potongan kode, dan tabel pada dokumen.
- Kompilasi dokumen secara otomatis menggunakan [GitHub Actions](https://github.com/features/actions).

## Cara Menggunakan Template

Bagian utama dokumen terletak pada file [`main.tex`](./main.tex) yang digunakan untuk mengatur package LaTeX yang digunakan serta file lain yang akan dimasukkan pada dokumen.
Setelah kompilasi dilakukan, hasilnya akan ada beberapa file `main` dengan format yang berbeda.
Yang terutama adalah file `main.pdf` yang merupakan hasil akhir dari proses kompilasi dokumen.

Selain file `main.tex`, ada juga beberapa bagian lain dari template ini yang bisa diubah, seperti:
- **[`abstrak`](./abstrak)**, berisi file `*.tex` untuk abstrak dalam Bahasa Indonesia dan Bahasa Inggris.
- **[`bab`](./bab)**, berisi file `*.tex` dari setiap bab yang akan dimasukkan pada buku tugas akhir.
- **[`gambar`](./gambar)**, berisi file `*.jpg`, `*.png`, maupun format gambar lain yang akan dimasukkan pada buku tugas akhir.
- **[`lainnya`](./lainnya)**, berisi file `*.tex` dari halaman lain seperti lembar pengesahan, kata pengantar, biografi penulis, dsb. yang akan dimasukkan pada buku tugas akhir.
- **[`program`](./program)**, berisi file kode program yang akan dimasukkan pada dokumen.
- **[`pustaka/pustaka.bib`](./pustaka/pustaka.bib)**, berisi daftar pustaka yang akan dimasukkan pada dokumen.
- **[`sampul`](./sampul)**, berisi file `*.tex` dari sampul luar dan dalam untuk buku tugas akhir.

> Penjelasan lebih lanjut mengenai penggunaan template ini akan dijelaskan dengan comment yang tersedia pada setiap file yang ada.

## Contoh Penggunaan Template

Berikut adalah daftar repositori lain yang menggunakan template yang berasal dari repositori ini:
- [threeal/buku-ta-simulasi-robot](https://github.com/threeal/buku-ta-simulasi-robot).
- [chillytaka/last_boss](https://github.com/chillytaka/last_boss).

## Lisensi

Kode sumber yang ada pada repositori ini dilisensikan di bawah [Lisensi MIT](./LICENSE).
