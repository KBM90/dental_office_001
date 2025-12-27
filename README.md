# Dental Office Website 🦷

A stunning, multilingual dental office website with modern design, WhatsApp appointment booking, and interactive features.

## 🌟 Features

### 🌍 Multilingual Support
- **5 Languages**: French, Arabic, English, Spanish, German
- **RTL Support**: Full right-to-left layout for Arabic
- **Language Persistence**: User's language preference saved locally

### 📱 WhatsApp Integration
- Direct appointment booking via WhatsApp
- Formatted messages with patient details
- Sends to: `0628144394`

### 🎨 Premium Design
- Modern, professional aesthetics
- Gradient backgrounds and glassmorphism effects
- Smooth animations and micro-interactions
- Fully responsive (mobile, tablet, desktop)

### 📋 Sections
1. **Hero Section**: Eye-catching introduction with CTAs
2. **Services**: 6 comprehensive dental services
3. **Video**: Cabinet tour showcase
4. **Appointment Form**: WhatsApp booking integration
5. **Map**: Interactive location with Leaflet.js
6. **Footer**: Contact information and quick links

## 🚀 Live Demo

Open `index.html` in your browser to view the website.

## 📂 Project Structure

```
dental_office_001/
├── index.html          # Main HTML structure
├── style.css           # Premium design system
├── script.js           # Interactive functionality
├── assets/
│   └── videos/
│       └── video.mp4   # Cabinet tour video
└── README.md
```

## 🛠️ Technologies

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties
- **JavaScript**: ES6+ features
- **Leaflet.js**: Interactive maps (v1.9.4)
- **Google Fonts**: Inter & Playfair Display

## 🌐 Supported Languages

| Language | Code | RTL Support |
|----------|------|-------------|
| French   | `fr` | ❌          |
| Arabic   | `ar` | ✅          |
| English  | `en` | ❌          |
| Spanish  | `es` | ❌          |
| German   | `de` | ❌          |

## 📋 Services Offered

1. **General Dentistry** - Exams, cleanings, fillings
2. **Cosmetic Dentistry** - Veneers, crowns, bridges
3. **Orthodontics** - Braces and invisible aligners
4. **Teeth Whitening** - Professional treatments
5. **Dental Implants** - Permanent tooth replacement
6. **Emergency Care** - Urgent dental needs

## 📞 Contact Information

- **Phone**: +212 628 144 394
- **Address**: 123 Rue de la Santé, Ville
- **Hours**: Mon-Fri: 9am-6pm

## 🔧 Customization

### Update WhatsApp Number
Edit `script.js` line 470:
```javascript
const whatsappNumber = '212628144394'; // Your number
```

### Update Office Location
Edit `script.js` lines 571-572:
```javascript
const lat = 33.5731;  // Your latitude
const lng = -7.5898;  // Your longitude
```

### Change Default Language
Edit `script.js` line 354:
```javascript
let currentLanguage = localStorage.getItem('dentalLanguage') || 'fr';
```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is created for dental office use.

## 👨‍💻 Development

No build process required! Simply edit the files and refresh your browser.

### File Purposes

- `index.html` - Structure and content
- `style.css` - All styling and animations
- `script.js` - Translations, form handling, map, interactions

## 🎨 Design Features

- **Color Palette**: Dental blues and teals
- **Typography**: Professional and readable
- **Animations**: Smooth scroll reveals
- **Cards**: Hover effects with gradients
- **Forms**: Clean validation and feedback

## 📸 Screenshots

The website features:
- Gradient hero section with animated background
- Service cards with hover effects
- Responsive video player
- Interactive appointment form
- Leaflet map integration
- Mobile-friendly navigation

---

**Built with ❤️ for dental professionals**
