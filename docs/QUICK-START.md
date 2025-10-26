# ⚡ Quick Start Guide

Panduan cepat untuk menjalankan website portfolio Anda.

---

## 🚀 3 Langkah Setup

### 1️⃣ Download/Clone Project
```bash
cd porto-arifyunanto
```

### 2️⃣ Update Foto Anda
- Buka folder `image/`
- Replace file `profile-photo.jpg` dengan foto Anda
- Format: JPG, Ukuran: 600x800 px

### 3️⃣ Buka di Browser
```bash
# Double click file index.html
# Atau gunakan:
# - VS Code Live Server extension
# - Python: python -m http.server
# - Node: npx http-server
```

✅ **Selesai!** Website Anda sudah running.

---

## 📝 Update Konten Cepat

### Update Nama & Info
Edit `index.html` line 20, 41-46
```html
<span class="logo-text">ARIF YUNANTO</span>

<h1>HAY! I'M ARIF</h1>
```

### Update Email & Phone
Edit `index.html` line 263, 267
```html
<a href="mailto:arifyunanto236@gmail.com">Email</a>
<a href="tel:089687940623">Phone</a>
```

### Update Projects
Edit `index.html` line 184-226

### Update Skills
Edit `index.html` line 136-159

---

## 🎨 Customize Warna

Edit `style.css` line 37
```css
.text-accent { color: #0d6efd; } /* Ganti kode warna */
```

Warna yang bisa diubah:
- Primary: `#0d6efd`
- Background: `#0b1b2e`
- Secondary: `#11253d`

---

## 📱 Test Mobile View

**Chrome DevTools:**
1. Press F12
2. Press Ctrl+Shift+M
3. Select device dari dropdown

---

## 🔧 Troubleshooting

**Foto tidak muncul?**
→ Pastikan nama file: `profile-photo.jpg` (HARUS SAMA PERSIS)

**Icon tidak muncul?**
→ Cek koneksi internet (Font Awesome via CDN)

**Menu mobile tidak bekerja?**
→ Pastikan JavaScript enabled di browser

---

## 📚 Dokumentasi Lengkap

- **[README.md](README.md)** - Installation & Setup
- **[DOCUMENTATION.md](DOCUMENTATION.md)** - Technical Details  
- **[INSTALASI-ICON-DAN-IMAGE.md](INSTALASI-ICON-DAN-IMAGE.md)** - Icon & Image Guide

---

## 💡 Tips

1. **Optimize foto** di https://tinyjpg.com/ sebelum upload
2. **Backup project** sebelum melakukan perubahan besar
3. **Test di berbagai device** untuk memastikan responsive
4. **Use Git** untuk version control

---

## 🚀 Deploy Ke Internet

**GitHub Pages (GRATIS):**
```bash
git add .
git commit -m "Initial commit"
git push origin main
# Settings → Pages → Deploy
```

**Netlify (GRATIS):**
1. Go to https://netlify.com
2. Drag & drop folder
3. Done!

---

**Selamat bekerja! 🎉**
