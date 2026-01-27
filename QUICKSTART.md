# ⚡ QUICK START GUIDE

Get your portfolio running in **2 minutes!**

---

## 🎯 Fastest Way to Open It

### Method 1: Double-Click (Easiest)
1. Open **File Explorer**
2. Navigate to `weeklyAssignment1` folder
3. Double-click **`index.html`**
4. Browser opens automatically ✓

**That's it! Your site is live locally!**

---

### Method 2: Right-Click & Open
1. Right-click on `index.html`
2. Choose "Open with" → Your browser
3. Done! 

---

### Method 3: Drag & Drop
1. Drag `index.html`
2. Drop it on browser window
3. Done!

---

## 📱 How to Test on Mobile / Tablet

### On Same Computer
1. Open index.html
2. Press **F12** (Opens Developer Tools)
3. Click **📱 Toggle Device Toolbar** (top-left)
4. Choose "iPhone 12" or "iPad" from dropdown
5. See how it looks on mobile!

### On Your Real Phone
1. Get your computer's IP: 
   ```bash
   ipconfig
   # Look for "IPv4 Address" like 192.168.x.x
   ```
2. On phone, open browser and go to:
   ```
   http://192.168.x.x:8000
   ```
3. See it on your phone!

---

## 🔄 Using a Local Server (Better Testing)

### Windows (Easiest)
1. Open PowerShell/Command Prompt
2. Go to folder:
   ```bash
   cd C:\Users\73ank\Desktop\Pep\weeklyAssignment1
   ```
3. Run:
   ```bash
   python -m http.server 8000
   ```
4. Open browser: `http://localhost:8000`
5. Press `Ctrl+C` to stop

### Mac/Linux
```bash
cd weeklyAssignment1
python3 -m http.server 8000
# Open: http://localhost:8000
```

---

## ✅ Testing Checklist

### Home Page
- [ ] Hero animation shows
- [ ] Featured projects appear
- [ ] Skills bars display
- [ ] Navigation works

### About Page
- [ ] Timeline shows your story
- [ ] All text is readable
- [ ] Images load correctly

### Projects Page
- [ ] Gallery displays properly
- [ ] Images load
- [ ] Grid is responsive

### Contact Page
- [ ] Form appears
- [ ] Form validates (try submitting empty)
- [ ] Contact info shows correctly

### Mobile View (F12)
- [ ] Hamburger menu works
- [ ] Layout stacks vertically
- [ ] Text is readable
- [ ] No content cut off

---

## 🎨 How to Customize

### Change Your Name & Email

**Step 1:** Open `index.html` in a text editor
```html
<!-- Find this line and change the name -->
<h1>Ankit Raj</h1>

<!-- Change email -->
<a href="mailto:73ankitkrsingh@gmail.com">73ankitkrsingh@gmail.com</a>
```

**Step 2:** Refresh browser (F5)
**Step 3:** Changes appear! ✓

### Change Colors

**Step 1:** Open `assets/css/style.css`
```css
:root {
    --primary-color: #6366f1;     /* Change this - main color */
    --secondary-color: #ec4899;   /* Change this - accent color */
    --dark-bg: #0f172a;           /* Change this - background */
}
```

**Step 2:** Refresh browser
**Step 3:** Whole site changes color! ✓

### Replace Images

Find images in the `assets/images/` folder:
```html
<img src="assets/images/your-image.jpg" alt="Description">
```

Replace with your own images!

---

## 🐛 Common Issues & Fixes

### Issue: Page shows "Cannot GET /"
**Fix:** Make sure you're opening `index.html`, not the folder!

### Issue: Images don't load
**Fix:** Check the path is correct:
```html
<!-- Wrong: src="image.jpg" -->
<!-- Correct: src="assets/images/image.jpg" -->
```

### Issue: Styling looks wrong
**Fix:** 
1. Press Ctrl+F5 (Hard refresh)
2. Clear browser cache
3. Try different browser

### Issue: Form doesn't validate
**Fix:** Check browser console (F12 → Console tab) for errors

