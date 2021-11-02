# React Dev Test
Sikan lihat ke [main repository README](../README.md) sebagai acuan.

Direktori ini berisi Dev Test using React.

## Sebelum testing:

* Klon repositori ini dan biasakan diri Anda dengan struktur proyek beserta kode dependensinya.
* Instal dependensi dan pastikan Anda dapat melayani aplikasi secara lokal dan menjalankan tes.
* Kirim pertanyaan apa pun kepada perekrut melalui email.

## Selama testing:

* Anda akan memiliki 1 jam untuk menyelesaikan sebanyak mungkin fitur dengan kualitas.

Jangan ragu untuk mengubah salah satu kode yang ada sebagai bagian dari pengujian Anda.

## Setup

Ini adalah proyek React 17 menggunakan NextJS. Anda harus menginstal dependensi berikut:

| Dependency | Version | Link(s) |
|------------|---------|---------|
| Node | ~ 14.15 | [NodeJS](https://nodejs.org/en/) |
| NPM | ^ 6.14 | [NodeJS](https://nodejs.org/en/) (bundled with NodeJS) |

Setelah Anda menginstal ini, navigasikan ke direktori `react` di jendela terminal dan jalankan:

```commandline
npm install
```

Ini akan mengunduh semua dependensi dan menyimpannya ke direktori lokal `node_modules`.

Karena proses pembuatan dijalankan sepenuhnya dari terminal, tidak ada batasan untuk IDE atau editor apa yang anda gunakan. Jangan ragu untuk menggunakan editor apa pun yang paling nyaman bagi Anda, tetapi pastikan untuk menambahkan file konfigurasi khusus IDE ke file `.gitignore` proyek.

## Mock Backend

REST API disediakan untuk menyajikan beberapa data uji dummy yang digunakan dalam mengembangkan interaksi klien-server. Server ini dapat ditemukan di direktori `../server` (satu tingkat di atas yang ini.) Petunjuk tentang cara menjalankan server tiruan ini disertakan di [main repository README](../README.md).

## Development server

Untuk melayani aplikasi dalam mode dev, jalankan `npm run dev` setelah menyelesaikan pengaturan Anda. Jika berhasil, Anda akan melihat pesan yang menunjukkan bahwa aplikasi tersedia di `http://localhost:4400/`. Aplikasi akan secara otomatis _rebuild_ dan _reload_ ketika mendeteksi perubahan sistem file apa pun.

Perhatikan bahwa perintah ini **tidak** akan menjalankan mock server. Anda harus menjalankan mock server di jendela terminal terpisah agar panggilan API berhasil.

## Tests

Proyek ini dikonfigurasi dengan Jest dan React Testing Library untuk _writing test_. Tes terletak di direktori `__tests__`. Anda dapat menjalankannya dengan perintah berikut:

```
npm test
```

## Dokumentasi

* [NextJS documentation](https://nextjs.org/docs)
* [Jest documentation](https://jestjs.io/)
* [React Testing Library documentation](https://testing-library.com/docs/react-testing-library/intro/)
