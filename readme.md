# Hesham Rashed - AI Engineer Portfolio

A modern, professional portfolio website showcasing AI engineering projects, experience, and skills.

## 🚀 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern Aesthetics**: Tech-forward design with animated elements and smooth transitions
- **Project Showcase**: Detailed project cards with metrics and technologies
- **Interactive Navigation**: Smooth scrolling with active section highlighting
- **Performance Optimized**: Fast loading with efficient animations

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🎨 Design Features

- Custom color palette with cyan accent (#00D9FF)
- JetBrains Mono font for technical elements
- DM Sans for body text
- Animated grid background
- Gradient text effects
- Hover animations and transitions
- Intersection Observer for scroll animations

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts

## 📦 Deployment to GitHub Pages

### Option 1: Using GitHub Web Interface (Easiest)

1. **Create a new repository on GitHub**
   - Go to https://github.com/new
   - Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Make it public
   - Don't initialize with README (we already have one)

2. **Upload your files**
   - Click "uploading an existing file"
   - Drag and drop all three files: `index.html`, `styles.css`, `script.js`, and `README.md`
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

4. **Access your site**
   - Your site will be live at: `https://your-username.github.io`
   - It may take a few minutes to deploy

### Option 2: Using Git Command Line

1. **Initialize and push to GitHub**
```bash
# Navigate to your portfolio folder
cd /path/to/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio deployment"

# Add your GitHub repository as remote
git remote add origin https://github.com/your-username/your-username.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

2. **Enable GitHub Pages**
   - Follow step 3 from Option 1 above

## 🎯 Customization Guide

### Update Personal Information

1. **Contact Details** (in `index.html`):
   - Search for email addresses and update them
   - Update LinkedIn URL
   - Update phone number

2. **Content**:
   - Update project descriptions in the Projects section
   - Add/remove timeline items in Experience section
   - Modify skills in the Skills section

3. **Colors** (in `styles.css`):
   - Change `--accent` variable to your preferred color
   - Adjust `--primary` and `--secondary` for background colors

4. **Profile Image**:
   - Replace the placeholder in the About section with your actual photo
   - Update the `.image-placeholder` section in `index.html`

### Adding New Projects

Add a new `.project-card` div in the Projects section:

```html
<div class="project-card">
    <div class="project-header">
        <span class="project-tag">Category</span>
        <h3 class="project-title">Project Name</h3>
    </div>
    <p class="project-description">
        Your project description here...
    </p>
    <div class="project-metrics">
        <div class="metric">
            <span class="metric-value">Value</span>
            <span class="metric-label">Label</span>
        </div>
    </div>
    <div class="project-tech">
        <span class="tech-tag">Tech1</span>
        <span class="tech-tag">Tech2</span>
    </div>
</div>
```

## 🔧 Development

To test locally:

1. Open `index.html` in your browser
2. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then open http://localhost:8000
   ```

## 📝 License

Feel free to use this template for your own portfolio. Attribution appreciated but not required.

## 💡 Tips

- Keep project descriptions concise and metric-focused
- Update your portfolio regularly with new projects
- Add a custom domain for a more professional look (optional)
- Optimize images before adding them to keep the site fast
- Test on multiple devices and browsers

## 🐛 Troubleshooting

**Site not loading?**
- Check that your repository is named correctly: `username.github.io`
- Ensure the `index.html` file is in the root directory
- Wait a few minutes after enabling GitHub Pages

**Styling not working?**
- Verify that `styles.css` and `script.js` are in the same directory as `index.html`
- Check browser console for any errors

## 📧 Contact

For questions or suggestions about this template, feel free to reach out!

---

Built with passion for AI and clean design 🚀