# 🚀 DEPLOYMENT GUIDE: Your Professional Website

Your professional website is ready! Follow these steps to go live:

---

## **STEP 1: Create a GitHub Account (if you don't have one)**
- Go to [github.com](https://github.com)
- Sign up with your email
- Verify your email

---

## **STEP 2: Create a New Repository on GitHub**

**Option A: Create a standard repository**
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `personal-website` (or any name you prefer)
3. Description: "Professional portfolio website"
4. Choose "Public" (required for free GitHub Pages)
5. Click "Create repository"

**Option B: Create a special repository (Recommended for cleaner URL)**
1. Create a repository named: `YOUR-GITHUB-USERNAME.github.io`
   - Replace YOUR-GITHUB-USERNAME with your actual GitHub username
   - Example: `jean-claude-mitchozounou.github.io`
2. This will give you a cleaner URL without `/personal-website` path

---

## **STEP 3: Push Your Code to GitHub**

Open Terminal and run these commands:

```bash
cd /home/jc1er/PersonalSite

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git

# Rename branch to main (GitHub's default)
git branch -M main

# Push to GitHub
git push -u origin main
```

Replace:
- `YOUR-USERNAME` with your GitHub username
- `YOUR-REPOSITORY-NAME` with your repository name

---

## **STEP 4: Enable GitHub Pages**

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar)
4. Under "Build and deployment":
   - Source: Select **Deploy from a branch**
   - Branch: Select **main**
   - Folder: **/root** (not /docs)
5. Click **Save**

GitHub will show: "Your site is live at: `https://YOUR-USERNAME.github.io/...`"

---

## **STEP 5: Update Your Profile**

### Add to LinkedIn:
1. Go to your LinkedIn profile
2. Click "Edit Public Profile"
3. Add your website URL in the "Websites" section
4. Save

### Customize the Website:
- Email: `sagbo.mitchozounou@um6p.ma` ✅ (Already set)
- LinkedIn: Already configured ✅
- ResearchGate: Already configured ✅
- Phone: `+212 610 495852` ✅ (Already set)

---

## **STEP 6: Testing Your Site**

After deployment:
1. Wait 1-2 minutes for GitHub Pages to build
2. Visit: `https://YOUR-USERNAME.github.io/personal-website/`
   - OR `https://YOUR-USERNAME.github.io/` (if using Option B)
3. Click through all sections to verify:
   - ✅ Navigation works
   - ✅ Images load
   - ✅ CV downloads
   - ✅ Social links work
   - ✅ Mobile responsive (test on phone)

---

## **FUTURE UPDATES: How to Update Your Website**

When you want to make changes:

```bash
cd /home/jc1er/PersonalSite

# Make your edits to index.html, css/styles.css, etc.

# Stage changes
git add .

# Commit with a message
git commit -m "Update: Added new research project"

# Push to GitHub
git push
```

GitHub Pages will automatically update your site within 1-2 minutes.

---

## **OPTIONAL: Custom Domain**

If you own a domain (e.g., yourname.com):

1. In repository Settings → Pages
2. Add your custom domain
3. Update DNS records at your domain registrar
4. GitHub will provide exact instructions

---

## **HELPFUL LINKS**

- 📖 [GitHub Pages Docs](https://pages.github.com/)
- 🎨 [CSS Customization Guide](https://www.w3schools.com/css/)
- 🔗 [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- 💼 [LinkedIn Profile Tips](https://www.linkedin.com/help/linkedin/answer/87)

---

## **Quick Troubleshooting**

| Issue | Solution |
|-------|----------|
| "Repository not found" | Check your remote URL: `git remote -v` |
| Site not updating | Wait 2 minutes and clear browser cache (Ctrl+Shift+Del) |
| Images not loading | Check file paths in index.html match your assets folder |
| Mobile view broken | Open DevTools (F12) and check responsive design |

---

## **QUESTIONS?**

- Check the README.md for customization tips
- GitHub Pages docs: https://pages.github.com/
- Contact support through GitHub

---

**Your website is ready to showcase your research! 🎉**

Updated: May 22, 2026
