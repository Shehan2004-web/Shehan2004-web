# GitHub Pages Deployment Guide

This guide will help you deploy your portfolio website to GitHub Pages.

## Quick Setup (Recommended)

1. **Navigate to your repository settings:**
   - Go to https://github.com/Shehan2004-web/Shehan2004-web
   - Click on "Settings" tab

2. **Configure GitHub Pages:**
   - In the left sidebar, click "Pages"
   - Under "Source", select "Deploy from a branch"
   - Under "Branch", select your branch (e.g., `main` or `copilot/create-modern-portfolio-website`)
   - Select folder: `/ (root)`
   - Click "Save"

3. **Wait for deployment:**
   - GitHub will automatically build and deploy your site
   - This usually takes 1-3 minutes
   - You'll see a green checkmark when it's ready

4. **Access your website:**
   - Your site will be available at: `https://shehan2004-web.github.io/Shehan2004-web/`
   - You can also find the URL in the Pages settings

## Custom Domain (Optional)

If you want to use a custom domain like `shehan.dev`:

1. **Add your custom domain:**
   - In the Pages settings, enter your domain in the "Custom domain" field
   - Click "Save"

2. **Configure DNS:**
   - Add a CNAME record in your domain registrar pointing to `shehan2004-web.github.io`
   - Or add A records pointing to GitHub's IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

3. **Enable HTTPS:**
   - Wait for DNS propagation (can take up to 24 hours)
   - Check "Enforce HTTPS" in the Pages settings

## Troubleshooting

### Site not loading?
- Ensure the branch and folder are correctly selected
- Check that `index.html` is in the root directory
- Wait a few minutes for deployment to complete

### 404 Error?
- Verify the repository name matches the URL
- Check that files are committed and pushed

### CSS/JS not loading?
- All file paths are relative, so they should work automatically
- Clear your browser cache and try again

## Updating Your Website

To make changes to your website:

1. Edit the files locally or on GitHub
2. Commit your changes
3. Push to the branch configured for GitHub Pages
4. Wait 1-3 minutes for automatic redeployment

## File Structure

```
Shehan2004-web/
├── index.html          # Main HTML file (homepage)
├── styles.css          # All CSS styles
├── script.js           # All JavaScript functionality
├── .gitignore          # Git ignore rules
└── README.md           # Documentation
```

## Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- Contact: chamikascp@gmail.com
- Repository: https://github.com/Shehan2004-web/Shehan2004-web

---

**Made with ❤️ by Shehan Chamika**
