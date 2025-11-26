# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, designed to be hosted on GitHub Pages.

## Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive**: Fully responsive layout that works on all devices
- **Fast Loading**: Lightweight and optimized for performance
- **Easy to Customize**: Well-organized code structure
- **GitHub Pages Ready**: Configured for easy deployment

## Setup Instructions

### 1. Create a New GitHub Repository

1. Go to GitHub and create a new repository (e.g., `mario-hernandez-portfolio` or `portfolio`)
2. **Important**: Make sure the repository name matches what you want in your URL (e.g., `username.github.io` for a user site, or `repository-name` for a project site)

### 2. Upload Files

You can upload files using one of these methods:

**Option A: Using Git (Recommended)**
```bash
cd Code/persona-website
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

**Option B: Using GitHub Web Interface**
1. Go to your repository on GitHub
2. Click "Add file" → "Upload files"
3. Drag and drop all files from this directory
4. Commit the changes

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - **Branch: main** (or master)
   - **Folder: / (root)**
5. Click **Save**
6. Your site will be available at: `https://YOUR-USERNAME.github.io/REPO-NAME/`

### 4. Update GitHub Links

Since you mentioned creating a new GitHub account, you'll need to update the GitHub links:

1. Open `index.html`
2. Find all instances of `github.com/pollyjuice74` and replace with your new username
3. Or use the JavaScript function in `script.js`:
   - Uncomment the `updateGitHubLink()` call at the bottom
   - Replace `'your-new-username'` with your actual username

### 5. Add Your Resume PDF

1. Place your resume PDF file in this directory
2. Name it `resume.pdf`
3. The download link in the resume section will automatically work

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --primary-dark: #1e40af;
    /* ... */
}
```

### Content
- Edit `index.html` to update any text, links, or sections
- All content from your resume is already included

### Contact Information
Update contact details in:
- The hero section
- The contact section
- The resume section

## File Structure

```
persona-website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
├── resume.pdf          # Your resume (add this)
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- The website is fully static and doesn't require any build process
- All assets are self-contained (no external dependencies except Google Fonts)
- The site is optimized for GitHub Pages hosting
- Print styles are included for the resume section

## License

This portfolio template is free to use and modify for personal or commercial projects.

