# Student Management REST API

## Deskripsi

Student Management REST API adalah aplikasi web sederhana yang digunakan untuk mengelola data siswa.

Aplikasi ini menyediakan fitur untuk:

- Melihat data siswa
- Menambahkan data siswa
- Mengubah data siswa
- Menghapus data siswa
- Mencari data siswa
- Memfilter siswa berdasarkan kelas
- Menampilkan jumlah siswa
- Dark mode pada halaman utama

Frontend menggunakan HTML, CSS, dan JavaScript. 
JavaScript menggunakan metode `fetch()` untuk berkomunikasi dengan REST API yang dibuat menggunakan Express.js.

---

## Teknologi

Teknologi yang digunakan dalam project ini:

- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- MySQL
- REST API
- Git
- GitHub

---

## Struktur Data Siswa

Data siswa yang digunakan dalam aplikasi terdiri dari:

| Field | Keterangan |
|---|---|
| `id` | ID siswa |
| `nis` | Nomor Induk Siswa |
| `nama` | Nama siswa |
| `kelas` | Kelas siswa |
| `jurusan` | Jurusan siswa |
| `alamat` | Alamat siswa |

---

## Struktur Folder

Struktur project:

```text
student-management-rest-api/
│
├── routes/
│   └── siswa.js
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── server.js
├── package.json
├── package-lock.json
└── README.md