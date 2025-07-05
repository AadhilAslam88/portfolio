# Deploying Your Portfolio to GitHub Pages

This guide will help you deploy your Ahmed Aadhil Data Science Portfolio to GitHub Pages for free hosting.

## 🚀 Quick Deployment Steps

### 1. Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in to your account
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `portfolio` (or any name you prefer)
4. Make it public (required for free GitHub Pages)
5. Don't initialize with README (we already have one)
6. Click "Create repository"

### 2. Upload Your Code

You have two options:

#### Option A: Using Git Commands (Recommended)
```bash
# In your project folder
git init
git add .
git commit -m "Initial commit: Ahmed Aadhil Portfolio"
git branch -M main
git remote add origin https://github.com/AadhilAslam88/portfolio.git
git push -u origin main
```

#### Option B: Upload via GitHub Web Interface
1. Download the source code archive from your Replit
2. Extract the files
3. Go to your GitHub repository
4. Click "uploading an existing file"
5. Drag and drop all your project files
6. Commit the changes

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the sidebar
4. Under "Source", select "GitHub Actions"
5. The workflow will automatically deploy your site

### 4. Access Your Live Portfolio

After deployment (usually 2-5 minutes), your portfolio will be available at:
```
https://AadhilAslam88.github.io/portfolio
```

## 🔧 Important Notes

### Static Deployment
The GitHub Pages deployment creates a static version of your portfolio:
- ✅ All pages and sections work perfectly
- ✅ Responsive design and animations
- ✅ Project showcase and filtering
- ❌ Contact form backend (form won't submit to database)

### Contact Form Alternatives for Static Sites
Since GitHub Pages only hosts static content, you can:

1. **Use a form service** like:
   - [Formspree](https://formspree.io/) - Free tier available
   - [Netlify Forms](https://www.netlify.com/products/forms/) - If you deploy to Netlify instead
   - [EmailJS](https://www.emailjs.com/) - Send emails directly from frontend

2. **Replace with direct contact links**:
   ```html
   <a href="mailto:aslamaadhil99@gmail.com">Send Email</a>
   <a href="tel:+94712833936">Call Me</a>
   ```

### Custom Domain (Optional)
To use a custom domain like `ahmedaadhil.com`:
1. Buy a domain from a registrar
2. In your repository settings → Pages → Custom domain
3. Add your domain and enable HTTPS

## 🔄 Updating Your Portfolio

Whenever you make changes:
1. Update your files in the repository
2. Commit and push the changes
3. GitHub Actions will automatically rebuild and deploy

## 📱 Alternative Hosting Options

### For Full Functionality (with database):
- **Vercel** - Free tier with serverless functions
- **Netlify** - Free tier with edge functions  
- **Railway** - Free tier with PostgreSQL
- **Render** - Free tier with database hosting

### Just Frontend (like GitHub Pages):
- **Netlify** - Easier setup than GitHub Pages
- **Vercel** - Great performance and easy deployment
- **Surge.sh** - Simple command-line deployment

## 🎯 Next Steps

1. Follow the deployment steps above
2. Share your live portfolio URL: `https://AadhilAslam88.github.io/portfolio`
3. Add the URL to your LinkedIn profile and resume
4. Consider setting up analytics with Google Analytics

Your portfolio is now ready to showcase your Data Science skills to potential employers and collaborators!
