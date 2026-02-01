# Personal Portfolio Website

A modern, minimalist single-page portfolio website for showcasing your MSBA education, experience, and projects. Designed with a personal blog aesthetic.

## 🚀 Quick Start

This website is designed to be hosted on GitHub Pages. Simply push this repository to your GitHub account and enable GitHub Pages in the repository settings.

## 📁 Structure

```
chloenguyen0319.github.io/
├── index.html           # Home page with Hero, About, Education, Experience
├── projects.html        # Projects portfolio page
├── beyond.html          # Beyond Analytics - interests and activities
├── css/
│   ├── main.css        # Global styles and components
│   └── responsive.css  # Mobile-responsive styles
├── js/
│   └── main.js         # Navigation, smooth scrolling, and interactions
└── assets/
    └── images/         # Profile photos and project screenshots
```

## ✨ Features

- **Clean Multi-Page Design**: Home, Projects, and Beyond Analytics pages
- **Smooth Scrolling Navigation**: Click navigation links to smoothly scroll to sections on home
- **Contact Info in Sidebar**: Easy access to contact information under profile picture
- **Beyond Analytics Page**: Showcase your interests, hobbies, and activities outside of data
- **Personal & Approachable**: Blog-style aesthetic that feels warm and personal
- **Fully Responsive**: Perfect on all devices from mobile to desktop

## ✏️ Customization Guide

### 1. Update Personal Information

Search for `[Your Name]` in `index.html`, `projects.html`, and `beyond.html` and replace with your actual name.

Update these placeholders throughout the site:
- `[Your Name]` - Your full name
- `[Your University Name]` - Your university
- `[Your Degree]` - Your degree program
- `[Month Year]` - Relevant dates
- `your.email@example.com` - Your email
- LinkedIn, GitHub URLs - Your social profiles

### 2. Add Your Resume

Place your resume PDF in the `assets/` folder and name it `resume.pdf`, or update the links in `index.html` (hero section and contact section)

### 3. Add Profile Photo

Add your professional photo to `assets/images/` and update the placeholder in the About section of `index.html`:

```html
<div class="about-image">
    <img src="assets/images/your-photo.jpg" alt="Your Name">
</div>
```

### 4. Customize Colors

Edit CSS variables in `css/main.css` (lines 8-14) to match your personal brand:

```css
:root {
    --primary-color: #2c3e50;  /* Main dark color */
    --accent-color: #3498db;   /* Accent/link color */
    --text-color: #333333;     /* Body text */
    /* ... more colors */
}
```

### 5. Update Content

#### Home Page (index.html)
The home page contains all sections in one scrollable page:

**About Section**
- Write your personal story and journey
- Update values and interests

**Education Section**
- Update your university, degree, GPA, and coursework
- Adjust skill levels in the progress bars (percentages in inline styles)
- Add your achievements

**Experience Section**
- Replace placeholder job descriptions with your actual experience
- Add company logos to `assets/images/` and update logo placeholders
- Update skills used for each position

**Contact Section**
- Update contact information and social links
- To make the form functional, integrate a service like:
  - [Formspree](https://formspree.io/)
  - [EmailJS](https://www.emailjs.com/)
  - [Netlify Forms](https://www.netlify.com/products/forms/)

#### Projects Page (projects.html)
- Replace example projects with your actual work
- Add project screenshots to `assets/images/`
- Update GitHub repository links
- Ensure `data-category` attributes match your filter buttons

### 6. Add Images

Place images in `assets/images/`:
- `profile-photo.jpg` - Your professional headshot
- `project-1.png`, `project-2.png`, etc. - Project screenshots
- `company-logo-1.png`, etc. - Company logos (optional)

## 🎨 Features

- ✅ Single-page design with smooth scrolling navigation
- ✅ Modern, minimalist, blog-style aesthetic
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Smooth animations and transitions
- ✅ Interactive project filtering on Projects page
- ✅ Mobile-friendly hamburger navigation
- ✅ SEO optimized with proper meta tags
- ✅ Accessibility compliant (ARIA labels, keyboard navigation)
- ✅ Fast loading with no external dependencies (except Google Fonts)

## 🌐 Deployment

### GitHub Pages

1. Create a repository named `yourusername.github.io`
2. Push this code to the repository
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io`

### Custom Domain (Optional)

1. Add a file named `CNAME` in the root directory
2. Add your custom domain to the file (e.g., `www.yourname.com`)
3. Configure DNS settings with your domain provider
4. Update GitHub Pages settings to use custom domain

## 🛠️ Technologies Used

- HTML5 - Semantic markup
- CSS3 - Modern styling with Grid & Flexbox
- Vanilla JavaScript - No frameworks, lightweight
- Google Fonts - Inter font family

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Tips

1. **Keep it updated**: Regularly add new projects and experiences
2. **Use real data**: Replace all placeholder content with actual information
3. **Optimize images**: Compress images before uploading (use tools like TinyPNG)
4. **Test responsiveness**: View on multiple devices before publishing
5. **Proofread**: Check for typos and grammatical errors
6. **Get feedback**: Ask peers to review before going live

## 📄 License

This template is free to use for personal portfolios. Feel free to customize it to match your style!

## 🤝 Contributing

Found a bug or want to suggest an improvement? Feel free to open an issue or submit a pull request.

---

**Good luck with your internship search! 🚀**

