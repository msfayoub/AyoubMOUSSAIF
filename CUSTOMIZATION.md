# Customization Checklist & Guide

Use this guide to update your portfolio with your actual information from your CV.

## 📝 Personal Information

### Basic Details
- [ ] Full Name: ___________________
- [ ] Professional Title: ___________________
- [ ] Email: ___________________
- [ ] Phone: ___________________
- [ ] Location: ___________________
- [ ] LinkedIn URL: ___________________
- [ ] GitHub URL: ___________________
- [ ] Twitter/X URL: ___________________

**Update locations in HTML:**
- Line ~20: Hero subtitle
- Line ~139: Contact section email link
- Line ~145: Contact section phone link
- Line ~150: Contact section location
- Line ~210: Footer links

---

## 🎓 Education

### Education Entry 1
- [ ] Degree/Program Name: ___________________
- [ ] University/Institution: ___________________
- [ ] Graduation Year: ___________________
- [ ] GPA (optional): ___________________
- [ ] Relevant Coursework: ___________________

### Education Entry 2
- [ ] Degree/Program Name: ___________________
- [ ] University/Institution: ___________________
- [ ] Graduation Year: ___________________

**Update in HTML:**
Lines ~98-114 (Education section in index.html)

Example:
```html
<div class="edu-card">
    <h3>Bachelor of Science in Computer Science</h3>
    <p class="institution">Université Mohammed VI Polytechnique</p>
    <p class="year">2020 - 2024</p>
    <p class="description">Major in Software Engineering with focus on Web Development</p>
</div>
```

---

## 💼 Experience

### Job 1
- [ ] Job Title: ___________________
- [ ] Company Name: ___________________
- [ ] Start Date: ___________________
- [ ] End Date (or "Present"): ___________________
- [ ] Key Responsibility 1: ___________________
- [ ] Key Responsibility 2: ___________________
- [ ] Key Responsibility 3: ___________________

### Job 2
- [ ] Job Title: ___________________
- [ ] Company Name: ___________________
- [ ] Start Date: ___________________
- [ ] End Date: ___________________
- [ ] Key Responsibility 1: ___________________
- [ ] Key Responsibility 2: ___________________
- [ ] Key Responsibility 3: ___________________

**Update in HTML:**
Lines ~64-95 (Experience section)

Example:
```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Full Stack Developer</h3>
        <p class="company">Tech Company Name | 2023 - Present</p>
        <p>Description of role and achievements.</p>
        <ul class="responsibilities">
            <li>Built responsive web applications using React and Node.js</li>
            <li>Managed database operations with MongoDB</li>
            <li>Collaborated with 5+ team members on agile projects</li>
        </ul>
    </div>
</div>
```

---

## 🛠️ Skills

### Technical Skills
**Frontend:**
- [ ] Skill 1: ___________________
- [ ] Skill 2: ___________________
- [ ] Skill 3: ___________________
- [ ] Skill 4: ___________________

**Backend:**
- [ ] Skill 1: ___________________
- [ ] Skill 2: ___________________
- [ ] Skill 3: ___________________
- [ ] Skill 4: ___________________

**Tools & Platforms:**
- [ ] Skill 1: ___________________
- [ ] Skill 2: ___________________
- [ ] Skill 3: ___________________
- [ ] Skill 4: ___________________

**Update in HTML:**
Lines ~117-135 (Skills section)

Example:
```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-tags">
        <span class="skill-tag">HTML</span>
        <span class="skill-tag">CSS</span>
        <span class="skill-tag">JavaScript</span>
        <span class="skill-tag">React</span>
        <span class="skill-tag">Vue.js</span>
    </div>
</div>
```

---

## 🚀 Projects

### Project 1
- [ ] Project Name: ___________________
- [ ] Description: ___________________
- [ ] Technologies Used: ___________________
- [ ] Live Link (optional): ___________________
- [ ] GitHub Link (optional): ___________________
- [ ] Image/Screenshot: ___________________

### Project 2
- [ ] Project Name: ___________________
- [ ] Description: ___________________
- [ ] Technologies Used: ___________________
- [ ] Live Link (optional): ___________________
- [ ] GitHub Link (optional): ___________________

### Project 3
- [ ] Project Name: ___________________
- [ ] Description: ___________________
- [ ] Technologies Used: ___________________
- [ ] Live Link (optional): ___________________
- [ ] GitHub Link (optional): ___________________

**Update in HTML:**
Lines ~137-181 (Projects section)

