# KB-Discovery-Coach
Personal coaching website
# Dr. Kim Bland - Discovery Coach Website

Professional coaching website for Dr. Kim Bland, featuring The Discovery Map Retreat.

## 🚀 Quick Start - GitHub Pages Deployment

### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it: `kimblandcoaching` (or your preferred name)
3. Make it **Public**
4. Do NOT initialize with README (we'll add files)

### Step 2: Upload Files
1. Create this folder structure in your repository:
   ```
   /
   ├── index.html
   └── images/
       ├── KBDC-logo.png
       ├── KBDC-logo-icon.png
       └── BLAND-14.jpg
   ```

2. Upload the files:
   - `index.html` → root directory
   - Logo files → `images/` folder
   - Photo → `images/` folder

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Scroll to **Pages** (left sidebar)
3. Under **Source**, select: `Deploy from a branch`
4. Under **Branch**, select: `main` and `/root`
5. Click **Save**

### Step 4: Access Your Site
- GitHub will build your site (takes 1-3 minutes)
- Your site will be at: `https://[your-username].github.io/kimblandcoaching/`

### Step 5: Custom Domain (Optional)
To use `kimblandcoaching.com`:

1. In your repository Settings → Pages → Custom domain
2. Enter: `kimblandcoaching.com`
3. Click Save
4. In your domain registrar (GoDaddy, Namecheap, etc.):
   - Add a CNAME record pointing to: `[your-username].github.io`
   - Or add A records pointing to GitHub's IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```

## 📁 Required Files

### Images You Need to Upload
Place these in the `images/` folder:

1. **KBDC-logo.png** - Full logo with text (hero section)
2. **KBDC-logo-icon.png** - Icon only logo (navigation & footer)
3. **BLAND-14.jpg** - Dr. Kim's photo
4. **discovery-framework.png** - Framework graphic (retreat section)

## 🎨 Brand Colors
- Deep Teal: `#004E59`
- Muted Gold: `#CBA35C`
- Warm Cream: `#F7F3E8`

## 📝 Content Notes

### What's Included
- ✅ Secular, inclusive language
- ✅ Professional credentials
- ✅ Discovery Map framework (high-level)
- ✅ Promise statement from screenshots
- ✅ Her coaching philosophy
- ✅ Contact form ready for integration
- ✅ Mobile responsive design
- ✅ Accessibility features

### What's NOT Included (By Design)
- ❌ Detailed retreat activities
- ❌ Biblical references
- ❌ Over-explanation of methodology
- ❌ Full framework breakdown

## 🔧 Customization

### Contact Form Setup
The form is connected to Formspree and ready to use!

Current setup:
```html
<form action="https://formspree.io/f/xreewppz" method="POST">
```

When someone submits the form, you'll receive an email notification. You can manage submissions at [Formspree.io](https://formspree.io).

**To change the form destination:**
1. Log into your Formspree account
2. Create a new form
3. Copy the new form ID
4. Update line 576 in `index.html`

### Update Phone Number
Currently shows: `719-651-4089`
- Line 374 in navigation
- Line 697 in contact section
- Line 731 in footer

## 📱 Testing

Before going live:
1. Test all navigation links
2. Test contact form
3. Check mobile responsiveness
4. Verify all images load
5. Test on different browsers

## 🆘 Troubleshooting

**Images not showing?**
- Verify images are in `/images/` folder
- Check file names match exactly (case-sensitive)
- Paths in HTML: `images/filename.png`

**Site not updating?**
- GitHub Pages can take 1-3 minutes to rebuild
- Hard refresh browser: `Ctrl+Shift+R` (PC) or `Cmd+Shift+R` (Mac)

**404 Error?**
- Check GitHub Pages is enabled in Settings
- Verify branch is set to `main` and path to `/root`

## 📞 Support

For technical questions about GitHub Pages:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

## ✅ Launch Checklist

- [ ] Repository created
- [ ] Files uploaded (index.html + images)
- [ ] GitHub Pages enabled
- [ ] Site loads correctly
- [ ] All images display
- [ ] Mobile view works
- [ ] Contact form configured
- [ ] Phone numbers correct
- [ ] Custom domain setup (if applicable)
- [ ] Tested on multiple browsers

---

**Built with:** HTML5, CSS3, JavaScript (Vanilla)  
**Fonts:** Cinzel (serif headers), Montserrat (body)  
**Hosted:** GitHub Pages
