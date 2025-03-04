## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

|  | Pemrograman Berbasis Framework 2025 |
|--|--|
| NIM |  2241720181 |
| Nama |  Hanief Mochsin |
| Kelas | TI - 3C |

## Persiapan

* buat project NextJS dan jalankan aplikasinya

![image](https://github.com/user-attachments/assets/3df58771-9fdf-4141-9726-5b50f5bc3aa3)

![image](https://github.com/user-attachments/assets/7151f10b-95d8-4ce2-a1c3-3e253160b3b4)

## Membuat Halaman dengan Server-Side Rendering (SSR)

* ubah kode didalam file pages/index.tsx

![image](https://github.com/user-attachments/assets/34d2e741-5f1f-48cb-ae0e-27c9a44ade4c)

* Anda akan melihat halaman utama dengan teks 
"Selamat Datang di Website Saya!".

![image](https://github.com/user-attachments/assets/81a484ba-ef66-4dfe-87be-68289541ceed)

## Menggunakan Static Site Generation (SSG)

* buat file baru blog.js di dalam folder pages dan tambahkan kode didalamnya.

![image](https://github.com/user-attachments/assets/e51a7845-8a4c-4dcb-91b1-e1b56fcfff0c)

![image](https://github.com/user-attachments/assets/b1b4be51-be68-4919-af8e-8d594df4d109)

* Anda akan melihat daftar post yang 
diambil dari API eksternal.

![image](https://github.com/user-attachments/assets/ffd2cdbe-d404-475e-a349-c6d2bb741806)

## Menggunakan Dynamic Routes

* buat folder baru bernama blog dan tambahkan file [slug].js dan tambahkan kode di filenya.

![image](https://github.com/user-attachments/assets/036d7070-a907-4b4e-95aa-fa11d55bdb5a)

![image](https://github.com/user-attachments/assets/813ee470-23b5-4661-9054-32c8fd42b91b)

* Anda akan melihat 
halaman yang menampilkan slug dari URL. 

![image](https://github.com/user-attachments/assets/3274a478-4b3a-461b-b0c4-be85b18feda2)

## Menggunakan API Routes

* di folder API buat file baru bernama products.js dan tambahkan kode didalamnya.

![image](https://github.com/user-attachments/assets/b89c16b2-2c84-4276-92c3-cbbc28112d9f)

![image](https://github.com/user-attachments/assets/8dd4e8b6-d2a8-4022-9dc4-289866435636)

* buat file baru di folder pages dengan nama products.js untuk menampilkan daftar produk

![image](https://github.com/user-attachments/assets/f28dfa7a-cc67-4c88-849d-d3d0819b6ce2)

![image](https://github.com/user-attachments/assets/c2e819b0-cac8-4bbe-9bfd-cf1e0dc3727c)

*  Anda akan melihat daftar 
produk yang diambil dari API route.

![image](https://github.com/user-attachments/assets/773e2f61-7324-4360-8843-8693015118e3)

## Menggunakan Link Component

* di file index.tsx modif dengan menambahkan kode untuk membuat link ke halman lain.

![image](https://github.com/user-attachments/assets/4b5c8248-618e-4d34-9ba4-838ba2fc0c3c)

* tambahkan juga di dalam div homepage

![image](https://github.com/user-attachments/assets/3854ff8a-ba29-48f6-93fc-a87d0995b47c)

* buat file baru about.js di folder pages untuk membuat link dari "tentang kami" mengarah ke halaman about.js

![image](https://github.com/user-attachments/assets/5ac8e72b-b788-45bb-a3c7-c9f64d81fc33)

*  buka http://localhost:3000 di browser dan Klik link "Tentang Kami" untuk navigasi ke 
halaman about.js.

![image](https://github.com/user-attachments/assets/a4f97ca7-dab9-4ce0-ac9a-00f9152217ee)

![image](https://github.com/user-attachments/assets/16e748fc-252c-46bd-90ac-e6f4bd450c11)

## Tugas 

1. Buat halaman baru dengan menggunakan Static Site Generation (SSG) yang menampilkan daftar 
pengguna dari API https://jsonplaceholder.typicode.com/users. 
2. Implementasikan Dynamic Routes untuk menampilkan detail pengguna berdasarkan ID. 
3. Buat API route yang mengembalikan data cuaca dari API eksternal (misalnya, OpenWeatherMap) 
dan tampilkan data tersebut di halaman front-end.

* buat folder baru bernama users di dalam folder pages. dan tambahkan file bernama [id].js dan index.js

![image](https://github.com/user-attachments/assets/38567565-acac-4e06-a5f3-ce58fbf48c37)

* buat file baru bernama weather.js di dalam folder API.

![image](https://github.com/user-attachments/assets/2e97d561-ca68-47f2-aa02-e5224cda0bb3)

* buat file baru bernama weather.js di dalam folder pages.

![image](https://github.com/user-attachments/assets/2088d0d3-350e-422f-a39d-762a43088c58)

* didalam folder users tambahkan kode di file index.js

![image](https://github.com/user-attachments/assets/14a1c608-a898-4087-9d4d-1d03d8d3803d)

* tambahkan kode di [id].js

![image](https://github.com/user-attachments/assets/b5d9ff05-6f05-4f8b-a9de-af34078ebac5)

* tambahkan kode di weather.js didalam folder pages

![image](https://github.com/user-attachments/assets/2d2db23e-8c54-4fae-ba4b-f17048e16e53)

* tambahkan kode di weather.js didalam folder API

![image](https://github.com/user-attachments/assets/1ba1ef0a-6d36-4764-a6ee-d8748fb31008)

* buka http://localhost:3000/user di browser anda akan melihat daftar user

![image](https://github.com/user-attachments/assets/a394abcc-e65a-4474-a2ed-07f826e8e3fb)

* ketika mengklik salah satu user akan memperlihatkan detail data dari salah satu user

![image](https://github.com/user-attachments/assets/856e8f00-acd3-4875-93ef-6e2938a6231d)

*buka http://localhost:3000/weather di browser, anda akan melihat tampilan form untuk mengecek cuaca berdasarkan latitude dan longitude

![image](https://github.com/user-attachments/assets/4427b4dc-cbc6-4bea-9c62-bbeb3b1ce402)

* masukkan data latitude dan longitude sesuai daerah anda

![image](https://github.com/user-attachments/assets/96130bf6-90ab-4c0c-aeb9-a7a9da8f2439)

* lalu, anda akan melihat data cuaca terkini dari daerah yang telah anda input

![image](https://github.com/user-attachments/assets/6ca548df-1132-453c-9e04-344a02bf1a58)






