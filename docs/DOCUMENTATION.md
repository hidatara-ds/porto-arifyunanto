# 📚 Panduan Detail - Portfolio Website

Panduan lengkap untuk memahami dan mengelola website portfolio ini.

---

## 📁 Struktur File

```
porto-arifyunanto/
├── index.html           ← File utama (isi website)
├── style.css            ← Styling & tampilan
├── README.md            ← Panduan singkat
└── image/               ← Folder foto
    └── profile-photo.jpg  ← Foto profil
```

---

## 🔧 Cara Update Konten

### 1. Update Foto Profil

**Langkah:**
1. Siapkan foto profesional Anda
2. Rename menjadi: `profile-photo.jpg`
3. Copy ke folder `image/`
4. Selesai!

**Tips:**
- Ukuran: 600x800 pixels
- Format: JPG (paling baik)
- Compress di: https://tinyjpg.com/

### 2. Update Nama & Info

**Buka file:** `index.html`

**Line 20 - Logo Name:**
```html
<span class="logo-text">ARIF YUNANTO</span>  ← Ganti di sini
```

**Line 44-45 - Hero Title:**
```html
<span class="text-white">HAY! I'M ARIF</span>
<span class="text-accent">DATA ANALYST & EXCEL SPECIALIST</span>
```

**Line 263 - Email:**
```html
<a href="mailto:arifyunanto236@gmail.com">arifyunanto236@gmail.com</a>
```

**Line 267 - Phone:**
```html
<a href="tel:089687940623">089687940623</a>
```

### 3. Update Deskripsi

**Buka:** `index.html`

**Line 47-48 - Hero Description:**
```html
<p class="hero-description">
    Deskripsi Anda di sini...
</p>
```

**Line 101-102 - About Description:**
```html
<p class="about-description">
    Deskripsi lengkap Anda di sini...
</p>
```

### 4. Update Skills

**Buka:** `index.html` bagian Skills (sekitar line 136)

**Struktur:**
```html
<div class="skill-category">
    <h3 class="skill-category-title">Nama Kategori</h3>
    <div class="skill-items">
        <span class="skill-item">Skill 1</span>
        <span class="skill-item">Skill 2</span>
    </div>
</div>
```

**Contoh:**
```html
<div class="skill-category">
    <h3 class="skill-category-title">Web Development</h3>
    <div class="skill-items">
        <span class="skill-item">HTML</span>
        <span class="skill-item">CSS</span>
        <span class="skill-item">JavaScript</span>
    </div>
</div>
```

### 5. Update Projects

**Buka:** `index.html` bagian Projects (sekitar line 184)

**Struktur:**
```html
<div class="project-card">
    <div class="project-thumbnail">
        <div class="thumbnail-content">
            <div class="thumbnail-title">Project Title</div>
            <div class="thumbnail-subtitle">Category</div>
        </div>
    </div>
    <div class="project-info">
        <h3 class="project-title">Judul Project</h3>
        <p class="project-role">Tools & Technology</p>
    </div>
</div>
```

**Contoh:**
```html
<div class="project-card">
    <div class="project-thumbnail">
        <div class="thumbnail-content">
            <div class="thumbnail-title">E-commerce Website</div>
            <div class="thumbnail-subtitle">Web Development</div>
        </div>
    </div>
    <div class="project-info">
        <h3 class="project-title">Online Store dengan React</h3>
        <p class="project-role">React, Node.js, MongoDB</p>
    </div>
</div>
```

---

## 🎨 Ubah Warna

**Buka file:** `style.css`

**Line 37 - Warna Utama (Biru):**
```css
.text-accent { color: #0d6efd; }  /* Ganti kode #0d6efd */
```

**Contoh warna:**
- Merah: `#ef4444`
- Hijau: `#10b981`
- Ungu: `#8b5cf6`
- Orange: `#f59e0b`

**Line 42 - Warna Tombol:**
```css
background: linear-gradient(135deg, #0d6efd, #0056b3);
                                        ↑         ↑
                              Warna 1      Warna 2
```

---

## 🖼️ Ganti Icon

