# 🐙 GitHub Setup & Deployment Guide

Complete step-by-step guide to submit your portfolio using GitHub!

---

## ✅ Status Check

**Your project is already on GitHub!** ✓

- Repository: https://github.com/Ankit-CSE-01/portfolio
- Live URL: https://Ankit-CSE-01.github.io/portfolio

**All code is already pushed and committed!** ✅

---

## 🚀 What's Next?

Your repository is set up, but let's verify everything is ready for submission!

---

## 📋 Verification Checklist

### Step 1: Verify Local Repository

```bash
# Navigate to your project folder
cd C:\Users\73ank\Desktop\Pep\weeklyAssignment1

# Check git status
git status

# Should show: "On branch main" and "nothing to commit"
```

**Expected Output:**
```
On branch main
Your branch is up to date with 'origin/main'.
nothing to commit, working tree clean
```

### Step 2: Verify Remote Repository

```bash
# Check if GitHub remote is configured
git remote -v

# Should show:
# origin  https://github.com/Ankit-CSE-01/portfolio (fetch)
# origin  https://github.com/Ankit-CSE-01/portfolio (push)
```

### Step 3: Verify Files are Pushed

```bash
# See commit history
git log --oneline -5

# All commits should have "push origin main" info
```

### Step 4: Verify on GitHub Website

1. Open: https://github.com/Ankit-CSE-01/portfolio
2. Verify you see:
   - ✓ All HTML files (index.html, about.html, projects.html, contact.html)
   - ✓ assets folder with css and js
   - ✓ README.md
   - ✓ Git commit history
   - ✓ Your name as "Ankit Raj"

---

## 🌐 Enable GitHub Pages (IMPORTANT)

GitHub Pages displays your site as a live website!

### Method 1: Automatic (Recommended)

1. Go to: https://github.com/Ankit-CSE-01/portfolio/settings
2. Left menu → Click **"Pages"**
3. Under "Build and deployment":
   - Source: Select **"Deploy from a branch"** (if not already)
   - Branch: Select **"main"** 
   - Folder: Select **"/ (root)"**
4. Click **Save**
5. Wait 1-2 minutes
6. Your live URL appears at the top! 

### Method 2: Manual Configuration

If auto doesn't work:

```bash
# From your local folder
git checkout main
git pull origin main

# Create/update gh-pages branch if needed
git branch gh-pages main
git push origin gh-pages

# Then follow Method 1 above and select "gh-pages" branch
```

---

## 📱 Verify Live Site Works

After enabling GitHub Pages:

1. **Visit your live URL:** https://Ankit-CSE-01.github.io/portfolio
2. **Test these pages:**
   - [ ] Home page loads (index.html)
   - [ ] About page link works
   - [ ] Projects page link works
   - [ ] Contact page link works
   - [ ] Navigation menu works
3. **Test responsiveness:**
   - [ ] Desktop view looks good
   - [ ] Mobile view works (use DevTools - F12)
   - [ ] Tablet view works
4. **Test interactions:**
   - [ ] Hamburger menu works
   - [ ] Form validation works
   - [ ] Social links work
   - [ ] Animations play

---

## 🔄 How to Update Your Live Site

Made changes and want to update the live version?

### Step 1: Make Your Changes
```bash
# Edit files locally
# For example, change colors in assets/css/style.css
```

### Step 2: Commit Changes
```bash
git add -A
git commit -m "Update: describe your changes"
# Example: git commit -m "Update: change primary color to blue"
```

### Step 3: Push to GitHub
```bash
git push origin main
```

### Step 4: Wait & Refresh
- Wait 1-2 minutes for GitHub Pages to rebuild
- Refresh your live URL: https://Ankit-CSE-01.github.io/portfolio
- Changes appear! ✓

---

## 📊 Understanding Git Workflow

### Basic Workflow
```
1. Make changes locally
        ↓
2. Add changes (git add)
        ↓
3. Commit (git commit)
        ↓
4. Push to GitHub (git push)
        ↓
5. GitHub Pages updates automatically
        ↓
6. Live site reflects changes
```

