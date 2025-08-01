# DarkOps Landing Page

A complete web application for darkops.ai featuring a terminal interface, main landing page, and demo page with working email capture.

## Files

- `index.html` - Terminal interface with command recognition
- `main.html` - Main landing page with hero section and email capture
- `demo.html` - Demo placeholder page with email capture
- `README.md` - This documentation file

## Features

### Terminal Interface (`index.html`)
- Authentic terminal design with green-on-black color scheme
- ASCII art logo
- Command recognition system:
  - `context`, `intelligence`, `operational-context` → redirects to main page
  - `help` → "ACCESS DENIED: Standard protocols insufficient" 
  - `admin`, `login` → "ACCESS DENIED: Administrative access requires operational understanding"
  - `darkops` → "ACCESS DENIED: Direct naming conventions flagged"
  - Other commands → "COMMAND NOT RECOGNIZED: Try again"
- Blinking cursor animation
- Mobile responsive design
- Hint system for user guidance

### Main Landing Page (`main.html`)
- Professional dark theme with gradient backgrounds
- Hero section with:
  - "DarkOps" header
  - "Operational Intelligence OS" subheader  
  - "The first AI system that can analyze its own decision-making process" description
  - "View Demo" CTA button
  - "Built in 3 months by former enterprise ops specialist" attribution
- Working email capture form with validation
- Responsive design for all screen sizes

### Demo Page (`demo.html`)
- "Demo available soon" message
- Status indicator with animation
- Email capture form identical to main page
- Navigation back to main page
- Consistent branding and styling

## Email Capture
- Uses Formspree for reliable email collection
- Form endpoint: `https://formspree.io/f/mwpqqzao`
- Includes both required email and optional name fields
- Client-side validation for email format
- Success/error message handling
- Graceful fallback for network issues

## Deployment
Simply upload all HTML files to any web host. No server-side processing required.

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on all screen sizes

## Customization
To customize the Formspree endpoint:
1. Sign up at formspree.io
2. Create a new form
3. Replace `mwpqqzao` in the form action URLs with your form ID

## Technical Details
- Pure HTML/CSS/JavaScript (no dependencies)
- Semantic HTML structure
- CSS Grid and Flexbox for layouts
- Smooth animations and transitions
- Optimized for performance and SEO