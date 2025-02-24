## Laporan Praktikum

|  | Pemrograman Berbasis Framework 2025 |
|--|--|
| NIM |  2241720217|
| Nama |  Muhammad Bagus Indrawan |
| Kelas | TI - 3A |


# Praktikum 1: Menyiapkan Lingkungan Pengembangan 
## Pertanyaan Praktikum 1 
1. Jelaskan kegunaan masing-masing dari Git, VS Code dan NodeJS yang telah Anda install 
pada sesi praktikum ini! 

- Git digunakan untuk melacak perubahan source code selama proses pengembangan.
- VS Code digunakan sebagai editor source code dalam proses pengembangan.
- Node JS digunakan untuk membangun aplikasi berbasis jaringan yang bersifat scalable.

2. Buktikan dengan screenshoot yang menunjukkan bahwa masing-masing tools tersebut 
telah berhasil terinstall di perangkat Anda!
![alt text](image.png)
![alt text](image-1.png)

# Praktikum 2: Membuat Proyek Pertama React Menggunakan Next.js
## Pertanyaan Praktikum 2 
1. Pada Langkah ke-2, setelah membuat proyek baru menggunakan Next.js, terdapat beberapa 
istilah yang muncul. Jelaskan istilah tersebut, TypeScript, ESLint, Tailwind CSS, App 
Router, Import alias, App router, dan Turbopack! 

    - TypeScript
    TypeScript : Merupakan bahasa pemrograman yang merupakan superset dari JavaScript, yang menambahkan sistem tipe statis. Dengan TypeScript, pengembang dapat mendeteksi kesalahan lebih awal karena kode yang lebih ketat dan dapat diprediksi. Next.js secara default mendukung TypeScript, sehingga pengembang bisa langsung menggunakannya dalam proyek.

    - ESLint
    ESLint : Merupakan alat statis untuk memeriksa kode JavaScript dan TypeScript agar sesuai dengan standar tertentu. ESLint membantu mengidentifikasi dan memperbaiki kesalahan atau inkonsistensi dalam kode, sehingga memudahkan pemeliharaan proyek.

    - Tailwind CSS : Sebuah framework CSS berbasis utility-first, yang memungkinkan pengembang untuk membuat antarmuka pengguna dengan cepat tanpa perlu menulis banyak kode CSS khusus. Dengan Tailwind, style dapat diterapkan langsung di dalam atribut className menggunakan kelas yang telah ditentukan.

    - App Router : Merupakan sistem routing baru di Next.js yang diperkenalkan sejak Next.js 13. App Router menggantikan sistem routing berbasis pages dengan pendekatan berbasis direktori app/. Dengan App Router, fitur seperti Server Components, Layouts, dan Streaming menjadi lebih mudah diimplementasikan, memberikan performa yang lebih baik dan pengelolaan kode yang lebih terstruktur.

    - Import Alias : Fitur yang memungkinkan pengembang untuk membuat jalur impor yang lebih singkat dan mudah dibaca, daripada menggunakan jalur relatif panjang seperti ../../../components/Button. Dengan menggunakan import alias (misalnya, @/components/Button), kode menjadi lebih bersih dan mudah dikelola.

    - Turbopack : Merupakan bundler baru yang dikembangkan oleh tim Next.js sebagai pengganti Webpack, dengan klaim kecepatan yang jauh lebih tinggi. Dibangun menggunakan Rust, Turbopack menawarkan proses build dan hot-reloading yang lebih cepat, terutama dalam pengembangan proyek besar.


2. Apa saja kegunaan folder dan file yang ada pada struktur proyek React yang tampil pada 
gambar pada tahap percobaan ke-3! 

- `.next/` : Folder ini dihasilkan secara otomatis setelah menjalankan build atau development server (npm run dev).
Berisi hasil build dari Next.js, termasuk cache untuk meningkatkan performa.
- `node_modules/` : Folder ini berisi semua dependensi atau package yang diinstal melalui npm install atau yarn install.
Jangan ubah isi folder ini secara manual.
- `public/` : Folder untuk menyimpan aset statis seperti gambar, ikon, atau file lainnya yang dapat diakses langsung melalui URL (misalnya, localhost:3000/favicon.ico).
File di dalamnya tidak melalui proses bundling Next.js.
- `src/app/` : Ini adalah folder utama untuk sistem App Router (diperkenalkan di Next.js 13).
Berisi file dan komponen utama untuk routing, layout, dan halaman aplikasi.
- `favicon.ico` : Ikon kecil yang ditampilkan di tab browser saat aplikasi berjalan.
- `globals.css` : File CSS global yang berlaku di seluruh aplikasi.
- `layout.tsx` : File ini digunakan untuk menentukan tata letak (layout) yang berlaku untuk semua halaman.
Biasanya digunakan untuk membungkus halaman dengan header, footer, atau tema tertentu.
- `page.tsx` : Merupakan entry point utama halaman (/) dalam sistem App Router Next.js.
Jika ada page.tsx di dalam app/, maka halaman utama aplikasi akan dirender berdasarkan kode dalam file ini.
- `.gitignore` : Berisi daftar file dan folder yang tidak perlu dikirim ke repository Git, seperti node_modules/, .next/, dan file cache lainnya.
- `eslint.config.mjs` : Konfigurasi ESLint untuk memastikan kode tetap rapi, sesuai standar, dan bebas dari bug potensial.
- `next-env.d.ts` : File deklarasi TypeScript yang membantu Next.js dalam mengenali tipe tertentu dalam proyek.
- `next.config.ts` : Konfigurasi khusus untuk Next.js, seperti pengaturan rewrites, redirects, dan optimasi performa.
- `package.json` : File utama untuk mengelola dependensi proyek, skrip, dan metadata aplikasi.
- `package-lock.json` : File yang mengunci versi package yang diinstal untuk memastikan semua tim menggunakan dependensi yang sama.
- `postcss.config.mjs` : Konfigurasi untuk PostCSS, sering digunakan bersama dengan Tailwind CSS untuk memproses gaya.
- `README.md` : File dokumentasi proyek yang berisi informasi tentang cara menggunakan, mengonfigurasi, atau menjalankan proyek.
- `tailwind.config.ts` : Konfigurasi untuk Tailwind CSS, digunakan untuk menyesuaikan tema, warna, dan fitur lainnya.
- `tsconfig.json` : Konfigurasi TypeScript dalam proyek, menentukan aturan kompilasi dan pengaturan yang berlaku.

3. Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah 
berhasil Anda lakukan! 
![alt text](image-6.png)
![alt text](image-3.png)
![alt text](image-2.png)
![alt text](image-5.png)

# Praktikum 3: Menambahkan Komponen React (Button)
## Pertanyaan Praktikum 3 
1. Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah 
berhasil Anda lakukan!
![alt text](image-4.png)

# Praktikum 4: Menulis Markup dengan JSX
## Pertanyaan Praktikum 4 
1. Untuk apakah kegunaan sintaks user.imageUrl? 
    
    Sintaks `user.imageUrl` digunakan untuk mengambil gambar dari tautan yang dideklarasikan pada properti imageUrl dari objek user. Pada source code praktikum, user.imageUrl dipanggil dalam komponen Profile sebagai sumber (src) untuk elemen image `<img>`, sehingga gambar dari tautan tersebut dapat ditampilkan pada halaman web.
2. Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah 
berhasil Anda lakukan!
![alt text](image-7.png)
