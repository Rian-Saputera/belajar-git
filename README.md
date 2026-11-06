# Belajar Git

![Banner Proyek Belajar Git](https://picsum.photos/800/300)

Repositori ini berisi dokumentasi dan praktik dasar penggunaan **Git** dan **GitHub**, mencakup manajemen cabang (*branching*), penggabungan (*merging*), resolusi *merge conflict*, serta standarisasi penulisan berkas *Markdown*.

## Daftar Fitur

Berikut adalah materi dan fitur yang telah diimplementasikan:

- [x] Inisialisasi repositori lokal dan remote GitHub
- [x] Alur kerja fitur cabang (`feature/halaman-utama` dan `feature/halaman-tentang`)
- [x] Pembuatan Pull Request dan penggabungan commit
- [x] Simulasi dan resolusi bentrok kode (*merge conflict*)
- [x] Penerapan *branch protection rules* pada branch `main`
- [ ] Penerapan workflow CI/CD GitHub Actions

## Spesifikasi Sistem

| Komponen | Spesifikasi Minimum | Keterangan |
| :--- | :--- | :--- |
| Git | Versi 2.40+ | Version control system |
| Terminal | Git Bash / CLI | Lingkungan eksekusi |
| Teks Editor | VS Code | Penyunting kode sumber |

## Cara Menjalankan

Jalankan perintah berikut di Git Bash untuk menguji repositori ini:

```bash
git clone [https://github.com/Rian-Saputera/belajar-git.git](https://github.com/Rian-Saputera/belajar-git.git)
cd belajar-git
git log --oneline --graph --all
Dokumentasi diperbarui untuk verifikasi commit alur remote.
