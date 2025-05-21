# Tiktionary GitHub Pages Site

A modern and professional GitHub Pages site for the Tiktionary project - an AI-powered tool that lets users chat with their saved TikToks.

## Overview

This repository contains a complete GitHub Pages site for the Tiktionary project, including:

- Modern, responsive design with black and white theme and blue accents
- Comprehensive information about the project
- Terms of Service and Privacy Policy pages
- Technical documentation
- Contact form and FAQ

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional interface with smooth animations
- **Complete Documentation**: Detailed technical information for developers
- **Legal Compliance**: Includes Terms of Service and Privacy Policy

## Getting Started

### Option 1: GitHub Pages Deployment

1. Create a new repository on GitHub named `tiktionary` or `username.github.io/tiktionary`
2. Upload all files from this zip to your repository
3. Go to repository Settings > Pages
4. Set the source to the main branch and the folder to root (/)
5. Your site will be published at `https://username.github.io/tiktionary`

### Option 2: Custom Domain Deployment

1. Follow steps 1-3 from Option 1
2. In repository Settings > Pages, enter your custom domain (e.g., tiktionary.app)
3. Update your domain's DNS settings to point to GitHub Pages
4. Your site will be published at your custom domain

## Customization

### Changing Colors

The color scheme can be modified in `assets/css/styles.css` by changing the CSS variables in the `:root` selector.

### Updating Content

- Edit the HTML files directly to update page content
- Replace `assets/images/logo.png` to update the logo
- Modify `assets/js/main.js` for JavaScript functionality

## Integration with Your App

To integrate this site with your Python-based RAG-style TikTok LLM application:

1. Add links to your application in the navigation or CTA buttons
2. Update the documentation page with specific implementation details
3. Consider adding an API documentation section for developers

## File Structure

```
tiktionary/
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── images/
│   │   └── logo.png
│   └── js/
│       └── main.js
├── index.html
├── about.html
├── faq.html
├── contact.html
├── documentation.html
├── terms.html
├── privacy.html
└── README.md
```

## License

This site template is provided for your use with the Tiktionary project. Please update the license information as needed for your specific project requirements.

## Contact

For questions or support, please visit the [GitHub repository](https://github.com/Lambourne2/tiktionary).
