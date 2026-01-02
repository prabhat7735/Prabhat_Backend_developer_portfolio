# Personal Portfolio Website - Prabhat Kumar Panigrahy

A modern, responsive personal portfolio website for a Python & Django Developer.

## Features

- **Modern Design**: Clean, professional UI with smooth animations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Enhanced navigation experience
- **Interactive Elements**: Hover effects, animations, and transitions
- **Contact Form**: Functional contact form with validation
- **SEO Friendly**: Proper meta tags and semantic HTML

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styling and responsive design
├── js/
│   └── script.js       # JavaScript for interactivity
└── README.md           # This file
```

## Sections Included

1. **Hero Section**: Name, role, introduction, and call-to-action buttons
2. **About Me**: Education background and professional introduction
3. **Skills**: Categorized technical skills display
4. **Projects**: Showcase of 3-4 projects with descriptions and GitHub links
5. **Resume**: Download resume section
6. **Contact**: Contact information and contact form
7. **Footer**: Social media links and copyright

## How to Use

1. Open `index.html` in a web browser to view the portfolio
2. Customize the content by editing `index.html`
3. Modify colors and styling in `css/styles.css`
4. Update JavaScript functionality in `js/script.js`

## Customization Guide

### Update Personal Information

1. **Email**: Search for `prabhat@example.com` in `index.html` and replace with your email
2. **Social Links**: Update GitHub and LinkedIn URLs in:
   - Hero section
   - Contact section
   - Footer section

### Add Resume PDF

1. Place your resume PDF in the root directory
2. In `index.html`, update the resume download link:
   ```html
   <a href="resume.pdf" class="btn btn-primary" id="downloadResume">
   ```
3. Or update `js/script.js` to point to your resume file:
   ```javascript
   window.open('resume.pdf', '_blank');
   ```

### Change Colors

Edit CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #2563eb;  /* Main brand color */
    --secondary-color: #7c3aed; /* Secondary color */
    /* ... other variables */
}
```

### Add/Remove Projects

Edit the projects section in `index.html`:
- Duplicate a `.project-card` div for each new project
- Update project details, icons, and GitHub links

### Update Skills

Modify the skills section in `index.html`:
- Add or remove skill categories
- Update skill tags as needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- JavaScript (Vanilla JS)
- Font Awesome (for icons)
- Google Fonts (Inter & Poppins)

## Notes

- The contact form currently uses a `mailto:` link. For production use, integrate with a backend service or email API
- Resume download button shows an alert. Update it to point to your actual resume PDF
- All external links (GitHub, LinkedIn) should be updated with your actual profile URLs

## License

Free to use and modify for personal portfolio purposes.

