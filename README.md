# Submission 2: Proyek Deploy Aplikasi Karsa Jobs dengan Kubernetes

> ⭐⭐⭐⭐⭐

## Kriteria dan Saran

- [x] Kriteria 1: Menggunakan Starter Project (Karsa Jobs)
- [x] Kriteria 2: Membuat Script untuk Build dan Push Docker Image
- [x] Kriteria 3: Deploy Aplikasi ke Kubernetes
- [x] Saran 1: Memberikan **penjelasan dalam bentuk komentar** untuk setiap perintah atau properti yang ada pada berkas script dan manifest.
- [x] Saran 2: Alih-alih Docker Hub, Anda menggunakan **GitHub Packages** (GitHub Container Registry) untuk penyimpanan image.
- [x] Saran 3: Mengimplementasikan monitoring dengan deploy **Prometheus** dan **Grafana** di Kubernetes. Silakan deploy keduanya di dalam Namespace bernama monitoring untuk mempermudah.
- [x] Saran 4: Menerapkan Continuous Integration untuk branch **karsajobs** dan **karsajobs-ui**.

---

## Menambahkan Submodule Repository

Berikut cara menambahkan submodule repository [lyrihkaesa/a433-microservices](https://github.com/lyrihkaesa/a433-microservices) branch `karsajobs` dan `karsajobs-ui` pada repository ini:

```bash
git submodule add -b karsajobs https://github.com/lyrihkaesa/a433-microservices karsajobs
```

```bash
git submodule add -b karsajobs-ui https://github.com/lyrihkaesa/a433-microservices karsajobs-ui
```

---

## 🙏 Thanks To

- [Indosat Ooredoo Hutchison - IDCamp 2023](https://idcamp.ioh.co.id/)
- [Dicoding - Belajar Membangun Arsitektur Microservices](https://www.dicoding.com/academies/433)
- [Mentor - Gesang Wibawono](#)

> [Submission 1: Proyek Deploy Aplikasi Item App dengan Docker Compose](https://github.com/lyrihkaesa/a433-microservices/tree/proyek-pertama)  
> [Submission 3: Proyek Implementasi Asynchronous Communication pada Aplikasi E-Commerce App](https://github.com/lyrihkaesa/proyek-implementasi-asynchronous-communication-pada-aplikasi-e-commerce-app)
