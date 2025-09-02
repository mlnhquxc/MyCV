# MyCV - Personal Resume Website

This is my personal CV website built with HTML, CSS, and JavaScript. The website features a modern, responsive design with interactive sections and automatic deployment to GitHub Pages.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional interface
- **Interactive Sections**: Smooth scrolling and hover effects
- **Social Media Integration**: Links to LinkedIn, GitHub, and Portfolio
- **Resume Modal**: Embedded Canva resume viewer
- **Auto Deployment**: Automatic deployment to GitHub Pages via GitHub Actions

## 🚀 Live Demo

Visit the live website: [https://mlnhquxc.github.io/MyCV/](https://mlnhquxc.github.io/MyCV/)

## 🛠️ Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/mlnhquxc/MyCV.git
cd MyCV
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm start
# or
npm run dev
```

4. Open your browser and visit `http://localhost:3000`

### Building for Production

```bash
npm run build
```

## 📦 Deployment

This project uses GitHub Actions for automatic deployment to GitHub Pages. Every push to the `quoc` or `main` branch will trigger a new deployment.

### Manual Deployment Setup

1. Go to your repository settings
2. Navigate to **Pages** section
3. Under **Source**, select **GitHub Actions**
4. The workflow will automatically deploy your site

## 🏗️ Project Structure

```
MyCV/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions workflow
├── assets/
│   └── img/                    # Images and icons
├── css/
│   └── styles.css             # Main stylesheet
├── js/
│   └── scripts.js             # JavaScript functionality
├── index.html                 # Main HTML file
├── info.json                  # Personal information data
├── package.json               # Node.js dependencies
└── README.md                  # Project documentation
```

## 🔧 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Bootstrap 5, Custom CSS
- **Icons**: Font Awesome
- **Build Tools**: Node.js, NPM
- **Deployment**: GitHub Actions, GitHub Pages
- **Development**: Live Server

## 📝 Customization

1. **Personal Information**: Edit `info.json` to update your details
2. **Resume**: Update the Canva embed URL in `index.html` (line 718)
3. **Projects**: Modify the projects section in `index.html`
4. **Styling**: Customize `css/styles.css` for visual changes
5. **Images**: Replace images in `assets/img/` folder

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Nguyễn Ngọc Minh Quốc (mlnhquxc)**

- GitHub: [@mlnhquxc](https://github.com/mlnhquxc)
- LinkedIn: [mlnhquxc](https://www.linkedin.com/in/mlnhquxc/)
- Email: mlnhquxc.work@gmail.com

---

⭐ If you found this project helpful, please give it a star on GitHub!