# Maharashtra Industrial Services Website

A professional website for Maharashtra Industrial Services, featuring Laundry and Catering services.

## Features

- Modern, responsive design
- Mobile-friendly navigation
- Separate pages for Laundry and Catering services
- Contact form
- Smooth scrolling animations
- Clean and professional UI

## GitHub Pages Setup

To host this website on GitHub Pages:

1. **Push the code to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Maharashtra Industrial Services website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/mahaindservices.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

3. **Access your website:**
   - Your website will be available at: `https://YOUR_USERNAME.github.io/mahaindservices/`
   - It may take a few minutes for the site to be deployed

## Project Structure

```
mahaindservices/
├── index.html          # Homepage
├── laundry.html        # Laundry services page
├── catering.html       # Catering services page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── MIL.pdf             # Laundry service profile
├── MIS.pdf             # Catering service profile
└── README.md           # This file
```

## Customization

### Update Contact Information

Edit the contact section in `index.html` (around line 90) to update:
- Email address
- Phone number
- Physical address

### Update Service Details

- **Laundry Services**: Edit `laundry.html` to add specific details from MIL.pdf
- **Catering Services**: Edit `catering.html` to add specific details from MIS.pdf

### Colors and Styling

Edit `styles.css` to customize colors:
- Primary color: `--primary-color` (currently blue: #2563eb)
- Secondary color: `--secondary-color` (currently green: #10b981)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2024 Maharashtra Industrial Services. All rights reserved.
