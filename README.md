# 🏥 Jasur Med - Dorixona Tizimi

> **JasurMED Pharm** - sog'lig'ingiz uchun ishonchli dorixona. Dorilarni onlayn tanlang, retseptingizni yuklang va buyurtmani uyingizga oling.

[![GitHub stars](https://img.shields.io/github/stars/jasurmed/pharm?style=social)](https://github.com/jasurmed/pharm)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🚀 Xususiyatlar

- 🛒 **Onlayn dorilar katalogi** - 12+ turdagi dorilar
- 📋 **Retsept yuklash** - Rasmdan retsept yuklash imkoniyati
- 🗺️ **Xarita orqali manzil** - OpenStreetMap integratsiyasi
- 🌙 **Qorong'u rejim** - Avtomatik dark mode
- 🌐 **Ikki til** - Lotin va Krill alifbolari
- 📱 **Responsive** - Mobil va desktop moslashuvchan
- 🔔 **Bildirishnomalar** - Real-time buyurtma statuslari
- 💬 **Chat** - Buyurtma bo'yicha xabar almashish
- 👥 **Rollar tizimi** - Admin, Farmatsevt, Kuriyer, Mijoz

## 📁 Loyiha Tuzilmasi

```
jasurmed-pharm/
├── index.html          # Asosiy HTML fayl
├── css/
│   └── style.css       # Barcha stillar
├── js/
│   └── app.js          # Asosiy JavaScript logikasi
├── manifest.json       # PWA manifest
├── .gitignore          # Git ignore qoidalar
└── README.md           # Ushbu fayl
```

## 🛠️ Texnologiyalar

- **HTML5** - Semantik markup
- **Tailwind CSS** - Utility-first CSS framework (CDN)
- **Vanilla JavaScript** - ES6+ (localStorage API)
- **Leaflet.js** - Interaktiv xaritalar
- **Font Awesome** - Ikonkalar
- **Google Fonts** - Inter shrifti

## 🔐 Standart Loginlar

| Rol | Email | Parol |
|-----|-------|-------|
| **Admin** | `pharmd2214@gmail.com` | `Jetour832` |
| **Farmatsevt** | `farmatsevt@jasurmed.uz` | `Jetour832` |
| **Kuriyer** | `kuriyer@jasurmed.uz` | `Jetour832` |
| **Mijoz** | `mijoz@jasurmed.uz` | `Jetour832` |

## 🚀 Ishga Tushirish

1. Repozitoriyani klonlash:
```bash
git clone https://github.com/username/jasurmed-pharm.git
cd jasurmed-pharm
```

2. Lokal server orqali ochish:
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

3. Brauzerda ochish:
```
http://localhost:8000
```

## 📦 GitHub Pages'da Joylash

1. GitHub'da yangi repozitoriy yaratish
2. Fayllarni yuklash:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/jasurmed-pharm.git
git push -u origin main
```
3. **Settings > Pages** bo'limiga o'tish
4. **Source** qismidan `main` branchni tanlash
5. Sayt avtomatik tarzda `https://username.github.io/jasurmed-pharm` manzilida ishga tushadi

## 📝 Eslatmalar

- **Client-side** ilova - barcha ma'lumotlar `localStorage`da saqlanadi
- Brauzer keshini tozalash ma'lumotlarni o'chiradi
- Retsept rasmlari base64 formatida saqlanadi
- Xarita uchun internet ulanishi talab qilinadi

## 🐞 Ma'lum Xatolar

1. **Xarita ko'rinmayapti** - Internet ulanishini tekshiring
2. **Login ishlamayapti** - Brauzer localStorage'ini tekshiring
3. **Dark mode saqlanmayapti** - Cookie/blocker sozlamalarini tekshiring

## 📄 Litsenziya

MIT License - [LICENSE](LICENSE) faylini ko'ring.

## 👨‍💻 Muallif

**Jasur Med** - [pharmd2214@gmail.com](mailto:pharmd2214@gmail.com)

---

> ⚠️ **Diqqat**: Bu loyiha faqat ta'lim va namoyish maqsadlarida yaratilgan. Haqiqiy dorixona tizimi uchun backend va ma'lumotlar bazasi talab qilinadi.
