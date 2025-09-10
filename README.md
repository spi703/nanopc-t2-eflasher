# NanoPC-T2 EFlasher

Repo ini berisi contoh **EFlasher** untuk NanoPC-T2.

## Build Otomatis
Setiap push ke branch `main`, GitHub Actions akan:
- Membuat `rootfs.tar.gz` dari folder `rootfs/`
- Membuat dummy image `eflasher-nanopc-t2.img`
- Upload hasilnya ke **GitHub Releases**

## Cara Pakai
1. Clone repo ini
2. Tambahkan rootfs atau OS kamu ke folder `rootfs/`
3. Push ke GitHub
4. Lihat hasil build di tab **Actions** dan **Releases**