Example:
```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>E-Commerce Platform</h3>
        <p>Full-stack e-commerce solution with payment integration and inventory management.</p>
        <div class="project-tags">
            <span class="tag">React</span>
            <span class="tag">Node.js</span>
            <span class="tag">Stripe</span>
        </div>
        <div class="project-links">
            <a href="https://project-live-link.com" class="project-link">View</a>
            <a href="https://github.com/username/project" class="project-link">Code</a>
        </div>
    </div>
</div>
```

---

## 🖼️ Add Profile Picture

1. **Save your image** as `profile.jpg` in the AyoubWebsite folder
2. **Update HTML** - Replace the avatar placeholder section (~line 38):

Replace:
```html
<div class="avatar-placeholder">
    <i class="fas fa-user"></i>
</div>
```

With:
```html
<img src="profile.jpg" alt="Ayoub's Profile Picture" class="avatar-placeholder" style="border-radius: 20px; object-fit: cover;">
```

---

## 📊 About Section Stats

### Update Statistics
- [ ] Years of Experience: _____ (number)
- [ ] Projects Completed: _____ (number)
- [ ] Clients/Users: _____ (number)

**Update in HTML:**
Lines ~49-62 (About stats)

Example:
```html
<div class="stat">
    <h3>3+</h3>
    <p>Years of Experience</p>
</div>
<div class="stat">
    <h3>15+</h3>
    <p>Projects Completed</p>
</div>
<div class="stat">
    <h3>20+</h3>
    <p>Happy Clients</p>
</div>
```

---

## 📱 Mobile Testing Checklist

After updates, test on mobile:
- [ ] Mobile menu opens/closes
- [ ] All text is readable
- [ ] Images display correctly
- [ ] Buttons are clickable
- [ ] Forms work properly
- [ ] No horizontal scrolling

Use Chrome DevTools (F12 → Device toolbar) to test

---

## 🎨 Optional Styling Customizations

### Change Colors
Edit `styles.css` variables:
```css
:root {
    --primary-color: #667eea;      /* Main blue */
    --secondary-color: #764ba2;    /* Purple */
    --accent-color: #f093fb;       /* Pink */
}
```

### Popular Color Combinations:

**Tech Blue:**
```
--primary-color: #0061ff;
--secondary-color: #0040e8;
--accent-color: #00d4ff;
```

**Orange Energy:**
```
--primary-color: #ff6b6b;
--secondary-color: #ee5a6f;
--accent-color: #ffa94d;
```

**Green Fresh:**
```
--primary-color: #1abc9c;
--secondary-color: #16a085;
--accent-color: #27ae60;
```

---

## ✉️ Email Contact Setup (Optional)

To make your contact form work, choose one:

### Option 1: Formspree (Easiest)
1. Visit https://formspree.io
2. Create new form
3. Copy your form ID
4. Update form action in HTML (line ~193):
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: EmailJS
1. Visit https://www.emailjs.com
2. Follow setup guide
3. Add script to your HTML head

---

## 📋 Final Checklist Before Deployment

- [ ] All personal information updated
- [ ] Education section filled
- [ ] Experience timeline complete
- [ ] Skills updated with your technologies
- [ ] Projects added (at least 2-3)
- [ ] Contact information correct
- [ ] Profile picture added
- [ ] Social media links updated
- [ ] Grammar/spelling checked
- [ ] Mobile version tested
- [ ] All links working
- [ ] No placeholder text remaining
- [ ] Colors (if changed) look professional

---

## 🚀 Deployment Command Reference

### GitHub Pages
```bash
cd AyoubWebsite
git init
git add .
git commit -m "Portfolio website"
git branch -M main
git remote add origin https://github.com/USERNAME/USERNAME.github.io.git
git push -u origin main
```

### Netlify
- Drag your AyoubWebsite folder to Netlify.com
- Site goes live instantly

### Vercel
```bash
npm i -g vercel
vercel
```

---

## 💡 Pro Tips

1. **Keep it simple** - Too many sections can overwhelm visitors
2. **Use actual images** - Placeholder images look unprofessional
3. **Quantify achievements** - "Increased performance by 40%" > "Improved performance"
4. **Fresh content** - Update portfolio regularly
5. **Mobile first** - Many visitors use phones
6. **Fast loading** - Optimize images and minify code
7. **Professional tone** - While personality shows, keep it professional

---

## 📞 Support Resources

- MDN Web Docs: https://developer.mozilla.org/
- HTML/CSS/JS Tutorial: https://www.w3schools.com/
- GitHub Help: https://docs.github.com/
- Netlify Support: https://docs.netlify.com/

---

Good luck with your portfolio! Remember, keep it updated as your skills and experience grow. 🎯
