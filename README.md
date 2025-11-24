# Job Vacancy Portal - Study Abroad Private Limited

A modern, responsive web application for displaying job vacancies at Study Abroad Private Limited. Built with HTML, CSS, and JavaScript, featuring an animated background, interactive job cards, and detailed job descriptions in modal windows.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Interactive Job Cards**: Clickable job cards with hover effects and smooth animations
- **Modal Job Details**: Detailed job descriptions displayed in elegant modal windows
- **Animated Background**: Floating icons and gradient animations for visual appeal
- **Modern UI/UX**: Clean, professional design with smooth transitions and effects
- **Highlighted Key Attributes**: Prominent display of important job requirements for Team Leader position
- **Accessibility**: Keyboard navigation support (ESC to close modals) and semantic HTML structure

## 📋 Available Positions

1. **Inquiry Handling Specialist**
   - Customer service and communication focused role
   - First point of contact for prospective students
   - Application deadline: 5th December 2025

2. **Team Leader – Inquiry Management**
   - Leadership and management position
   - Key attributes highlighted:
     - Flexible to work extra hours based on operational needs
     - Strong ability to perform effectively in a fast-paced and high-pressure environment
     - Demonstrated capability to meet and exceed performance targets
   - Application deadline: 5th December 2025

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installation required

### Installation

1. Clone or download this repository
2. Ensure all files are in the same directory:
   - `index.html`
   - `style.css`
   - `logo.png`
   - Other image assets (if any)

### Running the Application

1. Open `index.html` in your web browser
2. You can either:
   - Double-click the `index.html` file
   - Right-click and select "Open with" your preferred browser
   - Use a local server (recommended for development):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```
3. Navigate to `http://localhost:8000` in your browser

## 📁 Project Structure

```
Job Vacancy/
│
├── index.html              # Main HTML file
├── style.css               # Stylesheet with all CSS rules
├── logo.png                # Company logo
├── README.md               # This file
│
└── [Other image assets]
```

## 🎨 Customization

### Changing the Logo

Replace `logo.png` with your own logo file. The logo is set to display at 350px width on desktop. Adjust in `style.css`:

```css
.logo {
    max-width: 350px;  /* Change this value */
}
```

### Modifying Job Listings

Edit the job details in `index.html`:
- Job cards are in the `.jobs-grid` section (lines ~37-86)
- Detailed job descriptions are in hidden divs (lines ~99-261)
- Update job titles, descriptions, requirements, and contact information

### Styling

All styles are in `style.css`. Key sections:
- `.header` - Header styling
- `.job-card` - Job card appearance
- `.highlight-box` - Highlighted key attributes box
- `.modal` - Modal window styling
- Media queries for responsive design

### Adding New Jobs

1. Copy an existing job card in the `.jobs-grid` section
2. Copy the corresponding job details template (hidden div with id `jobX-details`)
3. Update the `onclick` attribute and ID to match (e.g., `job3`)
4. Update all content for the new position

## 🌐 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- Desktop: Full layout with grid (1200px max-width)
- Tablet: 768px and below - Adjusted spacing and font sizes
- Mobile: 480px and below - Single column layout, optimized touch targets

## 🎯 Key Sections

### Header
- Company logo
- Page title: "Career Opportunities"
- Company name

### Job Cards
- Visual header with background image
- Job title and location
- Brief description
- Tags for job categories
- Application deadline
- "View Details" link

### Job Details Modal
- Full job description
- About Us section
- Role Overview (for Inquiry Handling Specialist)
- Responsibilities
- Requirements (with highlighted key attributes for Team Leader)
- Benefits
- How to Apply
- Equal Opportunity statement

## 📧 Contact Information

For applications, email: **info@studyabroad.lk**

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients, animations, and transitions
- **JavaScript**: Modal functionality and interactivity
- **Unsplash API**: Background images for job cards

## 📝 Notes

- The website uses external images from Unsplash for job card backgrounds
- All animations are CSS-based for optimal performance
- No external libraries or frameworks required
- Fully self-contained - no build process needed

## 🔄 Recent Updates

- Increased logo size for better visibility
- Removed company address from header and footer
- Added prominent highlighting for key Team Leader attributes
- Enhanced job card visibility with stronger borders and shadows
- Improved responsive design for mobile devices

## 📄 License

This project is for Study Abroad Private Limited. All rights reserved.

## 👤 Author

Created for Study Abroad Private Limited

---

**Note**: This is a static website. No backend or database is required. Simply open `index.html` in a browser to view.

