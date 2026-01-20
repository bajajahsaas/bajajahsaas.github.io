# Ahsaas Bajaj - Personal Website

A modern, professional portfolio website showcasing ML engineering work, research publications, patents, and speaking engagements.

## 🚀 Quick Start

### Setting up GitHub Pages

1. **Create a new repository**
   - Go to GitHub and create a new repository named `your-username.github.io`
   - For example: `bajajahsaas.github.io`
   - Make it public

2. **Upload your files**
   - Upload `index.html` to the root of your repository
   - Alternatively, clone the repo and push:
   ```bash
   git clone https://github.com/your-username/your-username.github.io
   cd your-username.github.io
   # Copy index.html to this directory
   git add index.html
   git commit -m "Initial commit: Add personal website"
   git push origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select the `main` branch
   - Click Save
   - Your site will be published at `https://your-username.github.io`

## ✏️ Customization

### Update Your Information

1. **Google Scholar Link** (Line 663)
   - Replace `YOUR_ID` with your actual Google Scholar ID
   - Find it in your Scholar profile URL

2. **Profile Photo** (Optional)
   - Add a profile photo to the hero section if desired
   - Upload image to repository and reference it

3. **Contact Information**
   - Email: Already set to `bajajahsaas@gmail.com`
   - Update GitHub, LinkedIn links if they've changed

### Adding New Content

**New Publications:**
Add a new publication card in the publications section:
```html
<div class="publication-card">
    <div class="publication-title">Your Paper Title</div>
    <div class="publication-authors">Author Names</div>
    <div class="publication-venue">Conference/Journal Name</div>
</div>
```

**New Speaking Engagement:**
```html
<div class="speaking-card">
    <div class="speaking-event">Event Name</div>
    <div class="speaking-topic">Topic Description</div>
    <div class="speaking-date">Date</div>
</div>
```

**New Award:**
```html
<div class="award-card">
    <div class="award-title">Award Name</div>
    <div class="award-description">Description</div>
</div>
```

## 🎨 Design Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Modern Typography**: Uses Fraunces (serif) for headings and DM Sans for body
- **Smooth Animations**: Fade-in effects and hover states for enhanced UX
- **Sticky Navigation**: Always accessible navigation bar
- **Clean Layout**: Professional, industry-focused design

## 🔧 Advanced Customization

### Color Scheme
Edit CSS variables in the `:root` section (starting at line 13):
```css
:root {
    --bg-primary: #fafaf9;
    --text-accent: #0ea5e9;
    /* etc. */
}
```

### Fonts
Current fonts:
- Display: Fraunces (serif)
- Body: DM Sans (sans-serif)

To change fonts, update the Google Fonts import and CSS font-family declarations.

## 📱 Mobile Optimization

The website is fully responsive with breakpoints at 768px. Mobile optimizations include:
- Single column layouts
- Adjusted font sizes
- Simplified navigation
- Touch-friendly buttons

## 🌐 Adding Custom Domain (Optional)

1. Create a file named `CNAME` in your repository
2. Add your custom domain (e.g., `ahsaasbajaj.com`)
3. Configure DNS settings with your domain provider
4. Point to GitHub Pages servers

## 📊 Analytics (Optional)

Add Google Analytics by inserting tracking code before `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🐛 Troubleshooting

**Site not showing up?**
- Wait 5-10 minutes after enabling GitHub Pages
- Check repository settings > Pages
- Ensure `index.html` is in the root directory
- Verify repository name matches `username.github.io`

**Styling issues?**
- Clear browser cache
- Check browser console for errors
- Verify all CSS is within `<style>` tags

## 📄 License

Feel free to use this template for your own personal website. Attribution appreciated but not required.

## 🤝 Contributing

This is a personal website, but suggestions for improvements are welcome via issues or pull requests.

---

Built with HTML, CSS, and JavaScript. No frameworks required - pure, performant code.