### Commands You'll Use

```bash
# Check what changed
git status

# Stage all changes
git add -A

# Commit with message
git commit -m "Your message here"

# Push to GitHub
git push origin main

# Pull latest from GitHub
git pull origin main

# View commit history
git log --oneline
```

---

## 🎯 Assignment Submission Checklist

Use this before submitting your assignment!

- [ ] **All files created**
  - [ ] index.html ✓
  - [ ] about.html ✓
  - [ ] projects.html ✓
  - [ ] contact.html ✓
  - [ ] assets/css/style.css ✓
  - [ ] assets/js/script.js ✓
  - [ ] assets/images/ (folder exists) ✓

- [ ] **CSS Features Implemented**
  - [ ] Flexbox layout ✓
  - [ ] CSS Grid layout ✓
  - [ ] Position properties ✓
  - [ ] Media queries (3+ breakpoints) ✓
  - [ ] CSS variables ✓
  - [ ] Animations/transitions ✓
  - [ ] Pseudo-classes ✓

- [ ] **JavaScript Features**
  - [ ] Form validation ✓
  - [ ] Hamburger menu ✓
  - [ ] Interactive elements ✓
  - [ ] Event handlers ✓

- [ ] **Git & GitHub**
  - [ ] Repository created ✓
  - [ ] Code pushed to main ✓
  - [ ] 10+ commits made ✓
  - [ ] Feature branches used ✓
  - [ ] Pull requests created ✓

- [ ] **GitHub Pages**
  - [ ] Pages enabled ✓
  - [ ] Live URL works ✓
  - [ ] Site displays correctly ✓
  - [ ] All links functional ✓

- [ ] **Documentation**
  - [ ] README.md ✓
  - [ ] INDEX.md ✓
  - [ ] QUICKSTART.md ✓
  - [ ] GITHUB_SETUP.md ✓
  - [ ] Clear instructions ✓

- [ ] **Personalization**
  - [ ] Your name added ✓
  - [ ] Your email added ✓
  - [ ] Your phone added ✓
  - [ ] Your location added ✓
  - [ ] Your GitHub linked ✓
  - [ ] Your LinkedIn linked ✓
  - [ ] Your social media linked ✓

- [ ] **Testing**
  - [ ] Tested in Chrome ✓
  - [ ] Tested in Firefox ✓
  - [ ] Tested mobile view ✓
  - [ ] Tested tablet view ✓
  - [ ] All pages accessible ✓
  - [ ] No console errors ✓
  - [ ] Live site works ✓

---

## 📝 What to Submit

For your assignment, provide:

1. **Repository URL:**
   ```
   https://github.com/Ankit-CSE-01/portfolio
   ```

2. **Live Website URL:**
   ```
   https://Ankit-CSE-01.github.io/portfolio
   ```

3. **Brief Description:**
   - Include your name, email, phone
   - Explain key features
   - List CSS/JS techniques used
   - Note responsive breakpoints

**Example:**
```
Portfolio Website - Ankit Raj

Repository: https://github.com/Ankit-CSE-01/portfolio
Live Site: https://Ankit-CSE-01.github.io/portfolio

Email: 73ankitkrsingh@gmail.com
Phone: +91 8383031054
Location: Patna, Bihar, India

Features:
- 4 responsive pages (Home, About, Projects, Contact)
- 2000+ lines of professional CSS
- 400+ lines of JavaScript interactivity
- CSS Flexbox & Grid layouts
- Responsive animations and transitions
- Form validation
- Mobile-first design

Mobile Breakpoints: 480px, 768px, 1200px
```

---

## 🐛 Troubleshooting

### Problem: Live site not updating after push

**Solution:**
```bash
# Hard refresh your browser
# Windows: Ctrl + Shift + Delete
# Mac: Cmd + Shift + Delete

# Or wait 1-2 minutes and refresh
# GitHub Pages takes time to rebuild
```

### Problem: Getting "404 Not Found" on live URL

**Solution:**
1. Check if Pages is enabled:
   - Go to: https://github.com/Ankit-CSE-01/portfolio/settings/pages
   - Verify branch is "main" and folder is "/ (root)"
