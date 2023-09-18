# Template LaTeX Buku Tugas Akhir ITS

[![latest version](https://img.shields.io/github/v/release/b201lab/template-buku-ta-its)](https://github.com/b201lab/template-buku-ta-its/releases/)
[![commits since latest version](https://img.shields.io/github/commits-since/b201lab/template-buku-ta-its/latest)](https://github.com/b201lab/template-buku-ta-its/commits/master)
[![repo size](https://img.shields.io/github/repo-size/b201lab/template-buku-ta-its)](https://github.com/b201lab/template-buku-ta-its)
[![license](https://img.shields.io/github/license/b201lab/template-buku-ta-its)](./LICENSE)
[![build status](https://img.shields.io/github/actions/workflow/status/b201lab/template-buku-ta-its/ci.yaml?branch=main)](https://github.com/b201lab/template-buku-ta-its/actions/workflows/ci.yaml)

Repositori ini berisi template [LaTeX](https://www.latex-project.org/) dari buku tugas akhir yang disesuaikan dengan format yang diberlakukan oleh [Institut Teknologi Sepuluh Nopember](https://www.its.ac.id/) (ITS). Template yang ada pada repositori ini bersifat universal dan bisa digunakan oleh setiap departemen yang ada di ITS karena sudah mengikuti aturan resmi yang berdasarkan pada [SK Rektor ITS No. 280 Tahun 2022](https://www.its.ac.id/pendidikan/wp-content/uploads/sites/112/2022/03/280-SK-Rektor-ttg-Pedoman-Penyusunan-Laporan-Tugas-Akhir-Sarjana-Sarjana-Terapan.pdf) tentang pedoman penyusunan laporan tugas/proyek akhir program sarjana dan sarjana terapan.

> Contoh file PDF dari template ini bisa dilihat di [sini](https://b201lab.github.io/template-buku-ta-its/buku-ta.pdf).

## Fitur

- Format ukuran halaman, margin, dan font yang disesuaikan dengan aturan yang berlaku di ITS.
- Disertai bagian-bagian yang diperlukan seperti pengesahan, latar belakang, tinjauan pustaka, dsb.
- Pembuatan daftar pustaka secara otomatis.
- Penomoran gambar dan referensi secara otomatis.
- Penambahan gambar dengan format JPEG, PNG, maupun format lain pada dokumen.
- Pembuatan daftar, persamaan ilmiah, dan tabel pada dokumen.
- Kompilasi dokumen secara otomatis menggunakan [GitHub Actions](https://github.com/features/actions).

## Cara Menggunakan Template

Bagian utama dokumen terletak pada file [`main.tex`](./main.tex) yang digunakan untuk mengatur package LaTeX yang digunakan serta file lain yang akan diinputkan pada dokumen.
Setelah kompilasi dilakukan, hasilnya akan ada beberapa file `main` dengan format yang berbeda.
Yang terutama adalah file `main.pdf` yang merupakan hasil akhir dari proses kompilasi dokumen.

Selain file `main.tex`, ada juga beberapa bagian lain dari template ini yang bisa diubah, seperti:

- **[`abstrak`](./abstrak)**, berisi file `*.tex` untuk abstrak dalam Bahasa Indonesia dan Bahasa Inggris.
- **[`bab`](./bab)**, berisi file `*.tex` dari setiap bab yang akan dimasukkan pada buku tugas akhir.
- **[`gambar`](./gambar)**, berisi file `*.jpg`, `*.png`, maupun format gambar lain yang akan dimasukkan pada buku tugas akhir.
- **[`lainnya`](./lainnya)**, berisi file `*.tex` dari halaman lain seperti lembar pengesahan, kata pengantar, biografi penulis, dsb. yang akan dimasukkan pada buku tugas akhir.
- **[`program`](./program)**, berisi file kode program yang akan dimasukkan pada dokumen.
- **[`pustaka/pustaka.bib`](./pustaka/pustaka.bib)**, berisi daftar pustaka yang akan dimasukkan pada dokumen.
- **[`pustaka/variables.tex`](./pustaka/variables.tex)**, berisi variabel-variabel yang memuat nama, nrp, dan hal-hal lain yang dapat disesuaikan dengan kebutuhan penulis.
- **[`sampul`](./sampul)**, berisi file `*.tex` dari sampul luar dan dalam untuk buku tugas akhir.

> Penjelasan lebih lanjut mengenai penggunaan template ini akan dijelaskan dengan comment yang tersedia pada setiap file yang ada.

## Contoh Penggunaan Template

Berikut adalah daftar repositori lain yang menggunakan template yang berasal dari repositori ini:

- [threeal/buku-ta-simulasi-robot](https://github.com/threeal/buku-ta-simulasi-robot).
- [chillytaka/last_boss](https://github.com/chillytaka/last_boss).

## Lisensi

Kode sumber yang ada pada repositori ini dilisensikan di bawah [lisensi MIT](./LICENSE).
