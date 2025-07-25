# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations, interactive elements, and mobile-first responsive layout.

## 🚀 Features

- **Modern Design**: Clean and professional layout with gradient backgrounds and glass-morphism effects
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: CSS animations and JavaScript-powered scroll effects
- **Interactive Elements**: Hover effects, form validation, and dynamic content
- **Mobile Menu**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Seamless navigation between sections
- **Loading Animations**: Progressive reveal animations on scroll
- **Notification System**: Toast notifications for user feedback

## 📁 Project Structure

```
portfolio-site/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal information and statistics
3. **Skills**: Technical skills organized by category
4. **Projects**: Showcase of featured projects
5. **Resume**: Work experience and education timeline
6. **Contact**: Contact information and contact form

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Icons for UI elements
- **Google Fonts**: Inter font family for typography

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your personal information

### Local Development

1. Navigate to the project directory
2. Open `index.html` in your browser
3. For live development, you can use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

## ✏️ Customization

### Personal Information

1. **Update Hero Section** in `index.html`:
   - Change "Your Name" to your actual name
   - Update the subtitle and description
   - Modify the call-to-action buttons

2. **Update About Section**:
   - Replace the placeholder text with your personal information
   - Update statistics (years of experience, projects, clients)

3. **Update Skills Section**:
   - Add/remove skills based on your expertise
   - Change icons using Font Awesome classes

4. **Update Projects Section**:
   - Replace project cards with your actual projects
   - Update project descriptions, technologies, and links

5. **Update Resume Section**:
   - Add your work experience and education
   - Update the timeline with your actual dates

6. **Update Contact Section**:
   - Replace contact information with your actual details
   - Update social media links

### Styling Customization

1. **Colors**: Modify CSS custom properties in `styles.css`
2. **Fonts**: Change the Google Fonts import in `index.html`
3. **Animations**: Adjust animation durations and effects in `styles.css`

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add navigation link in the navbar
4. Add any JavaScript functionality in `script.js`

## 🌐 Deployment

### GitHub Pages

1. **Create a GitHub repository**
2. **Upload** your project files
3. **Go to Settings** → Pages
4. **Select source** as "Deploy from a branch"
5. **Choose branch** (usually `main` or `master`)
6. **Save** and wait for deployment

### Netlify

1. **Sign up** for Netlify
2. **Drag and drop** your project folder to Netlify
3. **Wait** for automatic deployment
4. **Customize** your domain (optional)

### Vercel

1. **Sign up** for Vercel
2. **Import** your GitHub repository
3. **Deploy** with default settings
4. **Customize** your domain (optional)

### Other Hosting Services

You can deploy to any static hosting service:
- AWS S3 + CloudFront
- Firebase Hosting
- Surge.sh
- GitLab Pages

## 📝 Form Configuration

The contact form currently shows a success message. To make it functional:

1. **Backend Integration**: Connect to a backend service (Formspree, Netlify Forms, etc.)
2. **Email Service**: Use services like EmailJS or a custom backend
3. **API Integration**: Modify the form submission in `script.js`

### Example with Formspree

1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Update the form action in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+ (with some limitations)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have any questions or need help with customization, please open an issue in the repository.

## 🎯 Future Enhancements

- [ ] Dark mode toggle
- [ ] Blog section
- [ ] Portfolio gallery
- [ ] Testimonials section
- [ ] Multi-language support
- [ ] PWA features
- [ ] SEO optimization
- [ ] Performance optimization

---

**Happy Coding! 🚀** 