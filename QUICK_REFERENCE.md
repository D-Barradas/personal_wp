# 🎨 Quick Reference - Customization Shortcuts

## 🔴 Immediate Customization (5 minutes)

### 1. Update Email & Social Links
**File**: `_config.yml` (Lines 115-135)
```yaml
email            : "your.email@example.com"
# Update all URLs in the "links:" section below
```

### 2. Update Your Name & Bio
**File**: `_config.yml` (Lines 115-118)
```yaml
name             : "Your Full Name"
bio              : "Your professional tagline"
location         : "Your City/Country"
```

### 3. Update Project Titles & Descriptions
**Files**: `index.html` (Featured Projects) or `projects.md` (Full Portfolio)

Search for: `[Add your project description here]`

Replace with actual project details.

---

## 🟠 Content to Fill In (15-30 minutes)

### Homepage Stats (`index.html` - Lines ~79-102)
```html
<div class="stat-number">50+</div>  <!-- Update numbers -->
<div class="stat-label">Students Trained</div>
```

### Academic Page (`academics.md`)
- Fill education history
- Add certifications
- List awards and recognitions
- Add publications (if applicable)

### Projects Page (`projects.md`)
- Add 8 project titles and descriptions
- Update technology stack for each
- Add GitHub/demo links

### Skills Section (`index.html` - Lines ~332-456)
Replace `[Add Skill]` placeholders with:
- Real skill names
- Your proficiency level (Beginner/Intermediate/Advanced)

### Contact Page (`contact.md`)
- Update email addresses
- Verify all social media links
- Add your location/timezone

---

## 🔵 Brand & Appearance Customization

### Change Colors
**File**: `assets/css/custom.css` (Lines 1-13)
```css
:root {
  --primary-blue: #003366;      /* Headers, main text */
  --accent-orange: #ff8c00;     /* Buttons, highlights */
  --white: #ffffff;              /* Backgrounds */
}
```

### Add Profile Picture
1. Save image to: `assets/images/profile.jpg`
2. Update `_config.yml`:
```yaml
author:
  avatar: /assets/images/profile.jpg
```

### Change Skin/Dark Theme
**File**: `_config.yml` (Line 16)
```yaml
minimal_mistakes_skin: "dark"  # Options: air, aqua, contrast, dark, dirt, neon, mint, plum, sunrise
```

---

## 📄 Page Placeholders Checklist

### index.html
- [ ] Line ~59: Your professional title
- [ ] Line ~60: Your tagline
- [ ] Lines ~79-102: Update stats (50+, 15+, 100+, 5+)
- [ ] Lines ~111-127: About section text
- [ ] Lines ~132-296: Achievement cards (6 items)
- [ ] Lines ~303-458: Featured projects (6 items)
- [ ] Lines ~463-558: Skills section (complete placeholders)

### academics.md
- [ ] Lines ~25-50: First degree info
- [ ] Lines ~51-76: Second degree info
- [ ] Lines ~91-156: Certifications (4 items)
- [ ] Lines ~162-225: Awards (3 items)
- [ ] Lines ~231-298: Publications (3 items)
- [ ] Lines ~302-325: Additional credentials

### projects.md
- [ ] Lines ~33-117: Project 1-8 titles & descriptions
- [ ] Lines ~45,77,109...: Technology badges
- [ ] All project links (View Details, GitHub, Live Demo)

### contact.md
- [ ] Lines ~31-46: Email address
- [ ] Lines ~47-62: LinkedIn URL
- [ ] Lines ~63-78: GitHub URL
- [ ] Lines ~79-94: Twitter handle
- [ ] Lines ~95-109: Location/Timezone
- [ ] Lines ~159-179: Contact form

### _config.yml
- [ ] Line 115: Author name
- [ ] Line 116: Profile picture path
- [ ] Line 117: Bio/description
- [ ] Line 118: Location
- [ ] Line 119: Email
- [ ] Lines 121-133: All social media links

---

## 🔗 Link Reference

### Internal Links
- Homepage: `/`
- Projects: `/projects/`
- Academics: `/academics/`
- Contact: `/contact/`
- Blog/Posts: `/year-archive/`

### External Links (Update These)
- Email: `mailto:your.email@example.com`
- GitHub: `https://github.com/yourusername`
- LinkedIn: `https://linkedin.com/in/yourusername`
- Twitter: `https://twitter.com/yourusername`

---

## 💾 How to Edit Files

### Option 1: VS Code (Recommended)
1. Open folder in VS Code
2. Edit files directly
3. Save (Ctrl+S / Cmd+S)
4. Commit and push to GitHub

### Option 2: GitHub Web Editor
1. Go to your repository on GitHub.com
2. Click the file you want to edit
3. Click the pencil icon (✏️)
4. Make changes
5. Click "Commit changes"

### Option 3: Command Line
```bash
# Open file in default editor
nano _config.yml

# Or using VS Code
code _config.yml
```

---

## 🔍 Search & Replace Shortcuts

Quick find-and-replace patterns:

| Find | Replace | Location |
|------|---------|----------|
| `[Add your project description here]` | Your actual description | `index.html`, `projects.md` |
| `[Add Skill]` | Real skill name | `index.html` |
| `[Degree Name]` | Your degree | `academics.md` |
| `your.email@example.com` | Your actual email | Multiple files |
| `yourusername` | Your GitHub username | `_config.yml`, pages |
| `[Year Graduated]` | Actual year | `academics.md` |

---

## 🚀 Deploy to Live

### Once You're Ready:
```bash
# Test locally
bundle exec jekyll serve
# Visit: http://localhost:4000

# Push to GitHub
git add .
git commit -m "Update personal website content"
git push origin main
```

Your site will be live at: `https://yourusername.github.io/personal_wp/`

---

## 📱 Test Responsiveness

1. Open your site in browser
2. Press F12 (DevTools)
3. Click device icon (top-left)
4. Test on iPhone SE, iPad, and Desktop views
5. All text should be readable
6. All buttons should be clickable

---

## 🎯 Priority Order

1. **Essential** (Do First):
   - Update email & social links
   - Add 3+ projects
   - Update contact info

2. **Important** (Next):
   - Fill academic section
   - Complete skills list
   - Update all placeholders

3. **Nice-to-Have** (Polish):
   - Add profile picture
   - Customize colors
   - Add more content

---

## ✨ Pro Tips

- **Emoji icons**: Using emoji (🎓, 🔬, 📊) keeps design clean without extra images
- **Spacing**: Leave white space for better readability
- **Links**: Test every link before deploying
- **Mobile**: Always check on mobile first for better UX
- **Content**: Shorter is better - 2-3 sentences per item
- **Updates**: Add new projects monthly to keep fresh

---

## 🆘 Common Issues & Fixes

| Problem | Solution |
|---------|----------|
| Links show as raw text | Check URL format: `/page/` not `page.html` |
| Colors not showing | Clear cache: Ctrl+Shift+Del, then refresh |
| Page not updating | Restart: `bundle exec jekyll serve` |
| Mobile layout broken | Check viewport meta tag in head |
| Images not loading | Verify path: `/assets/images/filename.jpg` |

---

**Remember**: Your website is a living document. Update it regularly with new projects, achievements, and skills! 🌟

---

*Last updated: 2025-12-26*
*For detailed guide, see: SETUP_GUIDE.md*
