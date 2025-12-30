# Deploy Your Website to GitHub Pages

## Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `personal-website` (or your preferred name)
3. Make it **Public** (required for free GitHub Pages)
4. **Don't** check any boxes (no README, .gitignore, or license)
5. Click "Create repository"

## Step 2: Push Your Code
After creating the repository, run these commands in your terminal:

```bash
cd "/home/mayur/Desktop/Personal website"

# Add your GitHub repository as remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/personal-website.git

# Rename branch to main (GitHub uses 'main' by default)
git branch -M main

# Push your code
git push -u origin main
```

## Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Your site will be live at: `https://YOUR_USERNAME.github.io/personal-website/`

## Alternative: Quick Deploy with Netlify (Even Easier!)
If you prefer an easier option:
1. Go to https://app.netlify.com/drop
2. Drag and drop your entire website folder
3. Your site will be live instantly with a random URL
4. You can customize the domain name in settings

## Your Live Website URL
Once deployed, your website will be accessible at:
- **GitHub Pages**: `https://YOUR_USERNAME.github.io/personal-website/`
- **Netlify**: `https://random-name.netlify.app` (or custom domain)

---

**Note**: Make sure to replace `YOUR_USERNAME` with your actual GitHub username in the commands above.

