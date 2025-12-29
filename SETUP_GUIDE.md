# 🚀 Your Professional Portfolio Website - Setup & Customization Guide

## Overview

Your modern, professional personal website is now ready! Built with Jekyll and the Minimal Mistakes theme, featuring a professional dark theme with deep blue and orange accent colors.

### ✨ What's Included

- **Hero Section** - Eye-catching landing section with animated gradient background
- **Academic Achievements** - Dedicated page for education, certifications, and honors
- **Projects Showcase** - Featured portfolio with 6+ project cards (filterable on projects page)
- **Skills & Technologies** - Organized skill categories with placeholder items for customization
- **Contact Page** - Multiple ways to connect with your audience
- **Color Scheme** - Professional deep blue (#003366) and orange (#ff8c00) with white backgrounds
- **Responsive Design** - Mobile-friendly on all devices
- **Interactive Elements** - Smooth animations, hover effects, and transitions

---

## 🎨 Your New Pages

### 1. **Homepage** (`/`)
- **Location**: `index.html`
- **Features**:
  - Hero section with your name and professional tagline
  - Stats overview (students trained, projects completed, etc.)
  - About section
  - Academic achievements grid
  - Featured projects (6 cards)
  - Skills section with categories
  - Contact call-to-action

### 2. **Academic Achievements** (`/academics/`)
- **Location**: `academics.md`
- **Sections**:
  - Education timeline
  - Certifications & credentials
  - Awards & honors
  - Publications & research
  - Additional credentials

### 3. **Projects Showcase** (`/projects/`)
- **Location**: `projects.md`
- **Features**:
  - Project filter buttons (All, Machine Learning, Visualization, Data Science)
  - 8 project cards with full details
  - Technology badges
  - Links to GitHub, demos, and project details
  - Collaboration call-to-action

### 4. **Contact & Connect** (`/contact/`)
- **Location**: `contact.md`
- **Includes**:
  - Multiple contact methods (email, LinkedIn, GitHub, Twitter)
  - Contact form
  - Collaboration opportunities
  - Expected response times

### 5. **Navigation**
- **Location**: `_data/navigation.yml`
- Links to: Home, Projects, Academics, Contact, Blog

---

## 📝 Quick Customization Guide

### Step 1: Update Your Email & Social Links

**File**: `_config.yml`

Find the "Site Author" section and update:

```yaml
author:
  name             : "Didier Barradas Bautista"
  email            : "your.email@example.com"  # ← Update this
  links:
    - label: "Email"
      url: "mailto:your.email@example.com"  # ← Update this
    - label: "Twitter"
      url: "https://twitter.com/dxbarradas"  # ← Update this
    - label: "GitHub"
      url: "https://github.com/yourusername"  # ← Update this
    - label: "LinkedIn"
      url: "https://linkedin.com/in/yourusername"  # ← Update this
```

### Step 2: Fill in Your Project Details

**File**: `index.html` (Featured Projects section) or `projects.md` (Full projects page)

Replace placeholders:

```html
<!-- Before -->
<h3 class="project-title">Project Title 1</h3>
<p class="project-description">
  [Add your project description here...]
</p>

<!-- After -->
<h3 class="project-title">Advanced Neural Network Classification</h3>
<p class="project-description">
  Developed a deep learning model achieving 95% accuracy on image classification. 
  Implemented using TensorFlow and deployed on AWS for production use.
</p>
```

### Step 3: Add Your Skills

**File**: `index.html` - Skills & Technologies section

Replace the `[Add Skill]` placeholders:

```html
<!-- Before -->
<div class="skill-item placeholder">
  <div class="skill-icon">?</div>
  <div class="skill-name">[Add Skill]</div>
  <div class="skill-level">Placeholder</div>
</div>

<!-- After -->
<div class="skill-item">
  <div class="skill-icon">🧠</div>
  <div class="skill-name">XGBoost</div>
  <div class="skill-level">Advanced</div>
</div>
```

### Step 4: Update Academic Information

**File**: `academics.md`

Fill in your education and certifications:

```markdown
<h3 style="color: var(--primary-blue); font-size: 1.2rem; margin-bottom: 8px;">[Degree Name]</h3>
<p style="color: var(--accent-orange); font-weight: 700; margin-bottom: 8px;">[University Name]</p>
<p style="color: #666; margin-bottom: 10px;">📅 [Year Graduated]</p>
<p style="color: #555; line-height: 1.6;">
  [Add degree details, major/minor, GPA, relevant coursework, thesis title, or honors received]
</p>
```

### Step 5: Update Contact Information

**File**: `contact.md`

Update your contact methods:

```html
<a href="mailto:your.email@example.com" style="...">
  your.email@example.com
</a>
```

---

## 🎯 Color Scheme Reference

The website uses a professional color palette you specified:

- **Primary Blue**: `#003366` - Headers, text, borders
- **Dark Blue**: `#001a33` - Darkest elements
- **Light Blue**: `#004d99` - Highlights
- **Accent Orange**: `#ff8c00` - Call-to-action buttons, icons
- **Light Orange**: `#ffa500` - Hover states
- **White**: `#ffffff` - Backgrounds
- **Light Gray**: `#f5f5f5` - Alternate sections

All CSS variables are defined in: `assets/css/custom.css`

---

## 🔧 Advanced Customization

### Change the Color Scheme

**File**: `assets/css/custom.css` (Lines 1-13)

```css
:root {
  --primary-blue: #003366;      /* Change this */
  --dark-blue: #001a33;         /* Change this */
  --light-blue: #004d99;        /* Change this */
  --accent-orange: #ff8c00;     /* Change this */
  --light-orange: #ffa500;      /* Change this */
  /* ... rest of colors ... */
}
```

### Modify Section Styling

All custom styles are in: `assets/css/custom.css`

Common sections to customize:
- `.hero-section` - Homepage hero section
- `.project-card` - Project cards
- `.achievement-card` - Achievement cards
- `.btn-cta` - Call-to-action buttons
- `.section-title` - Section headings

### Add a Profile Picture

**File**: `_config.yml`

```yaml
author:
  avatar: /assets/images/profile-photo.jpg  # Add your image path here
```

Then place your image in: `assets/images/profile-photo.jpg`

---

## 📊 Statistics to Update

**File**: `index.html` - Stats Section

Update the numbers in the stats container:

```html
<div class="stat-box">
  <div class="stat-number">50+</div>  <!-- Update this -->
  <div class="stat-label">Students Trained</div>
</div>
```

---

## 📱 Mobile Responsiveness

The website is fully responsive! It automatically adapts to:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

No additional configuration needed. All components stack properly on smaller screens.

---

## 🚀 How to Deploy

### Option 1: GitHub Pages (Recommended)

1. Push your changes to your GitHub repository
2. Go to repository Settings → Pages
3. Select the branch where your code is pushed
4. Your site will be live at: `https://yourusername.github.io/personal_wp/`

### Option 2: Local Testing

```bash
# Install dependencies (first time only)
bundle install

# Serve locally
bundle exec jekyll serve

# Visit: http://localhost:4000
```

---

## ✅ Checklist for Completion

- [ ] Updated email address in `_config.yml`
- [ ] Updated social media links (Twitter, LinkedIn, GitHub)
- [ ] Filled in at least 3 project descriptions in `/projects/`
- [ ] Added your education details in `/academics/`
- [ ] Updated your skills with at least 5 real skills
- [ ] Filled in contact information on `/contact/`
- [ ] Updated stats on homepage (`index.html`)
- [ ] Added profile picture (optional but recommended)
- [ ] Tested all links work correctly
- [ ] Viewed on mobile device to verify responsiveness
- [ ] Deployed to GitHub Pages or hosting

---

## 🎓 File Structure

```
personal_wp/
├── index.html              ← Homepage
├── academics.md            ← Academic Achievements
├── projects.md             ← Projects Showcase
├── contact.md              ← Contact Page
├── _config.yml             ← Site configuration
├── assets/
│   └── css/
│       └── custom.css      ← Your custom styles (deep blue + orange)
├── _data/
│   └── navigation.yml      ← Navigation menu
└── _includes/
    └── head.html           ← Links custom CSS
```

---

## 🆘 Troubleshooting

### Links not working?
- Make sure URLs start with `/` for internal links
- Check that filenames match exactly

### Colors not showing correctly?
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Check `assets/css/custom.css` is being loaded

### Projects not filtering?
- Make sure JavaScript is enabled in browser
- Check browser console for errors (F12)

### Mobile layout broken?
- The CSS includes responsive breakpoints at 768px
- Test in browser DevTools mobile view

---

## 📚 Resources

- **Jekyll Documentation**: https://jekyllrb.com/docs/
- **Minimal Mistakes Theme**: https://mmistakes.github.io/minimal-mistakes/
- **CSS Grid Guide**: https://css-tricks.com/snippets/css/complete-guide-grid/
- **Color Picker Tool**: https://colorpicker.com/

---

## 💡 Tips for Success

1. **Keep descriptions concise** - 2-3 sentences per project or achievement
2. **Use emoji strategically** - Adds visual interest without extra images
3. **Update regularly** - Add new projects and achievements as you progress
4. **Test before deploying** - Use `bundle exec jekyll serve` locally first
5. **Backup your content** - Keep copies of your project descriptions
6. **SEO friendly** - The site is already optimized for search engines

---

## 🎉 You're All Set!

Your professional portfolio website is ready to showcase your work! 

**Next Steps**:
1. Fill in your personal details
2. Add your projects and achievements
3. Deploy to GitHub Pages
4. Share your new website! 🚀

Good luck! 🌟

---

**Questions or need help?** Reach out and customize away! This is your professional space to shine.
