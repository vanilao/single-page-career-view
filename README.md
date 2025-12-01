# Somchai Piunti - Single Page CV

A clean, single-page CV/resume website built with HTML and CSS, optimized for social media sharing with Open Graph tags.

## 🚀 Live Demo

**Project URL**: https://vanilao.github.io/single-page-career-view/

## 📋 Features

- **Responsive Design**: Works on all devices
- **Social Media Optimized**: Open Graph tags for better sharing
- **Favicon Support**: Custom icons for browsers and bookmarks
- **Semantic HTML**: Accessible and SEO-friendly
- **Minimal Styling**: Clean, professional appearance

## 🛠️ Tech Stack

- HTML5
- CSS3 (no frameworks)
- Vanilla JavaScript (not required for this static site)

## 📁 Project Structure

```
single-page-career-view/
├── index.html              # Main CV page
├── assets/                 # Icon files
│   ├── favicon.ico         # Main favicon
│   ├── apple-touch-icon.png # iOS icon
│   ├── android-chrome-192x192.png
│   └── android-chrome-512x512.png
└── README.md               # This file
```

## 🌐 How to Run

### Option 1: Local Development

1. Clone or download the repository
2. Open `index.html` in your web browser
3. No build process required - it's a static site!

### Option 2: Live Server (VS Code)

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Python Simple Server

```bash
# If you have Python installed
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📱 Social Media Sharing

The page includes Open Graph tags that will display rich previews when shared on:

- Facebook
- LinkedIn
- Twitter/X
- Other social platforms

## 🎨 Customization

### To Personalize This CV:

1. **Edit `index.html`**:

   - Update name, title, and contact information
   - Modify skills, education, and experience sections
   - Change social media links

2. **Update Open Graph Tags**:

   ```html
   <meta property="og:title" content="Your Name - Your Title" />
   <meta property="og:description" content="Your description" />
   <meta property="og:image" content="your-image-url" />
   <meta property="og:url" content="your-website-url" />
   ```

3. **Replace Favicon**:
   - Create a 16x16 or 32x32 pixel icon
   - Replace files in the `assets/` folder
   - Update the paths in `index.html` if needed

## 🚀 Deployment

This site can be deployed to any static hosting service:

- GitHub Pages (recommended)
- Netlify
- Vercel
- Any web server

### GitHub Pages Setup:

1. Push to GitHub repository
2. Go to Settings → Pages
3. Select source branch (usually `main` or `master`)
4. Enable GitHub Pages
5. Your site will be available at `https://username.github.io/repository-name/`

## 📄 License

This project is open source. Feel free to use it as a template for your own CV.

## 👤 Contact

- **Name**: Somchai Piunti
- **Location**: Bangkok, Thailand
- **Email**: somchai.piunti@gmail.com
- **LinkedIn**: [linkedin.com/in/somchai-piunti](https://www.linkedin.com/in/somchai-piunti)
- **GitHub**: [github.com/somchai-piunti](https://github.com/somchai-piunti)
