# Life Practical Tools Website 🛠️

A modern website that combines multiple practical online tools to help users improve efficiency in daily work and life. Focus on providing a clean, ad-free user experience.

[中文版](README.md) | English

## ✨ Features

### 🎯 Main Tools
- **Code Generator** - Support QR codes, barcodes for text, URL, WiFi, email, phone and more
- **Color Tools** - Color picker, format conversion, palette management
- **Text Processing** - Word count, case conversion, encoding/decoding, etc.
- **Time Tools** - Timestamp conversion, countdown timer, world clock
- **Password Generator** - Customizable secure password generation
- **Unit Converter** - Length, weight, temperature, area, volume, time conversion
- **Base64 Tools** - Base64 encoding/decoding for text, files, images
- **PDF Toolbox** - PDF merge, split, compress and conversion features
- **Image Editor** - Online image editing with filters, text, shapes and more

### 🎨 Design Features
- Modern responsive design
- Mobile-friendly
- Intuitive user interface
- Fast loading
- Local processing for privacy protection

### 💰 Highlights
- Completely free to use
- No ads interference
- Search engine optimized (SEO)
- High-quality content and user experience

## 🚀 Quick Start

### Environment Requirements
- Node.js 16.x or higher
- npm or yarn package manager

### Install Dependencies
```bash
npm install
```

### Run in Development Mode
```bash
npm run dev
```
Visit [http://localhost:3000](http://localhost:3000) to view the website

### Build Production Version
```bash
npm run build
```

### Preview Production Version
```bash
npm run preview
```

## 📁 Project Structure

```
├── public/                 # Static assets
├── src/
│   ├── components/         # Common components
│   │   ├── Header.jsx      # Header navigation
│   │   └── Footer.jsx      # Footer information
│   ├── pages/              # Page components
│   │   ├── Home.jsx        # Homepage
│   │   ├── QRGenerator.jsx # QR code generator
│   │   ├── ColorTools.jsx  # Color tools
│   │   ├── TextTools.jsx   # Text tools
│   │   ├── TimeTools.jsx   # Time tools
│   │   ├── PasswordGenerator.jsx # Password generator
│   │   ├── UnitConverter.jsx     # Unit converter
│   │   ├── Base64Tools.jsx       # Base64 tools
│   │   ├── PDFTools.jsx          # PDF toolbox
│   │   └── PhotoEditor.jsx       # Image editor
│   ├── i18n/               # Internationalization
│   │   ├── index.js        # i18n configuration
│   │   └── locales/        # Language files
│   │       ├── zh-CN.json  # Chinese
│   │       └── en-US.json  # English
│   ├── App.jsx             # Main app component
│   ├── main.jsx            # App entry point
│   └── index.css           # Global styles
├── index.html              # HTML template
├── package.json            # Project configuration
├── vite.config.js          # Vite configuration
├── tailwind.config.js      # Tailwind configuration
└── README.md               # Project documentation
```

## 🛠️ Tech Stack

- **Frontend Framework**: React 18
- **Build Tool**: Vite
- **CSS Framework**: Tailwind CSS
- **Router**: React Router DOM
- **Icon Library**: Lucide React
- **QR Code**: qrcode.js
- **Color Picker**: react-color
- **PDF Processing**: pdf-lib
- **Image Editing**: Fabric.js
- **File Download**: file-saver
- **Internationalization**: react-i18next

## 🌍 Language Support

The website supports Chinese and English, with automatic language detection and manual switching:
- **Chinese (zh-CN)** - Default language
- **English (en-US)** - English interface
- Language preferences are saved locally
- Real-time switching without page refresh

## 📈 SEO Optimization

### Implemented SEO Features
- Semantic HTML structure
- Optimized meta tags
- Open Graph tags
- Twitter Cards
- Structured data (JSON-LD)
- Responsive design
- Fast loading times
- User-friendly URL structure

### Keyword Strategy
- Online tools
- Practical tools
- Free tools
- QR code generator
- Color tools
- Text processing
- Password generator
- PDF tools
- Image editor
- Online Photoshop
- PDF merge
- PDF split

## 💻 Deployment Recommendations

### Vercel Deployment
1. Push code to GitHub
2. Connect Vercel account
3. Import project
4. Automatic deployment

### Netlify Deployment
1. Run `npm run build`
2. Upload `dist` directory to Netlify
3. Configure custom domain

### Other Platforms
- GitHub Pages
- Firebase Hosting
- AWS S3 + CloudFront

## 🎯 Future Plans

### Feature Extensions
- [x] PDF toolbox - Completed
- [x] Image editor - Completed
- [x] Internationalization - Completed
- [ ] JSON formatting tool
- [ ] Markdown editor
- [ ] Regular expression tester
- [ ] Hash calculator
- [ ] Network ping test
- [ ] OCR text recognition
- [ ] Video format conversion

### Optimization Plans
- [ ] PWA support
- [ ] Dark theme
- [ ] User preference settings
- [ ] Tool usage statistics

## 📱 Responsive Design

The website now has 14+ practical tools and fully supports:
- Desktop (1200px+)
- Tablet (768px-1199px)
- Mobile (320px-767px)

## 🔒 Privacy Protection

- All tool processing is done locally
- No collection of personal user information
- No storage of user input data
- GDPR compliant

## 🤝 Contributing

1. Fork the project
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create Pull Request

## 📄 Open Source License

This project is licensed under the [MIT License](LICENSE).


⭐ If this project helps you, please give us a Star!

