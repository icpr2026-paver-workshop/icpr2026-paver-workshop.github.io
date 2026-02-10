# Deployment Guide - Hosting on GitHub Pages

Your website is ready to be hosted! Follow these steps to make it accessible online for free using GitHub Pages.

## Option 1: GitHub Pages (Recommended - Free)

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top right → "New repository"
3. Repository name: `icpr2026-workshop` (or any name you prefer)
4. Keep it **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README (we already have files)
6. Click "Create repository"

### Step 2: Push Your Code to GitHub

After creating the repository, GitHub will show you commands. Run these commands in your terminal:

```bash
# Add the remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/icpr2026-workshop.git

# Push your code
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. In the left sidebar, click "Pages"
4. Under "Source", select branch: **main**
5. Click "Save"
6. Wait 1-2 minutes for deployment

Your website will be live at:
```
https://YOUR_USERNAME.github.io/icpr2026-workshop/
```

---

## Option 2: Netlify (Alternative - Free)

1. Go to [netlify.com](https://www.netlify.com) and sign up
2. Click "Add new site" → "Deploy manually"
3. Drag and drop your project folder
4. Your site will be live immediately!
5. You can customize the URL in site settings

---

## Option 3: Vercel (Alternative - Free)

1. Go to [vercel.com](https://vercel.com) and sign up
2. Click "Add New" → "Project"
3. Import your GitHub repository (after pushing to GitHub)
4. Click "Deploy"
5. Your site will be live immediately!

---

## Quick Commands Reference

```bash
# To update your website after making changes:
git add .
git commit -m "Update website content"
git push

# GitHub Pages will automatically update in 1-2 minutes
```

---

## Custom Domain (Optional)

After deployment, you can connect a custom domain:
- **GitHub Pages**: Settings → Pages → Custom domain
- **Netlify**: Site settings → Domain management
- **Vercel**: Project settings → Domains

---

## Need Help?

If you encounter any issues:
1. Make sure your GitHub repository is **Public**
2. Check that `index.html` is in the root directory
3. Wait a few minutes after enabling GitHub Pages
4. Clear your browser cache if the site doesn't update

Your website is ready to share with the world! 🚀
