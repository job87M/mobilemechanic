# Quick Customization Cheat Sheet

## 🎯 Top Changes to Make First

### 1. Business Name & Contact Info
**Find this in the code:**
```
Line ~55: <div class="logo">⚙️ ProMech</div>
Line ~845: <p>(555) 123-4567</p>
Line ~849: <p>info@promech.com</p>
```

**Change to:**
```html
<div class="logo">🔧 YourBusinessName</div>
<p>(YOUR) PHONE-NUMBER</p>
<p>your.email@business.com</p>
```

---

### 2. Services (Your 6 Main Services)
**Find lines ~370-420** - Each service card looks like:
```html
<div class="service-card">
    <div class="service-icon">🛢️</div>
    <h3>Oil Changes</h3>
    <p>Complete oil and filter changes with full fluid top-offs. Extending your engine's lifespan has never been easier.</p>
</div>
```

**Change the icon, title, and description** to match your services.

---

### 3. Pricing
**Find lines ~430-480** - Update prices in each card:
```html
<div class="price-tag">$65</div>  <!-- Change this -->
<li>Your service here</li>       <!-- Change these -->
```

---

### 4. Gallery Images
**Find lines ~540-570** - Replace image URLs:
```html
OLD: <img src="https://images.unsplash.com/photo-1486262715619-3417b3999elated?w=400&h=400&fit=crop" alt="Oil Change Service">

NEW: <img src="https://your-image-url.com/photo.jpg" alt="Oil Change Service">
```

💡 **Tip:** Upload your photos to Imgur, Cloudinary, or use your own hosting

---

### 5. Testimonials
**Find lines ~590-620** - Replace customer reviews:
```html
<p class="testimonial-text">"Your customer quote here"</p>
<p class="testimonial-author">Customer Name</p>
```

---

### 6. Colors (Dark Theme Customization)
**Find lines ~15-24** - Change the color scheme:
```css
:root {
    --primary: #0f172a;      /* Main dark background */
    --secondary: #ff6b35;    /* Orange/warm accent */
    --accent: #00d9ff;       /* Cyan/bright accent */
    --text-light: #e2e8f0;   /* Light text */
    --text-muted: #94a3b8;   /* Muted text */
}
```

### Popular Color Combinations:

**Modern Blue (Cyan & Blue):**
```css
--primary: #0a0e27;
--secondary: #2563eb;
--accent: #0ea5e9;
```

**Professional Red (Red & Black):**
```css
--primary: #1a1a1a;
--secondary: #dc2626;
--accent: #ef4444;
```

**Fresh Green (Green & White):**
```css
--primary: #064e3b;
--secondary: #10b981;
--accent: #6ee7b7;
```

---

## 🚀 How to Deploy Changes

### Local Testing
1. Save your edits in a text editor
2. Open the `index.html` file in your browser
3. Check all changes look good
4. No internet needed for local preview!

### Deploy to GitHub Pages
1. Upload the updated `index.html` to your GitHub repository
2. Changes go live within 1-2 minutes
3. No rebuild needed - instant updates!

---

## 📸 Image Tips

### Where to Find Free Images:
- **Unsplash**: unsplash.com (mechanic searches)
- **Pexels**: pexels.com
- **Pixabay**: pixabay.com
- **Imgur**: imgur.com (upload and get free URL)

### Image URL Format:
Make sure URLs are:
- ✅ Start with `https://`
- ✅ End with `.jpg`, `.png`, or `.webp`
- ✅ Direct links (not pages)

### Example Good URLs:
```
https://images.unsplash.com/photo-1517420879312-b6be4f625c45?w=400&h=400&fit=crop
https://imgur.com/abc123.jpg
https://your-domain.com/images/service.jpg
```

---

## 🎨 Common Edits Quick Reference

### Change Hero Title
**Find:** `<h1>Professional Mobile Mechanics on Demand</h1>`  
**Change to:** `<h1>Your Title Here</h1>`

### Change Hero Subtitle
**Find:** `<p>Expert automotive repair...</p>`  
**Change to:** `<p>Your description here</p>`

### Change Section Headers
**Find:** `<h2>Our Services</h2>`  
**Change to:** `<h2>What We Offer</h2>`

### Add More Services
Copy this template and paste it in the services-grid:
```html
<div class="service-card">
    <div class="service-icon">EMOJI_HERE</div>
    <h3>Service Name</h3>
    <p>Service description goes here.</p>
</div>
```

### Add More Testimonials
Copy this template and paste it in the testimonials-grid:
```html
<div class="testimonial-card">
    <div class="stars">★★★★★</div>
    <p class="testimonial-text">"Customer quote here"</p>
    <p class="testimonial-author">Name</p>
    <p class="testimonial-role">Verified Customer</p>
</div>
```

---

## ⚙️ Tech Tips

### Form Handling
Currently, form submissions show a pop-up alert. To actually receive emails:

**Option 1: Use Formspree (Free)**
1. Go to formspree.io
2. Create account
3. Replace form action: 
```html
<form action="https://formspree.io/f/YOUR_ID" method="POST">
```

**Option 2: Use Netlify (Free)**
- Redeploy on Netlify instead of GitHub Pages
- Add `netlify` attribute to form

---

## 🔍 Line Number Reference

| Feature | Location |
|---------|----------|
| Logo | Line ~55 |
| Navigation | Line ~50-60 |
| Hero Title | Line ~150 |
| Services Section | Line ~370-420 |
| Pricing Cards | Line ~430-480 |
| Gallery | Line ~540-570 |
| Testimonials | Line ~590-620 |
| Appointment Form | Line ~650-800 |
| Contact Info | Line ~840-860 |
| Colors (CSS) | Line ~15-24 |
| Animations (CSS) | Line ~890-920 |

---

## 📱 Testing Checklist

Before launching, test on:
- [ ] Desktop Chrome/Firefox
- [ ] Mobile Safari (iPhone)
- [ ] Mobile Chrome (Android)
- [ ] Tablet view
- [ ] All links work
- [ ] Images load
- [ ] Form submits
- [ ] Navigation scrolls smooth

---

## 💡 Pro Tips

1. **Keep your brand consistent** - Use 2-3 main colors
2. **Update regularly** - Add new services/testimonials monthly
3. **Use real photos** - Professional photos > stock photos
4. **Mobile first** - Test on phone before launching
5. **Analytics** - Add Google Analytics to track visitors

---

## ❓ Questions?

- **Form not working?** Set up Formspree (see Form Handling section)
- **Images not showing?** Check URL starts with https://
- **Colors look wrong?** Clear browser cache (Ctrl+Shift+Delete)
- **Changes not live?** Wait 2 minutes and hard refresh (Ctrl+F5)

---

**You're all set! Edit, customize, and launch your website! 🚀**