**Website menggunakan Font Awesome icons**

**Cara cari icon:**
1. Buka: https://fontawesome.com/icons
2. Cari icon yang Anda inginkan
3. Klik icon tersebut
4. Copy kode class

**Contoh:**
```html
<!-- Icon email -->
<i class="far fa-envelope"></i>

<!-- Icon phone -->
<i class="fas fa-phone"></i>

<!-- Icon chart -->
<i class="fas fa-chart-bar"></i>
```

**Jenis icon:**
- `fas` = Penuh (solid)
- `far` = Outline (regular)
- `fab` = Brand/sosial media

---

## 📱 Test Mobile View

**Chrome:**
1. Tekan `F12`
2. Tekan `Ctrl+Shift+M` (Windows) atau `Cmd+Shift+M` (Mac)
3. Pilih device dari dropdown

**Firefox:**
1. Tekan `F12`
2. Klik ikon responsive design
3. Pilih ukuran device

---

## 🐛 Troubleshooting

### Foto tidak muncul

**Masalah:** Foto tidak muncul di website

**Solusi:**
- Pastikan nama file: `profile-photo.jpg` (huruf kecil semua)
- Pastikan lokasi: folder `image/`
- Pastikan format: JPG atau PNG
- Refresh browser: `Ctrl + F5`

### Icon tidak muncul

**Masalah:** Icon blank atau tidak muncul

**Solusi:**
- Cek koneksi internet (icon dari internet)
- Buka Console (F12) untuk lihat error
- Pastikan link Font Awesome aktif di line 10 `index.html`

### Menu mobile tidak bekerja

**Masalah:** Hamburger menu tidak terbuka

**Solusi:**
- Pastikan JavaScript enabled di browser
- Buka Console (F12) untuk error
- Test di device kecil (< 768px width)

### Link tidak berfungsi

**Masalah:** Email/Phone/LinkedIn tidak diklik

**Solusi:**
- Email: `mailto:email@example.com`
- Phone: `tel:+6281234567890`
- LinkedIn: `https://linkedin.com/in/username`

---

## 📦 Upload ke Internet

### GitHub Pages (Gratis)

**Langkah:**
1. Buat akun GitHub
2. Buat repository baru
3. Upload semua file
4. Settings → Pages → Branch main → Save
5. Website live di: `username.github.io/repository-name`

### Netlify (Gratis)

**Langkah:**
1. Buka: https://netlify.com
2. Sign up/login
3. Drag & drop folder project
4. Website langsung online!

### Vercel (Gratis)

**Langkah:**
1. Install Node.js
2. Install Vercel CLI: `npm i -g vercel`
3. Buka folder project
4. Run: `vercel`
5. Follow instructions

---

## 💡 Tips

1. **Selalu backup** sebelum mengubah banyak hal
2. **Test dulu** di browser sebelum upload
3. **Optimize gambar** untuk loading cepat
4. **Update secara bertahap** jangan sekaligus semua

---

## 📖 Pengetahuan Dasar

### HTML
- File ini berisi struktur website
- Edit untuk mengubah teks dan konten

### CSS  
- File ini berisi styling dan tampilan
- Edit untuk mengubah warna dan layout

### JavaScript
- File ini berisi interaksi
- Hamburger menu menggunakan ini

### Image
- Folder ini berisi foto
- Upload foto profil di sini

---

## 🔗 Referensi Bermanfaat

- **HTML Reference:** https://www.w3schools.com/html/
- **CSS Reference:** https://www.w3schools.com/css/
- **Font Awesome Icons:** https://fontawesome.com/icons
- **Color Picker:** https://htmlcolorcodes.com/
- **Image Optimizer:** https://tinyjpg.com/

---

## 📞 Butuh Bantuan?

**Arif Yunanto**
- Email: arifyunanto236@gmail.com
- Phone: 089687940623
- LinkedIn: linkedin.com/in/arifyunanto

---

**Tips:** Mulai dari yang sederhana dulu, baru lanjut ke hal yang lebih kompleks. Semua masalah ada solusinya! 🚀