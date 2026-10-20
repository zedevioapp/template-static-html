# Template situs statis Zedevio

Situs HTML, CSS, dan JavaScript tanpa proses build. Zedevio menyajikan file di repo ini apa adanya.

## Memakai template

1. Klik **Use this template** lalu **Create a new repository** di GitHub.
2. Di Client Area Zedevio, buka **Auto Deploy > Project baru**, lalu impor repo baru tersebut. Bila repo belum muncul, izinkan Zedevio mengaksesnya lewat **Atur repo yang diizinkan**.
3. Zedevio mendeteksi situs statis dari `index.html` di root repo dan langsung men-deploy-nya.

Setiap push ke cabang produksi di-deploy ulang otomatis.

## Struktur

- `index.html`: halaman utama.
- `style.css`: tampilan.
- `assets/`: tempat gambar dan file lain.

Bila nanti butuh proses build (misalnya React atau Vite), tambahkan `package.json`; Zedevio akan membangunnya dengan Nixpacks.
