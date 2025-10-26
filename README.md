# 🚀 Portfolio Website - Arif Yunanto

Portfolio website profesional untuk menampilkan keahlian sebagai Data Analyst & Excel Specialist. Website ini dibangun dengan HTML, CSS, dan JavaScript vanilla untuk performa optimal.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [How to Update Content](#how-to-update-content)
- [Customization](#customization)
- [Deployment](#deployment)
- [Browser Support](#browser-support)
- [Troubleshooting](#troubleshooting)

---

## 🎯 Overview

Portfolio website untuk Arif Yunanto yang berfokus pada:
- Data Analysis & Excel Advanced
- Financial Modeling & Visualization
- SPSS, Eviews, Smart PLS Expertise
- Power BI & Google Data Studio
- Training & Consultation

**Live Preview:** [Add your website URL here]

---

## ✨ Features

### 📱 Responsive Design
- ✅ Mobile-first approach
- ✅ Hamburger menu untuk mobile devices
- ✅ Tablet & Desktop optimized
- ✅ Touch-friendly navigation

### 🎨 Modern UI/UX
- ✅ Dark theme dengan gradient accents
- ✅ Smooth animations & transitions
- ✅ Font Awesome icons integration
- ✅ Professional color scheme (dark blue #0b1b2e)

### 📧 Contact Integration
- ✅ Click-to-call functionality
- ✅ Email link integration
- ✅ LinkedIn profile link
- ✅ Social media icons

### 🖼️ Image Management
- ✅ Optimized image loading
- ✅ Placeholder system untuk mudah update foto
- ✅ Lazy loading ready

---

## 🛠️ Technology Stack

```
Frontend:
├── HTML5 (Semantic markup)
├── CSS3 (Custom properties, Flexbox, Grid)
├── JavaScript (Vanilla ES6+)
└── Font Awesome 6.5.1 (Icons)

External Services:
├── Google Fonts (Inter font family)
└── CDN for Font Awesome
```

---

## 📦 Installation

### Prerequisites
- Text editor (VS Code recommended)
- Modern web browser
- Git (optional)

### Setup Steps

1. **Clone atau download repository**
   ```bash
   git clone [repository-url]
   cd porto-arifyunanto
   ```

2. **Buka project di text editor**
   ```bash
   code .
   ```

3. **Update foto profil**
   - Letakkan foto Anda di folder `image/`
   - Rename menjadi `profile-photo.jpg`
   - Ukuran recommended: 600x800 px

4. **Jalankan website**
   - Buka file `index.html` di browser
   - Atau gunakan Live Server extension di VS Code

---

## 📁 Project Structure

```
porto-arifyunanto/
│
├── index.html                  # Main HTML file
├── style.css                   # All CSS styling
├── README.md                   # Documentation (this file)
│
├── image/                      # Images folder
│   ├── profile-photo.jpg       # Your profile photo (UPDATE THIS)
│   ├── project-1.jpg          # Project thumbnails (optional)
│   └── README.md              # Image folder documentation
│
├── .git/                       # Git repository
└── INSTALASI-ICON-DAN-IMAGE.md # Guide untuk icon & image
```

---

## 📝 How to Update Content

### 1. Update Profile Photo

**Langkah:**
1. Siapkan foto profesional Anda (format JPG/PNG)
2. Optimize foto di https://tinyjpg.com/
3. Rename menjadi `profile-photo.jpg`
4. Replace file di folder `image/`

**Spesifikasi Foto:**
- Format: JPG atau PNG
- Ukuran: 600x800 pixels (rasio 3:4)
- File size: Max 2MB
- Background: Netral/relevan

### 2. Update Personal Information

Edit file `index.html`:

**Hero Section (Line ~44-46):**
```html
<h1 class="hero-title">
    <span class="text-white">HAY! I'M ARIF</span><br>
    <span class="text-accent">DATA ANALYST & EXCEL SPECIALIST</span>
</h1>
```

**About Section (Line ~106-111):**
```html
<p class="about-description">
    Your custom description here...
</p>
```

**Contact Information (Line ~261-277):**
```html
<a href="mailto:your-email@example.com">Email</a>
<a href="tel:your-phone">Phone</a>
<a href="your-linkedin-url">LinkedIn</a>
```

### 3. Update Skills

Edit file `index.html` di Skills Section (Line ~136-159):

```html
<div class="skill-category">
    <h3 class="skill-category-title">Your Category</h3>
    <div class="skill-items">
        <span class="skill-item">Skill 1</span>
        <span class="skill-item">Skill 2</span>
    </div>
</div>
```

### 4. Update Projects

Edit file `index.html` di Projects Section (Line ~182-226):

```html
<div class="project-card">
    <div class="project-thumbnail">
        <div class="thumbnail-content">
            <div class="thumbnail-title">Project Title</div>
            <div class="thumbnail-subtitle">Category</div>
        </div>
    </div>
    <div class="project-info">
        <h3 class="project-title">Your Project Title</h3>
        <p class="project-role">Tools & Technologies used</p>
    </div>
</div>
```

### 5. Change Colors

Edit file `style.css`:

**Primary Color (Line ~37):**
```css
.text-accent { color: #0d6efd; } /* Change this hex code */
```

**Background Colors:**
- Main: `#0b1b2e`
- Secondary: `#11253d`
- Cards: `#152b46`

**Gradient (Line ~42):**
```css
background: linear-gradient(135deg, #0d6efd, #0056b3);
```

---

## 🎨 Customization

### Change Theme Color

1. Buka `style.css`
2. Search & replace color codes:
   - `#0d6efd` → Your primary color
   - `#0056b3` → Your secondary color
   - `#0b1b2e` → Your background color

### Change Fonts

Edit `index.html` (Line ~9):
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

Then edit `style.css`:
```css
body {
    font-family: 'YourFont', sans-serif;
}
```

### Add New Icons

Buka https://fontawesome.com/icons dan cari icon yang Anda inginkan.

**Contoh:**
```html
<i class="fas fa-chart-bar"></i>
```

Icon types:
- `fas` = Solid (penuh)
- `far` = Regular (outline)
- `fab` = Brands (sosial media)

### Modify Mobile Menu

**Width & Height:** Edit `style.css` Line ~768-769:
```css
width: 280px;  /* Menu width */
height: 100vh;  /* Menu height */
```

**Background:** Line ~763:
```css
background: rgba(11, 27, 46, 0.98);
```

---

## 🚀 Deployment

### Option 1: GitHub Pages (Recommended)

1. Push code ke GitHub repository
2. Go to Settings → Pages
3. Select branch `main` and folder `/root`
4. Save
5. Website akan live di: `https://yourusername.github.io/porto-arifyunanto`

### Option 2: Netlify

1. Go to https://netlify.com
2. Drag & drop folder project
3. Website langsung live!

### Option 3: Vercel

```bash
npm i -g vercel
vercel
```

### Option 4: Traditional Hosting

1. Upload files via FTP
2. Keep structure intact
3. Update image paths if needed

---

## 🌐 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Opera (Latest)
- ⚠️ IE 11 (Not supported)

---

## 🔧 Troubleshooting

### Issue: Foto tidak muncul
**Solution:**
- Pastikan nama file: `profile-photo.jpg` (case sensitive)
- Lokasi: `image/profile-photo.jpg`
- Format: JPG atau PNG
- Hard refresh browser (Ctrl+F5)

### Issue: Icon Font Awesome tidak load
**Solution:**
- Cek koneksi internet (CDN)
- Buka Console (F12) untuk error message
- Pastikan link CDN aktif di `index.html`

### Issue: Mobile menu tidak bekerja
**Solution:**
- Pastikan JavaScript enabled
- Cek Console untuk error
- Verifikasi mobile device (< 768px width)

### Issue: Contact links tidak berfungsi
**Solution:**
- Email: Format `mailto:email@example.com`
- Phone: Format `tel:+628123456789`
- LinkedIn: Format `https://linkedin.com/in/username`

### Issue: Styling tidak responsive
**Solution:**
- Hard refresh browser (Ctrl+F5)
- Clear cache
- Check media queries di `style.css`

---

## 📊 Performance Tips

1. **Optimize Images:**
   - Use TinyJPG: https://tinyjpg.com/
   - Target: < 500KB per image

2. **Minify CSS:**
   ```bash
   npm install -g clean-css-cli
   cleancss -o style.min.css style.css
   ```

3. **Minify HTML:**
   - Use online tool: https://www.websiteplanet.com/webtools/htmlcompressor/

4. **Enable Gzip Compression** (server-side)

---

## 📞 Support & Contact

**Arif Yunanto**
- 📧 Email: arifyunanto236@gmail.com
- 📱 Phone: 089687940623
- 💼 LinkedIn: https://www.linkedin.com/in/arifyunanto

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Credits

- **Fonts:** [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- **Icons:** [Font Awesome](https://fontawesome.com)
- **Design Inspiration:** Modern portfolio templates

---

## 🎉 Changelog

### Version 1.0.0 (Current)
- ✅ Initial release
- ✅ Responsive design
- ✅ Mobile hamburger menu
- ✅ Font Awesome integration
- ✅ Contact integration
- ✅ Skills & Projects sections
- ✅ Professional dark theme

---

**Made with ❤️ by Arif Yunanto**
