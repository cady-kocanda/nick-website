# Nick's Portfolio Website

A modern, sleek portfolio website for a professional fitness trainer and soccer coach.

## Features

- **Modern Design**: Clean, professional interface with smooth animations
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Enhanced navigation with smooth scroll behavior
- **Interactive Elements**: Hover effects, animations, and dynamic interactions
- **Sections**:
  - Hero section with call-to-action buttons
  - About section with statistics
  - Work experience timeline
  - Accomplishments showcase
  - Contact form

## Getting Started

### Prerequisites

No special prerequisites needed! This is a static website that runs entirely in the browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use.

### Local Development Server (Optional)

For a better development experience, you can use a local server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Customization

### Updating Content

1. **Personal Information**: Edit the content in `index.html`
   - Update the hero section with your name/title
   - Modify the about section with your story
   - Update work experience in the timeline
   - Add your accomplishments
   - Update contact information

2. **Colors**: Customize colors in `styles.css` by modifying the CSS variables in the `:root` selector:
   ```css
   :root {
       --primary-color: #2563eb;
       --secondary-color: #10b981;
       /* ... other colors */
   }
   ```

3. **Fonts**: The website uses Google Fonts (Inter). To change fonts, update the font link in `index.html` and the `font-family` in `styles.css`.

### Adding Your Own Content

- Replace placeholder text with your actual experience and accomplishments
- Update contact information (email, phone, location)
- Add your social media links in the footer
- Customize the statistics in the about section
- Modify the timeline items with your actual work history

## File Structure

```
nick-website/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

Consider adding:
- Image gallery for training sessions or events
- Testimonials section
- Blog section
- Online booking system
- Integration with email service for contact form
- Analytics tracking

## License

This project is open source and available for personal use.

## Contact

For questions or suggestions, feel free to reach out!

