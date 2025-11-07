# Modern Minimalist Portfolio

A clean, professional portfolio website with a sophisticated gray and brown color aesthetic. Built with pure HTML, CSS, and JavaScript for optimal performance and easy customization.

## 🎨 Design Features

- **Color Palette**: Muted grays and earthy browns for a modern, cozy feel
- **Typography**: Elegant fonts (Inter & Playfair Display)
- **Minimalist UI**: Rounded elements, clean spacing, subtle shadows
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **Fully Responsive**: Optimized for all devices from mobile to desktop

## 🚀 Quick Start

### Option 1: XAMPP (Recommended for your setup)

1. Make sure XAMPP is running
2. Navigate to: `http://localhost/Portfolio/`
3. Your portfolio should load automatically!

### Option 2: Live Server (VS Code)

1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Simple HTTP Server

```bash
# Using Python
python -m http.server 8000

# Then visit: http://localhost:8000
```

## 📁 File Structure

```
Portfolio/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
└── README.md          # This file
```

## ✏️ Customization Guide

### 1. Personal Information

**Open `index.html` and update:**

- Line 40: Replace `"Your Name"` with your actual name
- Line 41: Change `"Creative Developer & Designer"` to your role
- Line 42: Update the tagline to match your expertise
- Lines 57-88: Add your bio and personal details
- Lines 109-217: Update project cards with your actual projects
- Lines 328-346: Add your contact information

### 2. Colors (Optional)

**Open `styles.css` and modify the `:root` variables:**

```css
:root {
    /* Current colors - modify as needed */
    --gray-lightest: #E5E5E5;
    --gray-light: #CFCFCF;
    --gray-medium: #A6A6A6;
    --gray-dark: #4F4F4F;
    
    --brown-light: #B08968;
    --brown-medium: #7F5549;
    --brown-dark: #5E3A2B;
}
```

### 3. Add Your Photo

Replace the placeholder in the About section:

```html
<!-- Replace this: -->
<div class="placeholder-image">
    <i class="fas fa-user"></i>
</div>

<!-- With: -->
<img src="your-photo.jpg" alt="Your Name">
```

### 4. Add Real Project Images

Replace project placeholders:

```html
<!-- Replace this: -->
<div class="placeholder-project">
    <i class="fas fa-laptop-code"></i>
</div>

<!-- With: -->
<img src="project-screenshot.jpg" alt="Project Name">
```

### 5. Skills Section

Update skill names and percentages in `index.html` (lines 235-305):

```html
<div class="skill-info">
    <span>Your Skill</span>
    <span>85%</span>
</div>
<div class="skill-bar">
    <div class="skill-progress" style="width: 85%"></div>
</div>
```

### 6. Social Links

Update social media URLs in `index.html` (lines 353-356):

```html
<a href="https://github.com/yourusername" class="social-link">
    <i class="fab fa-github"></i>
</a>
```

## 🎯 Sections Overview

### Hero Section
- Large welcoming headline
- Role/title display
- Call-to-action buttons
- Smooth scroll indicator

### About Me
- Professional photo placeholder
- Biography text
- Contact details
- Personal information

### Projects
- Card-based layout
- Project descriptions
- Technology tags
- Live demo & code links

### Skills
- Categorized skill sets
- Visual progress bars
- Icon representations
- Percentage indicators

### Contact
- Working contact form
- Contact information cards
- Social media links
- Clean, accessible design

## 🔧 Form Integration

The contact form currently shows a success notification. To make it functional:

### Option 1: Formspree (Easiest)

1. Sign up at [formspree.io](https://formspree.io)
2. Get your form endpoint
3. Update the form action in `index.html`:

```html
<form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

4. Remove or modify the JavaScript form handler in `script.js`

### Option 2: EmailJS

1. Sign up at [emailjs.com](https://www.emailjs.com)
2. Add EmailJS SDK to `index.html`
3. Update the form handler in `script.js`

### Option 3: Backend Integration

Connect to your own backend API in the form submit handler (`script.js`, line 99).

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## ✨ Features

- ✅ Smooth scroll navigation
- ✅ Mobile hamburger menu
- ✅ Scroll-triggered animations
- ✅ Skill bar animations
- ✅ Parallax effects
- ✅ Hover effects on cards
- ✅ Form validation
- ✅ Notification system
- ✅ Active navigation highlighting
- ✅ Optimized performance

## 🎨 Typography

**Primary Font**: Inter (body text)
- Professional and highly readable
- Modern sans-serif design

**Heading Font**: Playfair Display (headings)
- Elegant and sophisticated
- Serif design for contrast

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📦 Dependencies

All dependencies are loaded via CDN - no installation required!

- **Google Fonts**: Inter & Playfair Display
- **Font Awesome**: Icons (v6.4.0)

## 🚀 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to Settings → Pages
3. Select branch and root folder
4. Your site will be live at: `https://yourusername.github.io/Portfolio/`

### Netlify

1. Drag and drop the Portfolio folder to [netlify.com](https://www.netlify.com)
2. Your site goes live instantly!

### Vercel

```bash
npm i -g vercel
cd Portfolio
vercel
```

## 💡 Tips for Success

1. **Replace all placeholder content** with your real information
2. **Add high-quality images** for projects and profile
3. **Update social links** to your actual profiles
4. **Test on multiple devices** to ensure responsiveness
5. **Optimize images** before adding them (use WebP format)
6. **Add meaningful project descriptions** that highlight your skills
7. **Keep the content concise** and professional
8. **Update regularly** with new projects and skills

## 📸 Screenshots

Your portfolio includes:
- Clean, modern hero section with gradient background
- Professional about section with image placeholder
- Card-based project showcase with hover effects
- Visual skill indicators with animated progress bars
- Functional contact form with information cards

## 🎯 Performance

- Lightweight: ~15KB (HTML + CSS + JS combined)
- No external dependencies except fonts and icons
- Optimized animations using CSS transforms
- Debounced scroll handlers for smooth performance
- Lazy loading support for images

## 🔄 Future Enhancements

Consider adding:
- Blog section
- Testimonials slider
- Dark mode toggle
- More animation effects
- Project filtering
- Downloadable resume
- Live chat integration

## 📝 License

This is a free template - feel free to use it for your personal portfolio!

## 🤝 Support

If you need help customizing your portfolio:
1. Check the inline comments in the code
2. Refer to this README
3. Test changes in your browser's developer tools
4. Make backups before major changes

---

**Made with ❤️ for aspiring developers and designers**

Enjoy building your professional online presence!
