# Deployment Guide for Ninja Motion Therapies Website

## Manual GitHub Upload Instructions

Since there are authentication issues with the automated git push, here are the manual steps to upload the website to GitHub:

### Option 1: Using GitHub Web Interface

1. **Download the Files**
   - Download the `ninjatherapy.zip` file from the workspace
   - Extract it to your local machine

2. **Upload to GitHub**
   - Go to https://github.com/taifz123/ninjatherapy
   - Click on "Add file" → "Upload files"
   - Drag and drop all the files from the extracted folder
   - Make sure to upload:
     - `index.html`
     - `about.html`
     - `services.html`
     - `pricing.html`
     - `conditions.html`
     - `faq.html`
     - `contact.html`
     - `README.md`
     - `css/` folder (with `styles.css`)
     - `js/` folder (with `main.js`)
     - `images/` folder (with `logo.png` and `yuhan-photo.jpg`)

3. **Commit Changes**
   - Add a commit message like "Initial commit: Complete Ninja Motion Therapies website"
   - Click "Commit changes"

### Option 2: Using Git Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/taifz123/ninjatherapy.git
   cd ninjatherapy
   ```

2. **Copy Files**
   - Copy all website files into the cloned repository folder
   - Make sure to maintain the folder structure

3. **Commit and Push**
   ```bash
   git add .
   git commit -m "Initial commit: Complete Ninja Motion Therapies website"
   git push origin main
   ```

## Files Included

### HTML Pages
- `index.html` - Homepage with hero section, services overview, testimonials
- `about.html` - About Yuhan and her qualifications
- `services.html` - Detailed services offered
- `pricing.html` - Pricing information
- `conditions.html` - Conditions treated
- `faq.html` - Frequently asked questions
- `contact.html` - Contact information and booking

### Assets
- `css/styles.css` - Complete styling with responsive design
- `js/main.js` - Interactive features and functionality
- `images/logo.png` - Ninja Motion Therapies logo
- `images/yuhan-photo.jpg` - Professional photo of Yuhan
- `README.md` - Project documentation

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Modern UI**: Clean, professional design based on reference websites
- **Interactive Elements**: FAQ accordion, testimonial slider, smooth scrolling
- **SEO Optimized**: Meta tags and structured data
- **Booking Integration**: Links to RecoveryZN booking platform
- **Contact Information**: Updated address, phone, and email

## Next Steps After Upload

1. **Enable GitHub Pages** (if you want to host directly from GitHub):
   - Go to repository Settings
   - Scroll down to "GitHub Pages"
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Save and wait for deployment

2. **Custom Domain** (optional):
   - Add custom domain in GitHub Pages settings
   - Update DNS records as needed

3. **Test the Website**:
   - Visit the GitHub Pages URL
   - Test all links and functionality
   - Check mobile responsiveness

## Support

If you encounter any issues during deployment, please let me know and I can help troubleshoot.