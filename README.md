# Ayoub's Portfolio Website

A modern, responsive portfolio website built with HTML5, CSS3, and JavaScript. Perfect for showcasing your projects and professional experience.

## Features

✨ **Modern Design**
- Gradient color scheme with smooth animations
- Dark theme optimized for eye comfort
- Fully responsive (mobile, tablet, desktop)
- Smooth scroll behavior

🎯 **Key Sections**
- Hero section with call-to-action buttons
- About section with statistics
- Experience timeline
- Education details
- Skills showcase
- Featured projects portfolio
- Contact form
- Social media links

⚡ **Performance**
- Fast loading times
- Optimized images
- Smooth animations
- Mobile-first responsive design

## Getting Started

### 1. Customize Your Information

Edit the `index.html` file and update:
- Your name and headline
- About section content
- Experience timeline entries
- Education information
- Skills and technologies
- Project details
- Contact information (email, phone, location)
- Social media links

### 2. Add Your Profile Picture

Replace the avatar placeholder with your actual image:
- Add your image file (e.g., `profile.jpg`) to the project folder
- Update the avatar section in `index.html` to display your image

### 3. Test Locally

Open `index.html` in your web browser to view your portfolio locally. No server required!

## File Structure

```
AyoubWebsite/
├── index.html          # Main HTML structure
├── styles.css          # Styling and responsive design
├── script.js           # Interactive features (hamburger menu, animations, etc.)
├── profile.jpg         # Your profile picture (optional)
└── README.md           # This file
```

## Customization Guide

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;      /* Main color */
    --secondary-color: #764ba2;    /* Gradient color */
    --accent-color: #f093fb;       /* Highlight color */
    --dark-bg: #0f0f1e;            /* Background */
    --text-primary: #ffffff;       /* Main text */
    --text-secondary: #a0aec0;     /* Secondary text */
}
```

### Fonts
To change the font, modify the `font-family` in `styles.css`

### Add More Sections
Copy any existing section and modify the content. The structure is:
```html
<section id="section-name" class="section-class">
    <div class="container">
        <h2 class="section-title">Section Name</h2>
        <!-- Your content here -->
    </div>
</section>
```

## Deployment Options

### Option 1: GitHub Pages (Free) ⭐ RECOMMENDED

1. Create a GitHub account at https://github.com
2. Create a new repository named `yourusername.github.io`
3. Clone the repository to your computer
4. Copy your portfolio files into the cloned folder
5. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial portfolio"
   git push origin main
   ```
6. Your site will be live at `https://yourusername.github.io`

**Advantages:** Free forever, no ads, works with custom domains

---

### Option 2: Netlify (Free)

1. Go to https://netlify.com
2. Sign up with GitHub or email
3. Drag and drop your project folder
4. Your site is live immediately with a free Netlify URL
5. Upgrade to custom domain later (paid)

**Advantages:** Simple drag-and-drop, fast deployment, automatic HTTPS

---

### Option 3: Vercel (Free)

1. Go to https://vercel.com
2. Sign up with GitHub
3. Import your repository
4. Your site deploys automatically
5. Get a free `*.vercel.app` domain

**Advantages:** Amazing performance, automatic deployments on push

---

### Option 4: Traditional Hosting

Popular affordable options:
- **Hostinger** (~$2.99/month)
- **Bluehost** (~$2.95/month)
- **NameCheap** (~$2.88/month)

Steps:
1. Choose a hosting provider
2. Purchase a domain
3. Upload files via FTP
4. Point domain to hosting

---

## Getting a Free Domain Name

### Option 1: GitHub Pages (Free with GitHub account)
- Automatically get `yourusername.github.io`
- No additional domain needed
- Best for starting out

### Option 2: Freenom.com (Free domains) ⭐
1. Go to https://www.freenom.com
2. Search for a domain (`.tk`, `.ml`, `.ga`, `.cf` are free TLDs)
3. Register for free (1-12 months)
4. Point to your hosting
5. Renew annually (also free)

**Note:** Free domains can look less professional, but good for starting

---

### Option 3: Cheap Domains with Hosting

- **Namecheap:** Domain + hosting combo deals (~$3-5/month)
- **Hostinger:** Includes free domain for 1st year
- **Bluehost:** Free domain registration for 1st year

---

### Option 4: Use a Subdomain (Free)

- GitHub Pages: `portfolios.user.github.io`
- Netlify: `myname.netlify.app`
- Vercel: `myname.vercel.app`

---

## Complete Deployment Tutorial

### Step 1: Prepare Your Code
```bash
# Make sure all your files are ready
- index.html (updated with your info)
- styles.css
- script.js
- Any images
```

### Step 2: Deploy to GitHub Pages (Recommended)

```bash
# Initialize git in your project folder
cd AyoubWebsite
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial portfolio commit"

# Create main branch if needed
git branch -M main

# Add remote (replace yourusername)
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git push -u origin main
```

**Your site will be live at:** `https://yourusername.github.io`

### Step 3: Add a Custom Domain (Optional - $10-15/year)

1. Buy domain from Namecheap, GoDaddy, or similar
2. Go to your GitHub repository settings
3. Scroll to "Pages" section
4. Enter your custom domain
5. Update domain nameservers to point to GitHub
6. GitHub will generate an SSL certificate automatically

---

## Contact Form Setup (Optional - Add Backend)

The contact form currently logs to console. To make it functional:

### Using Formspree (Free)
1. Go to https://formspree.io
2. Sign up and create a form
3. Update the form in your HTML:
```html
<form class="contact-form" action="https://formspree.io/f/FORM_ID" method="POST">
```

### Using EmailJS (Free)
1. Go to https://www.emailjs.com
2. Sign up and follow setup
3. Update the JavaScript code

---

## SEO Optimization

Add this meta description to your `index.html` in the `<head>`:
```html
<meta name="description" content="Ayoub's portfolio - Full Stack Developer with 5+ years experience">
<meta name="keywords" content="developer, portfolio, projects, skills">
<meta name="author" content="Your Name">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

---

## Performance Tips

1. **Optimize Images:** Compress images before adding them
2. **Lazy Loading:** Load images only when needed
3. **Minify Code:** Minimize CSS/JS file sizes
4. **CDN:** Use Content Delivery Networks for faster loading

---

## Troubleshooting

**Images not showing?**
- Check file path in HTML
- Ensure image files are in same folder as HTML

**Styles not applying?**
- Clear browser cache (Ctrl+Shift+Delete)
- Check CSS file path

**Mobile menu not working?**
- Check browser console for JavaScript errors
- Ensure script.js is properly linked

**Deployment issues?**
- Check file structure
- Ensure index.html is in root folder
- Verify file permissions

---

## Next Steps

1. ✅ Customize all content with your information
2. ✅ Test on mobile devices
3. ✅ Choose deployment option
4. ✅ Deploy your site
5. ✅ Add to your resume/CV
6. ✅ Share with potential employers

---

## Quick Links

- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [Netlify Docs](https://docs.netlify.com)
- [Responsive Design Tips](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Web Design Best Practices](https://www.nngroup.com/articles/responsive-web-design-definition/)

---

## License

Free to use and modify. Attribution appreciated but not required.

---

## Questions?

Feel free to customize and enhance your portfolio. The key is to make it reflect your personality and skills!

Good luck with your portfolio! 🚀
