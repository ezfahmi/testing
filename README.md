# Front-end Dev Test

Dalam putaran proses interview ini Anda akan diminta untuk menginterpretasikan persyaratan produk dan membangun fitur sederhana. Anda akan menggunakan repo proyek ini untuk pengembangan Anda dan diminta untuk mendiskusikan pekerjaan Anda setelah selesai. Persyaratan akan dikirim pada hari jadwal test Anda. Sebelum test ini, harap membiasakan diri Anda dengan repositori ini dan pastikan Anda dapat mengikuti pengaturan dasar dan menjalankan instruksi.

Repositori ini berisi empat basis kode independen:

| Directory | Code Base |
|-----------|-----------|
| `angular` | Angular 11 |
| `react`    | ReactJS |
| `vue`      | VueJS |

**Gunakan bahasa yang paling nyaman bagi Anda.** Semua UI secara fungsional sama; mereka hanya berbeda dalam bahasa dan kerangka kerja yang digunakan.

## Sebelum testing:

* Klon repositori ini dan biasakan diri Anda dengan struktur proyek beserta kode dependensinya.
* Instal dependensi dan pastikan dapat melayani aplikasi secara lokal dan menjalankan testing ini.
* Kirim pertanyaan apa pun kepada rekruiter melalui email.

## Before your scheduled test:

* Clone this repository and familiarize yourself with the project structure, its dependencies and existing code.
* Install the dependencies and ensure you can serve the application locally and run the tests.
* Send any questions to the recruiter via email.

**Catatan:** Setiap bahasa koding individual. disertakan README masing-masing dengan dokumentasi khusus untuk bahasa dan kerangka kerja tersebut.

## Selama testing Anda:

* Persyaratan fitur akan dikirim pada awal tes terjadwal.
* Anda akan memiliki 1 jam untuk menyelesaikan sebanyak mungkin fitur.


## Mock backend

Repositori ini berisi _mock backend_ yang menyajikan data statis sederhana, yang memberikan target query API anda. Backend ini terletak di direktori `server/`.

Untuk menjalankan server, Anda harus terlebih dahulu menginstal utilitas berikut:

| Utility | Version | Link(s) |
|------------|---------|---------|
| Node | ~ 14.15 | [NodeJS](https://nodejs.org/en/) |
| NPM | ^ 6.14 | [NodeJS](https://nodejs.org/en/) (bundled with NodeJS) |

Kemudian navigasikan ke direktori `server` dan jalankan:

```commandline
npm install
```
Ini akan menginstal dependensi yang diperlukan. Untuk memulai _mock server_, jalankan perintah berikut dari dalam direktori `server`:

```commandline
npm run start
```

Anda harus membiarkan jendela terminal ini berjalan di background; server akan berhenti bila anda keluar dari terminal instance.