2. Check if files are actually pushed:
   ```bash
   git push origin main --force  # Force push if needed
   ```
3. Wait 2-3 minutes for rebuild
4. Try different browser/clear cache

### Problem: Links not working on live site

**Solution:**
Check HTML paths:
```html
<!-- WRONG - relative path won't work on GitHub Pages -->
<a href="about.html">About</a>

<!-- These work on both local and GitHub Pages -->
<a href="./about.html">About</a>
<a href="/portfolio/about.html">About</a>

<!-- The correct way for GitHub Pages -->
<!-- If repo name is "portfolio", use "./" relative paths -->
```

### Problem: CSS/Images not loading on live site

**Solution:**
```html
<!-- Wrong -->
<link rel="stylesheet" href="/style.css">
<img src="/image.jpg">

<!-- Correct for GitHub Pages -->
<link rel="stylesheet" href="./assets/css/style.css">
<img src="./assets/images/image.jpg">
```

### Problem: Committed to wrong branch

**Solution:**
```bash
# Switch to main
git checkout main

# Pull latest main
git pull origin main

# Create PR from feature branch if needed
# Or cherry-pick commits

# For quick fix, just commit directly to main:
git add -A
git commit -m "Fix: move to main"
git push origin main
```

---

## 🎓 Git Best Practices

### Good Commit Messages
```bash
# GOOD
git commit -m "Add form validation"
git commit -m "Update navbar styling"
git commit -m "Fix mobile menu bug"

# BAD
git commit -m "fix"
git commit -m "blah"
git commit -m "asdf"
```

### Making Feature Branches
```bash
# Create feature branch
git checkout -b feature/new-feature

# Make changes, commit
git add -A
git commit -m "Add new feature"

# Push feature branch
git push origin feature/new-feature

# Later, merge back to main
git checkout main
git merge feature/new-feature
```

---

## 🎯 Final Steps Before Submission

1. **Verify repository on GitHub:**
   ```bash
   # Check what's on GitHub
   git log --oneline
   # Compare with GitHub website
   ```

2. **Test live site one more time:**
   - Open: https://Ankit-CSE-01.github.io/portfolio
   - Test all pages
   - Test mobile view
   - Test form
   - Test links

3. **Document what you created:**
   - README.md explains everything
   - All code is commented
   - File structure is clear

4. **Prepare submission materials:**
   - Repository URL ✓
   - Live URL ✓
   - Project description ✓
   - Screenshots (optional) ✓

5. **Submit:**
   - Provide repo and live URLs
   - Write brief description
   - Include your contact info
   - Done! 🎉

---

## 💡 Pro Tips

1. **Keep commits small and focused**
   - Each commit = one thing
   - Makes history clean

2. **Write descriptive commit messages**
   - Future you will thank you
   - Makes reviewing easy

3. **Test before pushing**
   - Run locally first
   - Check all links
   - Verify on mobile

4. **Use branches for big changes**
   - Keep main stable
   - Merge when tested

5. **Check live site regularly**
   - Catch bugs early
   - Test in real browser

---

## 🔗 Quick Links

| Link | Purpose |
|------|---------|
| https://github.com/Ankit-CSE-01/portfolio | Your repository |
| https://Ankit-CSE-01.github.io/portfolio | Your live site |
| https://github.com/settings/tokens | GitHub access tokens |
| https://docs.github.com/en/pages | GitHub Pages docs |
| https://git-scm.com/docs | Git documentation |

---

## ✨ You're Ready!

Your portfolio is live and ready for submission! 🚀

**Repository:** https://github.com/Ankit-CSE-01/portfolio  
**Live Site:** https://Ankit-CSE-01.github.io/portfolio

**Summary:**
- ✅ Code is on GitHub
- ✅ Live site is deployed
- ✅ All features working
- ✅ Mobile responsive
- ✅ Documentation complete

**Happy Coding!** 💻

---

*GitHub Setup Guide - January 27, 2026*  
*Version: 1.0*
