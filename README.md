# Hafiz Muhammad Arslan - Portfolio Website

A modern, responsive portfolio website showcasing my experience as a Data Scientist specializing in Enterprise Machine Learning, Generative AI, and Agentic solutions.

## Features

- Fully responsive design (mobile, tablet, desktop)
- Smooth scrolling navigation
- Animated sections with scroll-triggered effects
- Professional timeline for work experience
- Skills showcase with categorized technical competencies
- Project highlights
- Contact information

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- Vanilla JavaScript
- Font Awesome icons

## Deployment to GitHub Pages

Follow these steps to deploy your portfolio to GitHub Pages:

### Step 1: Initialize Git Repository

Open terminal in your project folder and run:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
```

### Step 2: Create GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the '+' icon in the top right corner
3. Select 'New repository'
4. Name your repository (e.g., `portfolio` or `your-username.github.io`)
5. Keep it public
6. **DO NOT** initialize with README, .gitignore, or license (we already have files)
7. Click 'Create repository'

### Step 3: Connect Local Repository to GitHub

Copy the commands from GitHub's "...or push an existing repository from the command line" section:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPO-NAME` with your actual GitHub username and repository name.

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on 'Settings' tab
3. Scroll down to 'Pages' in the left sidebar
4. Under 'Source', select 'Deploy from a branch'
5. Under 'Branch', select 'main' and folder '/ (root)'
6. Click 'Save'

### Step 5: Access Your Website

After a few minutes, your website will be live at:
- If repository name is `your-username.github.io`: `https://your-username.github.io`
- If repository name is anything else: `https://your-username.github.io/repository-name`

GitHub will show you the URL in the Pages settings.

## Alternative Deployment Options

### Using GitHub Desktop (GUI Method)

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Open GitHub Desktop
3. Click 'File' > 'Add local repository'
4. Select your portfolio folder
5. Click 'Publish repository' button
6. Choose repository name and description
7. Uncheck 'Keep this code private' if you want it public
8. Click 'Publish repository'
9. Follow Step 4 above to enable GitHub Pages

### Using VS Code

1. Install the 'GitHub Pull Requests and Issues' extension
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
3. Type 'Git: Initialize Repository' and select your folder
4. Press `Ctrl+Shift+P` again and type 'Git: Publish to GitHub'
5. Follow the prompts to create and publish your repository
6. Follow Step 4 above to enable GitHub Pages

## Updating Your Portfolio

Whenever you make changes to your portfolio:

```bash
git add .
git commit -m "Description of changes"
git push
```

GitHub Pages will automatically update your website within a few minutes.

## Customization

### Changing Colors

Edit the CSS variables in `styles.css` (lines 10-21):

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... modify other colors as needed */
}
```

### Updating Content

Edit the `index.html` file to update:
- Personal information
- Work experience
- Projects
- Skills
- Education
- Contact details

### Modifying Animations

Edit `script.js` to adjust:
- Animation timings
- Scroll effects
- Navigation behavior

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Local Development

To view the website locally, simply open `index.html` in your web browser. For a better development experience with live reload:

1. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Right-click on `index.html`
3. Select 'Open with Live Server'

Or use Python's built-in server:

```bash
# Python 3
python -m http.server 8000

# Then open browser to http://localhost:8000
```

## Troubleshooting

### Website not showing up after deployment
- Wait 5-10 minutes for GitHub Pages to build
- Check that GitHub Pages is enabled in repository settings
- Ensure the main branch has your files
- Clear browser cache and try again

### Styling looks broken
- Check that `styles.css` and `script.js` are in the same folder as `index.html`
- Check browser console for any errors (F12)

### Images not loading
- Ensure image paths are relative (not absolute paths from your computer)
- Check that images are committed to the repository

## Contact

- Email: hfz.arslan@gmail.com
- LinkedIn: [linkedin.com/in/hfzarslan](https://www.linkedin.com/in/hfzarslan)
- Phone: +92 347 4313382

## License

This project is open source and available for personal use.
