# Sparient - Cloud, Data & AI Solutions Website

A modern, responsive website showcasing Sparient's comprehensive IT solutions including Cloud Services, Data Engineering, AI/ML, DevOps, and traditional IT services.

## 🚀 Features

- **Cloud Services**: AWS, Azure, GCP solutions
- **Data Engineering**: Data warehouse, lakehouse, and ETL solutions
- **AI/ML Services**: Machine learning, generative AI, and analytics
- **DevOps**: CI/CD, containerization, and infrastructure as code
- **ERP & Integration**: PeopleSoft, Salesforce, Boomi, and enterprise solutions
- **Enterprise Content Management**: Adobe AEM, OnBase, FileNet, and ECM solutions
- **Traditional IT**: SharePoint, enterprise apps, mobile development
- **Modern UI/UX**: Bootstrap 5.3.2, responsive design, smooth animations

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Framework**: Bootstrap 5.3.2
- **Icons**: Bootstrap Icons, Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Deployment**: GitHub Pages

## 📁 Project Structure

```
Website/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
├── .github/            # GitHub Actions workflows
│   └── workflows/
│       └── deploy.yml  # Auto-deployment to GitHub Pages
└── .gitignore          # Git ignore rules
```

## 🚀 GitHub Pages Deployment

### Automatic Deployment (Recommended)

This project is configured for automatic deployment to GitHub Pages using GitHub Actions. Simply push to the `main` or `master` branch and your site will be automatically deployed.

#### Setup Steps:

1. **Fork or Clone** this repository to your GitHub account
2. **Enable GitHub Pages**:
   - Go to your repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "GitHub Actions"
3. **Push to main branch** - the GitHub Action will automatically deploy your site

### Manual Deployment

If you prefer manual deployment:

1. Go to your repository Settings
2. Navigate to "Pages"
3. Select "Deploy from a branch"
4. Choose your main branch and `/ (root)` folder
5. Click "Save"

## 🔧 Local Development

### Prerequisites
- A modern web browser
- Git (for version control)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. Open `http://localhost:8000` in your browser

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🎨 Customization

### Colors
The website uses a modern color scheme defined in `styles.css`:
- Primary: Bootstrap primary colors
- Accent: Custom gradients for company branding
- Text: Dark grays for readability

### Fonts
- **Primary**: Inter (Google Fonts) - Modern, clean, professional
- **Fallback**: System fonts for optimal performance

### Icons
- **Bootstrap Icons**: For UI elements and services
- **Font Awesome**: For additional icon variety

## 🔄 Updates and Maintenance

### Adding New Services
1. Edit `index.html` to add new service sections
2. Update `styles.css` for custom styling
3. Add any new functionality to `script.js`

### Content Updates
- Service descriptions in `index.html`
- Company information and contact details
- Case studies and testimonials

## 📞 Support

For questions or support regarding this website template, please refer to the documentation or create an issue in the repository.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Sparient** - Empowering businesses with cutting-edge technology solutions.
