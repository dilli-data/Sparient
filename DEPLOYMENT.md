# 🚀 GitHub Pages Deployment Guide

This guide will walk you through deploying your Sparient website to GitHub Pages.

## 📋 Prerequisites

- A GitHub account
- Git installed on your local machine
- Your website files ready

## 🔧 Step-by-Step Deployment

### 1. Create a New Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `sparient-website`)
5. Make it **Public** (required for free GitHub Pages)
6. Don't initialize with README (we already have one)
7. Click "Create repository"

### 2. Upload Your Website Files

#### Option A: Using Git (Recommended)

```bash
# Clone the repository
git clone https://github.com/yourusername/sparient-website.git
cd sparient-website

# Copy your website files into this folder
# (index.html, styles.css, script.js, etc.)

# Add all files to git
git add .

# Commit the changes
git commit -m "Initial website upload"

# Push to GitHub
git push origin main
```

#### Option B: Drag & Drop

1. In your new repository, click "uploading an existing file"
2. Drag and drop all your website files
3. Add a commit message
4. Click "Commit changes"

### 3. Enable GitHub Pages

1. Go to your repository's **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source**, select **GitHub Actions**
4. Click **Save**

### 4. Automatic Deployment

The GitHub Action workflow (`.github/workflows/deploy.yml`) will automatically:
- Deploy your site when you push to the main branch
- Build and optimize your static files
- Deploy to GitHub Pages

### 5. Access Your Website

Your website will be available at:
```
https://yourusername.github.io/sparient-website
```

## 🔄 Updating Your Website

### Automatic Updates

1. Make changes to your local files
2. Commit and push to GitHub:
```bash
git add .
git commit -m "Update website content"
git push origin main
```
3. The GitHub Action will automatically redeploy your site

### Manual Updates

1. Edit files directly on GitHub
2. Or upload new versions through the web interface
3. Changes will be deployed automatically

## 🛠️ Troubleshooting

### Common Issues

**Site not loading:**
- Check if GitHub Pages is enabled
- Verify the repository is public
- Wait a few minutes for initial deployment

**Changes not appearing:**
- Check GitHub Actions tab for deployment status
- Ensure you're pushing to the main branch
- Clear browser cache

**404 errors:**
- Verify `index.html` is in the root directory
- Check file names and paths

### GitHub Actions Issues

1. Go to **Actions** tab in your repository
2. Check the latest workflow run
3. Look for error messages in the logs
4. Common fixes:
   - Ensure repository is public
   - Check file permissions
   - Verify workflow file syntax

## 📱 Custom Domain (Optional)

To use a custom domain:

1. Go to repository **Settings** → **Pages**
2. Under **Custom domain**, enter your domain
3. Add a `CNAME` file to your repository with your domain
4. Configure DNS with your domain provider

## 🔒 Security Considerations

- **Public Repository**: Your website code will be public
- **No Sensitive Data**: Don't include API keys or passwords
- **HTTPS**: GitHub Pages automatically provides SSL certificates

## 📊 Performance Tips

- **Optimize Images**: Compress images before uploading
- **Minimize CSS/JS**: Consider minifying your files
- **CDN**: External libraries are already loaded from CDNs
- **Caching**: GitHub Pages provides good caching

## 📞 Need Help?

- Check [GitHub Pages documentation](https://pages.github.com/)
- Review GitHub Actions logs for errors
- Create an issue in your repository
- Check GitHub Community forums

---

**Your website will be live in minutes!** 🎉
