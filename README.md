# ProMech Mobile - Professional Mobile Mechanic Website

A modern, sleek, fully-responsive website for mobile mechanic services built with HTML/CSS/JavaScript.

## ✨ Features

✅ **Modern Design** - Contemporary dark theme with gradient accents  
✅ **Fully Responsive** - Works perfectly on desktop, tablet, and mobile  
✅ **Fast Loading** - Single HTML file, no dependencies  
✅ **All 5 Suggestions Included:**
- Professional service showcase with 6 service categories
- Transparent pricing cards (with featured tier highlighting)
- Contact form with appointment booking system
- Beautiful image gallery with hover effects
- Customer testimonials section

## 📋 Sections

1. **Hero** - Eye-catching landing section with call-to-action buttons
2. **Services** - 6 service cards with icons and descriptions
3. **Pricing** - 3 pricing tiers with full details
4. **Gallery** - 6 high-quality service images with overlays
5. **Testimonials** - 3 customer reviews with 5-star ratings
6. **Appointment Booking** - Complete form for scheduling services
7. **Contact** - Phone, email, and service area information
8. **Footer** - Social media links and copyright

## 🚀 How to Deploy on GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New** to create a new repository
3. Name it: `username.github.io` (replace 'username' with your GitHub username)
4. Keep it **Public**
5. Click **Create repository**

### Step 2: Add Your Website
1. Download the `index.html` file from this folder
2. Click **Upload files** in your new repository
3. Drag and drop `index.html` into the upload area
4. Click **Commit changes**

### Step 3: Verify GitHub Pages is Enabled
1. Go to your repository **Settings**
2. Scroll to **Pages** section
3. Under "Source", make sure "Deploy from a branch" is selected
4. Select **main** branch and **/ (root)** folder
5. Click **Save**

### Step 4: Access Your Site
Your website is now live at: `https://username.github.io`

---

### Using a Custom Domain (Optional)
1. In Settings > Pages, scroll to "Custom domain"
2. Enter your domain (e.g., `promechmobile.com`)
3. Click **Save**
4. Update your domain's DNS settings with GitHub's values (shown in settings)

## 🎨 Customization Guide

### Change Business Information
Edit these sections in `index.html`:

**Contact Details** (around line 850):
```html
<p>(555) 123-4567</p>  <!-- Change phone -->
<p>info@promech.com</p> <!-- Change email -->
```

**Services** (around line 380):
Update the 6 service cards with your actual services

**Pricing** (around line 420):
Modify prices and service tiers

**Testimonials** (around line 560):
Add real customer reviews

### Change Colors
Edit CSS variables at the top of the style section (around line 15):
```css
:root {
    --primary: #0f172a;      /* Dark background */
    --secondary: #ff6b35;    /* Orange accent */
    --accent: #00d9ff;       /* Cyan accent */
    /* ... etc ... */
}
```

### Change Gallery Images
Replace the Unsplash image URLs with your own service photos:
```html
<img src="YOUR_IMAGE_URL" alt="Service Description">
```

### Update Logo Text
Find the logo and change:
```html
<div class="logo">⚙️ ProMech</div>
```

## 📱 Features Breakdown

### Modern Sleek Design ✨
- Dark theme with neon cyan and orange accents
- Smooth animations and transitions
- Gradient overlays and floating elements
- Professional typography

### Services Section 🔧
- 6 customizable service cards
- Hover animations with gradient sheen effect
- Icons using emoji for easy customization

### Pricing Tiers 💰
- 3 pricing cards with transparent background
- Featured tier with scale highlight
- Checkmark list for included features
- Easy to add/remove pricing options

### Image Gallery 📸
- 6 responsive gallery items
- Hover overlay with service labels
- Uses real mechanic service images from Unsplash
- Smooth zoom effect on hover

### Testimonials ⭐
- 3 customer review cards
- 5-star rating display
- Professional typography
- Left border accent color

### Appointment Booking Form 📅
- Professional form layout
- Vehicle type and service selection
- Date picker for scheduling
- Additional notes textarea
- Form validation
- Success message on submission

### Contact Section 📞
- Phone, email, and service area info
- 3 card layout with icons
- Hover animations

## 🛠 Technical Details

- **Single File**: Everything in one `index.html`
- **No Dependencies**: Pure HTML, CSS, JavaScript
- **Performance**: Optimized animations using CSS transforms
- **Accessibility**: Semantic HTML structure
- **Mobile First**: Responsive breakpoints at 768px and 480px

## 📸 Gallery Image Sources

The gallery uses high-quality images from Unsplash (free, with attribution). Images include:
- Oil change service
- Tire replacement
- Brake service
- Battery check
- Computer diagnostics
- Mobile on-site service

Replace these URLs with your own service photos for authenticity.

## 🔧 JavaScript Features

✓ Form submission handling  
✓ Mobile menu toggle  
✓ Smooth scroll navigation  
✓ Input validation  
✓ Success notifications  

## 📊 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Pro Tips

1. **Add Real Photos**: Replace Unsplash images with actual service photos for credibility
2. **Update Contact**: Change phone, email, and service area to your business info
3. **Add Review Widget**: Consider adding Google Reviews integration
4. **Form Backend**: Currently logs to console - integrate with form service (Formspree, Netlify Forms, etc.)
5. **Analytics**: Add Google Analytics for traffic tracking
6. **SEO**: Update meta tags in `<head>` for better search visibility

## 📝 Making Changes

1. Download the file
2. Open in any text editor (VS Code, Sublime, Notepad++, etc.)
3. Make your edits
4. Upload the updated file to GitHub
5. GitHub Pages automatically deploys the new version

## 🆘 Troubleshooting

**Site not showing?**
- Wait 1-2 minutes after pushing to GitHub
- Check Settings > Pages to ensure deployment is enabled
- Verify the file is named `index.html`

**Images not loading?**
- Check that image URLs are correct
- Ensure URLs start with `https://`
- Test URLs in browser first

**Form not submitting?**
- Currently submits to browser console
- For production, integrate with Formspree or similar service

## 📄 License

Free to use and modify for your business

---

**Need help?** Review the code comments or customize the CSS variables at the top of the file for quick style changes.

**Let's get your business online! 🚀**
