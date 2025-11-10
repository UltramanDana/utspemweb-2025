# 🧩 UTS PEMWEB  
### Oleh  
## 20230801539 – Happy Adrian Pradana Putra  

---

## 🧠 PROSES SLR  

### P.I.C.O.S.  
**Tema:** Konversi Template Statis ke Aplikasi Dinamis Laravel  

| Komponen | Penjabaran |
|-----------|-------------|
| **P (Platform)** | Konversi Template HTML5 & CSS3 (Anime - Bootstrap 4 Template) menjadi Aplikasi Web Dinamis berbasis Laravel. |
| **I (Intervention)** | Pemanfaatan Admin Panel Generator Laravel (seperti **Filament** atau **Nova**) dan **Laravel Blade Component** untuk mengintegrasikan 9+ file HTML statis (yang ada di template) menjadi struktur **Views** dan **Layouts** yang dinamis dan terkelola. |
| **C (Comparison)** | Penggunaan 9 file HTML terpisah dengan tautan statis (.html atau ./categories.html) yang membutuhkan modifikasi manual untuk setiap perubahan konten dan rentan terhadap **Error 404** saat navigasi. |
| **O (Outcome)** | Sistem Aplikasi Web Anime yang **fully dynamic** dengan navigasi yang mulus melalui **Laravel Routing**, di mana data konten, kategori, dan program gallery dikelola secara terpusat melalui database dan Admin Panel. |
| **S (Suspect)** | Mengurangi **maintenance effort**, memastikan **Single Source of Truth (SSOT)** untuk data konten, dan menyediakan **User Experience (UX)** yang profesional tanpa hambatan Error 404 pada navigasi. |

---

## 🔍 PROSES RQ  

### RQ Utama  
> Seberapa besar peningkatan efisiensi data management dan pengurangan maintenance effort yang dicapai melalui implementasi **Admin Panel Generator** berbasis **Laravel**, dibandingkan dengan metode template statis, pada **Aplikasi Web Katalog Anime**?

### RQ Turunan 1  
> Berapa perbandingan waktu yang dibutuhkan untuk manajemen (membuat, mengelola, memelihara) kategori konten dinamis menggunakan **Admin Panel Generator (I)** versus modifikasi **template statis (C)**?

### RQ Turunan 2  
> Seberapa efektif **Laravel Routing** dan **Blade Templating** dalam mengatasi isu navigasi statis (Error 404) dan meningkatkan **User Experience (UX)** pada Aplikasi Web Katalog Anime?

**Penjelasan:**  
RQ ini berfokus pada *outcome* penelitian. Setelah data diproses dan diklasifikasikan oleh model ML, peneliti dapat merancang dan menguji berbagai bentuk dashboard (misalnya: scorecard, grafik garis kelelahan, atau heatmap distribusi kerja) dan mengevaluasi kejelasan serta dampaknya terhadap kesadaran pengguna melalui *user study*.

---

## 🧩 Keyword Pencarian Jurnal  

Berikut daftar *keywords* yang bisa digunakan untuk pencarian jurnal di Google Scholar, IEEE Xplore, atau ResearchGate:  

- `Laravel dynamic web application`  
- `Admin panel generator Laravel Filament Nova`  
- `HTML template to Laravel conversion`  
- `Dynamic vs static website maintenance`  
- `Laravel Blade templating performance`  
- `Laravel routing user experience improvement`  
- `Single Source of Truth (SSOT) in web development`  
- `Database-driven web content management Laravel`  
- `Error 404 prevention through Laravel routing`  
- `Web application maintainability Laravel framework`  

---

## 📎 Lampiran File  

- **SLR.pdf** → berisi Systematic Literature Review berdasarkan P.I.C.O.S.  
- **BRD.pdf** → berisi Business Requirement Document hasil analisis dari SLR.  

---

## 💻 Implementasi Website  

Langkah-langkah implementasi proyek Laravel untuk konversi template statis menjadi aplikasi dinamis:  

```bash
1. cd /root/boilerplate
2. ./start.sh utspemweb
3. cd /root/perkuliahan/utspemweb
4. cd src
5. code .
6. Template website diambil dari:
   https://themewagon.com/themes/free-bootstrap-4-html5-gaming-anime-website-template-anime/
7. cd resources/views
8. mkdir layouts && mkdir pages && mkdir partials
9. cd ../../routes/
