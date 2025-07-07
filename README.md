# Designer Portfolio Website

A beautiful, modern, and interactive HTML portfolio website for designers. Features smooth animations, responsive design, and an elegant way to showcase your work.

## Features

- **Modern Design**: Clean, professional layout with beautiful gradients and typography
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth animations, hover effects, and interactive elements
- **Work Showcase**: Filterable portfolio grid with project categories
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Loading Animations**: Elegant page load and scroll animations

## Sections

1. **Hero Section**: Eye-catching introduction with animated elements
2. **About Section**: Personal information and skills showcase
3. **Work Section**: Portfolio grid with filtering capabilities
4. **Contact Section**: Contact information and contact form
5. **Footer**: Social links and additional information

## Customization Guide

### Personal Information

1. **Update the hero section** in `index.html`:
   ```html
   <h1 class="hero-title">
       <span class="title-line">Your Name</span>
       <span class="title-line">Designer</span>
   </h1>
   <p class="hero-subtitle">Your tagline here</p>
   ```

2. **Update the about section**:
   - Replace the placeholder text with your personal information
   - Update the skills tags to match your expertise
   - Add your profile photo (replace the placeholder icon)

3. **Update contact information**:
   - Email: `hello@designer.com`
   - Phone: `+1 (555) 123-4567`
   - Location: `San Francisco, CA`

### Portfolio Projects

1. **Add your projects** in the work section:
   ```html
   <div class="work-item" data-category="ui-ux">
       <div class="work-image">
           <!-- Replace with your project image -->
           <img src="path/to/your/image.jpg" alt="Project Name">
           <div class="work-overlay">
               <div class="work-details">
                   <h3>Your Project Name</h3>
                   <p>Project description</p>
                   <button class="btn btn-small">View Project</button>
               </div>
           </div>
       </div>
   </div>
   ```

2. **Project categories**:
   - `ui-ux`: UI/UX Design projects
   - `branding`: Branding and identity projects
   - `web`: Web design projects
   - Add new categories as needed

### Styling Customization

1. **Colors**: Update the color scheme in `styles.css`:
   - Primary color: `#3182ce` (blue)
   - Secondary color: `#667eea` (purple)
   - Background colors: `#f7fafc` (light gray)

2. **Fonts**: The website uses Inter font family. You can change it by updating the Google Fonts link in the HTML head.

3. **Animations**: Customize animation speeds and effects in the CSS file.

### Adding Real Images

1. Create an `images` folder in your project
2. Add your project images and profile photo
3. Update the HTML to reference your images:
   ```html
   <img src="images/your-project.jpg" alt="Project Name">
   ```

### Social Media Links

Update the social media links in the footer:
```html
<div class="footer-social">
    <a href="your-dribbble-url" class="social-link"><i class="fab fa-dribbble"></i></a>
    <a href="your-behance-url" class="social-link"><i class="fab fa-behance"></i></a>
    <a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-instagram-url" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Your images folder (create this)
    ├── profile.jpg
    ├── project1.jpg
    ├── project2.jpg
    └── ...
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS animations
- Lazy loading for images (when added)
- Smooth scrolling
- Efficient JavaScript event handling

## Deployment

1. **GitHub Pages**: Upload to a GitHub repository and enable GitHub Pages
2. **Netlify**: Drag and drop your folder to Netlify
3. **Vercel**: Connect your GitHub repository to Vercel
4. **Traditional hosting**: Upload files to any web hosting service

## Customization Tips

1. **Keep it simple**: Don't overcrowd the design with too many elements
2. **Use high-quality images**: Ensure your project images are clear and professional
3. **Test on mobile**: Always test the responsive design on different devices
4. **Optimize images**: Compress images for faster loading
5. **Update regularly**: Keep your portfolio current with your latest work

## Support

If you need help customizing your portfolio or have questions, feel free to modify the code or reach out for assistance.

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Happy designing!** 🎨 # radwakayid23.github.io