### Issue: Mobile layout broken
**Fix:**
1. Check if you edited CSS
2. Verify media queries are correct
3. Try different phone size in DevTools

### Issue: Hamburger menu not working
**Fix:** Check if JavaScript is enabled
- F12 → Console → Look for errors

---

## 🚀 Going Live (GitHub Pages)

Your site is already on GitHub!

**View it live:** https://Ankit-CSE-01.github.io/portfolio

**To update live version:**
1. Make changes locally
2. Run:
   ```bash
   git add -A
   git commit -m "Update: describe what changed"
   git push origin main
   ```
3. Wait 1-2 minutes
4. Refresh live URL
5. Done! ✓

---

## 📂 File Structure

```
weeklyAssignment1/
├── index.html                 ← HOME PAGE
├── about.html                 ← ABOUT PAGE
├── projects.html              ← PROJECTS PAGE
├── contact.html               ← CONTACT PAGE
│
├── assets/
│   ├── css/
│   │   └── style.css          ← ALL STYLING
│   ├── js/
│   │   └── script.js          ← ALL INTERACTIVITY
│   └── images/                ← YOUR IMAGES
│
├── .git/                       ← Version control (auto-managed)
├── README.md                   ← Full documentation
├── INDEX.md                    ← This file
├── QUICKSTART.md               ← Getting started
├── GITHUB_SETUP.md             ← GitHub guide
└── .gitignore                  ← Git configuration
```

---

## 🎓 Understanding the Files

### HTML Files (The Structure)
- **index.html** - Homepage with hero, featured projects, skills
- **about.html** - Your story with timeline
- **projects.html** - Project gallery and pricing
- **contact.html** - Contact form

Each has:
- Navigation menu (same on all pages)
- Main content
- Footer with social links

### CSS File (assets/css/style.css)
- **2000+ lines** of professional styling
- Responsive design (mobile, tablet, desktop)
- Animations and hover effects
- Color variables (easy to customize)

### JavaScript File (assets/js/script.js)
- **400+ lines** of interactivity
- Form validation
- Hamburger menu
- Scroll animations
- Click handlers

---

## 💡 Pro Tips

1. **Use VS Code:**
   - Opens HTML files nicely
   - Built-in preview
   - Easy editing

2. **DevTools is Your Friend:**
   - F12 to open
   - Check mobile view
   - See errors
   - Inspect elements

3. **Test in Multiple Browsers:**
   - Chrome, Firefox, Safari, Edge
   - Ensures compatibility

4. **Test on Real Phone:**
   - See actual user experience
   - Check touch interactions
   - Verify performance

5. **Keep Git Updated:**
   - Commit regularly
   - Write good messages
   - Push to GitHub

---

## 🔗 Quick Links

| Link | Purpose |
|------|---------|
| `index.html` | Open in browser to see site |
| `assets/css/style.css` | Edit colors and layout |
| `assets/js/script.js` | Edit interactivity |
| `README.md` | Full documentation |
| `GITHUB_SETUP.md` | GitHub guide |

---

## ❓ Questions?

### How do I...

**...change the header color?**
Edit `assets/css/style.css` → Find `:root { --primary-color: #6366f1; }` → Change color

**...add a new section?**
Copy a section in HTML, paste it, edit the content, the CSS handles styling automatically!

**...fix the mobile menu?**
Check `assets/js/script.js` → look for hamburger menu code

**...add my own images?**
Put image in `assets/images/` folder, then use: `<img src="assets/images/myimage.jpg">`

**...submit this for the assignment?**
1. Follow GITHUB_SETUP.md
2. Get your GitHub Pages URL
3. Submit repository + live URL

---

## ✨ You're All Set!

Your responsive portfolio website is ready to go! 🎉

**Next Steps:**
1. ✅ Open index.html in browser
2. ✅ Test all pages
3. ✅ Review the code
4. ✅ Make customizations
5. ✅ When ready, follow GITHUB_SETUP.md to submit

**Happy coding!** 💻

---

*Quick Start Guide - January 27, 2026*  
*Version: 1.0*
