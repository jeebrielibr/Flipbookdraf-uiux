# 🌿 Taman Kita Depok - UI/UX Portfolio Flipbook

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)](https://jquery.com/)

## 📖 Deskripsi Proyek

**Taman Kita Depok** adalah portfolio interaktif yang menampilkan case study lengkap proyek UI/UX untuk platform digital Ruang Terbuka Hijau (RTH) di Depok. Flipbook ini dirancang sebagai presentasi yang engaging dan profesional untuk showcase proses design thinking dari awal hingga akhir.

### 🎯 Tujuan Proyek
- Menghidupkan kembali ruang publik Depok melalui platform digital
- Mengatasi kesenjangan informasi RTH yang tersebar
- Memberdayakan komunitas untuk berpartisipasi dalam pengembangan RTH
- Menciptakan ekosistem digital yang menghubungkan warga dengan ruang publik

## ✨ Fitur Utama

### 🎨 **Interactive Flipbook Experience**
- **11 halaman** dengan navigasi yang smooth
- **Responsive design** untuk desktop, tablet, dan mobile
- **Multiple navigation methods**: button, keyboard arrows, touch gestures
- **Page transitions** dengan animasi yang elegan
- **Progress indicator** untuk tracking posisi

### 📱 **Cross-Platform Compatibility**
- **Desktop**: Optimal viewing dengan layout 900x600px
- **Tablet**: Responsive scaling untuk layar medium
- **Mobile**: Touch-optimized dengan gesture support
- **Keyboard navigation**: Arrow keys untuk accessibility

### 🎭 **Visual Design System**
- **Color Palette**: Green theme (#2E7D32, #4CAF50, #AED581)
- **Typography**: Lato (body) + Poppins (headings) + Dancing Script (accent)
- **Layout**: Flexbox dengan two-column layouts
- **Imagery**: Placeholder images dengan Picsum Photos integration

## 🛠️ Technology Stack

### **Frontend Technologies**
- **HTML5**: Semantic markup dan struktur konten
- **CSS3**: Modern styling dengan Flexbox dan responsive design
- **JavaScript**: Interaktivitas dan state management
- **jQuery 3.7.1**: DOM manipulation dan event handling

### **External Dependencies**
- **Google Fonts**: Lato, Poppins, Dancing Script
- **Picsum Photos**: Placeholder images untuk demo

## 📁 Struktur Proyek

```
Flipbook/
├── index.html          # Main flipbook file
├── images/             # Image assets directory
├── README.md           # Project documentation
└── desktop.ini         # Windows system file
```

## 🚀 Cara Menjalankan

### **Option 1: Local Development**
1. Clone repository ini:
```bash
git clone https://github.com/yourusername/taman-kita-flipbook.git
cd taman-kita-flipbook
```

2. Buka file `index.html` di browser:
```bash
# Menggunakan Python (jika tersedia)
python -m http.server 8000

# Atau langsung buka file di browser
open index.html
```

### **Option 2: Live Server (VS Code)**
1. Install extension "Live Server" di VS Code
2. Right-click pada `index.html`
3. Pilih "Open with Live Server"

### **Option 3: GitHub Pages**
1. Push ke repository GitHub
2. Aktifkan GitHub Pages di Settings
3. Akses via `https://username.github.io/repository-name`

## 🎮 Cara Penggunaan

### **Navigation Controls**
- **Button Navigation**: Klik "Sebelumnya" / "Berikutnya"
- **Keyboard**: Gunakan arrow keys (←/→)
- **Touch**: Swipe left/right pada mobile devices
- **Progress**: Lihat indicator halaman di bawah

### **Content Structure**
1. **Cover Page** - Showcase visual dengan branding
2. **The "Why"** - Understanding users (3 halaman)
3. **The Challenge** - Problem statement & HMW
4. **The "How"** - Solution design (2 halaman)
5. **The Proof** - Testing & iteration (2 halaman)
6. **The Future** - Impact & roadmap
7. **Penutup** - Learnings & contact

## 📱 Responsive Breakpoints

| Device | Width | Height | Features |
|--------|-------|--------|----------|
| Desktop | 900px | 600px | Full experience |
| Tablet | 700px | 500px | Scaled layout |
| Mobile | 500px | 350px | Touch optimized |
| Small Mobile | 350px | 250px | Compact view |

## 🎨 Customization Guide

### **Mengganti Konten**
1. **Text Content**: Edit teks di dalam `<div class="page">`
2. **Images**: Ganti URL placeholder dengan gambar Anda
3. **Branding**: Update nama dan contact info di halaman cover
4. **Colors**: Modifikasi CSS variables untuk tema custom

### **Menambah Halaman**
1. Copy template halaman existing
2. Update `data-page` attribute
3. Increment `totalPages` variable di JavaScript
4. Update navigation logic

### **Styling Modifications**
```css
/* Custom color scheme */
:root {
    --primary-color: #2E7D32;
    --secondary-color: #4CAF50;
    --accent-color: #AED581;
    --background-color: #f0f2f5;
}
```

## 🔧 Development Notes

### **Browser Compatibility**
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ⚠️ IE11 (limited support)

### **Performance Optimizations**
- Lazy loading untuk images
- CSS transitions untuk smooth animations
- Minimal JavaScript footprint
- Optimized font loading

### **Accessibility Features**
- Semantic HTML structure
- Keyboard navigation support
- ARIA labels (planned)
- Screen reader compatibility

## 📊 Case Study Highlights

### **Design Process**
- **Empathize**: User research dengan 2 personas utama
- **Define**: Problem statement dan HMW questions
- **Ideate**: Three-pillar solution approach
- **Prototype**: Wireframe to high-fidelity design
- **Test**: Usability testing dengan 7 participants

### **Key Results**
- **100% Task Success Rate** pada usability testing
- **46.4% Misclick Rate** yang diidentifikasi dan diperbaiki
- **Iterative Design** berdasarkan user feedback

## 🤝 Contributing

1. Fork repository ini
2. Buat feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📄 License

Proyek ini dilisensikan di bawah [MIT License](LICENSE) - lihat file LICENSE untuk detail.

## 📞 Contact & Links

- **Portfolio**: [Your Portfolio URL]
- **LinkedIn**: [Your LinkedIn Profile]
- **Email**: [your.email@example.com]
- **GitHub**: [@yourusername]

---

## 🙏 Acknowledgments

- **Google Fonts** untuk typography
- **Picsum Photos** untuk placeholder images
- **jQuery** untuk DOM manipulation
- **Design Thinking methodology** untuk framework proses

---

<div align="center">
  <p>Made with ❤️ for better public spaces</p>
  <p>🌿 <strong>Taman Kita Depok</strong> - Connecting Communities with Green Spaces</p>
</div> 
