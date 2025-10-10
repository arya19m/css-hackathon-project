STRIKE - Coder Army Landing Page 🚀
https://images/strike/strike-img.png

A modern, responsive landing page for STRIKE - an innovative live YouTube course platform by Coder Army that bridges the gap between fundamental computer science concepts and emerging technologies like DSA and Generative AI.

🌟 Table of Contents
Features

Demo

Technologies Used

Project Structure

Quick Start

Customization Guide

Responsive Design

Browser Compatibility

Performance

Contact

License

✨ Features
🎨 Design & User Experience
Modern Dark Theme with golden accent colors

Fully Responsive Design - optimized for all devices

Smooth Scroll Animations and hover effects

CSS-only Mobile Menu with hamburger toggle

Scroll-to-Top Button for easy navigation

Video Background support in hero section

🎯 Interactive Elements
Animated Course Cards with hover effects

Flip-style Mentor Cards revealing detailed information

Pulsing Call-to-Action Buttons

Form Validation with visual feedback

Social Media Integration

📱 Sections Included
Hero Section - Eye-catching landing with video background

About Section - Company mission and vision

Courses Section - Main courses with detailed features

Other Courses - Additional course offerings with hover effects

Mentors Section - Interactive mentor profiles

Contact Section - Contact form and information

Footer - Links and social media

🎥 Demo
https://images/strike/1.jpg

Live Demo: View Project

🛠️ Technologies Used
HTML5 - Semantic markup structure

CSS3 - Modern styling with Flexbox and Grid

Font Awesome 6.4.0 - Icons and social media buttons

Pure CSS Animations - No JavaScript dependencies

CSS Variables - Consistent theming system

Mobile-First Approach - Responsive design principles

📁 Project Structure
text
strike-landing-page/
│
├── index.html                 # Main HTML file
├── style.css                  # Complete styling with animations
├── images/                    # Image assets
│   ├── strike/
│   │   ├── courses/
│   │   │   ├── dsa.png
│   │   │   ├── genai.jpg
│   │   │   └── bundle.jpg
│   │   ├── 1.jpg
│   │   ├── 4.jpg
│   │   ├── strike-img.png
│   │   └── lv_0_20251010145600.mp4
│   ├── Negi-Da/
│   │   ├── 2.jpg
│   │   └── 3.jpg
│   └── tandon-ji/
│       ├── 1.jpg
│       └── 3.jpg
└── README.md                  # Project documentation
🚀 Quick Start
Prerequisites
A modern web browser (Chrome, Firefox, Safari, Edge)

Basic understanding of HTML/CSS (for customization)

Installation & Setup
Download the Project

bash
# Clone or download the project files
# Ensure all files maintain the same folder structure
Open the Website

bash
# Simply open index.html in your web browser
# Or use a local server for better performance:
python -m http.server 8000
# Then visit: http://localhost:8000
Customize Content

Edit index.html to update text content

Modify style.css to change colors and styling

Replace images in the images/ folder with your own

🎨 Customization Guide
Changing Colors
Update CSS variables in :root section of style.css:

css
:root {
    --primary-bg: #0a0a0a;        /* Main background */
    --secondary-bg: #111111;      /* Secondary background */
    --accent: #FFD700;            /* Golden accent color */
    --accent-dark: #B8860B;       /* Darker accent */
    --text-primary: #ffffff;      /* Main text color */
    --text-secondary: #b0b0b0;    /* Secondary text */
    --card-bg: #1a1a1a;          /* Card backgrounds */
    --transition: all 0.3s ease;  /* Default transition */
}
Adding New Courses
Add new course cards in the courses section of index.html:

html
<div class="course-card">
    <div class="course-image">
        <div class="image-overlay"></div>
        <img src="images/your-course-image.jpg" alt="Course Name">
    </div>
    <div class="course-content">
        <h3>Your Course Title</h3>
        <p>Course description...</p>
        <ul class="features">
            <li>Feature 1</li>
            <li>Feature 2</li>
            <li>Feature 3</li>
        </ul>
        <a href="#contact" class="btn course-btn">Enroll Now</a>
    </div>
</div>
Modifying Animations
Adjust animation timing and effects in the CSS:

css
@keyframes yourAnimation {
    0% { transform: scale(1); }
    50% { transform: scale(1.1); }
    100% { transform: scale(1); }
}

.element {
    animation: yourAnimation 2s ease-in-out infinite;
}
📱 Responsive Design
The website is built with a mobile-first approach and includes breakpoints for:

Desktop: 1200px and above

Tablet: 768px - 1199px

Mobile: 576px - 767px

Small Mobile: Below 576px

Key Responsive Features:
Flexible grid layouts

Adjustable font sizes

Optimized image sizes

Touch-friendly navigation

Mobile-optimized forms

🌐 Browser Compatibility
✅ Chrome 90+

✅ Firefox 88+

✅ Safari 14+

✅ Edge 90+

⚡ Performance
Optimizations Included:
Optimized Images - Proper sizing and formats

Efficient CSS - Organized and minified code

CSS Animations - Hardware-accelerated transforms

Mobile-First - Performance-oriented design

Lazy Loading Ready - Structure supports lazy loading

Performance Tips:
Compress images before uploading

Use CDN for Font Awesome icons

Minimize CSS and HTML files for production

Enable GZIP compression on server

🎯 Key Sections
Navigation
Fixed navigation bar with blur effect

CSS-only mobile menu with smooth transitions

Active state indicators

Logo with hover effects

Hero Section
Video background with fallback image

Animated scroll indicator

Gradient text effects

Responsive typography

Courses Display
Grid-based course cards

Hover animations and transformations

Feature lists with interactive icons

Pricing and duration information

Mentor Profiles
Interactive flip cards on hover

Social media links

Achievement lists with star icons

Professional background information

Contact Form
Form validation with error messages

Success message display

Responsive form layout

Contact information with hover effects

🔧 Development
CSS Architecture
The stylesheet is organized into logical sections:

CSS Variables & Theme Setup

Reset & Base Styles

Layout & Container Styles

Typography & Text Styles

Component Styles (Navigation, Hero, Courses, etc.)

Animations & Keyframes

Responsive Design

Code Organization
Semantic HTML5 elements

BEM-inspired CSS naming convention

CSS Custom Properties for theming

Modular component structure

Comprehensive comments

🤝 Contributing
This is a hackathon project. For improvements or customizations:

Fork the project

Create your feature branch

Commit your changes

Push to the branch

Open a Pull Request

📞 Contact & Support
STRIKE - Coder Army
📧 Email: contact@strike.com
📞 Phone: +91-93547-62687
📍 Location: Kotdwar, Uttarakhand-246123

Follow Us
🐦 Twitter: @rohit_negi9

💼 LinkedIn: Rohit Negi

💻 GitHub: Coder Army Notes

📺 YouTube: Coder Army

📄 License
This project is created for educational and hackathon purposes. All rights reserved by STRIKE - Coder Army.

Built with ❤️ for the Hackathon | STRIKE - Empowering Developers with First-Thought Principle Approach

🚀 Getting Started Checklist
Download all project files

Maintain folder structure

Open index.html in browser

Customize content as needed

Test on different devices

Deploy to web server

🔍 Troubleshooting
Images not loading?

Check file paths in HTML

Ensure images are in correct folders

Verify file names match exactly

Styles not applying?

Check CSS file path in HTML

Ensure all CSS files are included

Clear browser cache

Mobile menu not working?

Verify CSS is properly linked

Check for JavaScript conflicts

Test on different browsers

For any issues or questions, please refer to the contact section above.