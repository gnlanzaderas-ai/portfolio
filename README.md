# Maryrose Portfolio

A modern, responsive personal portfolio website featuring a clean white theme with pink accents.

## Features

- **Home Page**: Introduction with call-to-action buttons
- **About Page**: Personal information, skills, and journey
- **Contact Info Page**: Contact details and message form
- **Photos Page**: Portfolio gallery with hover effects

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla JS)
- Responsive Design

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content, images, and contact information to match your needs

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #e91e63;  /* Main accent color */
    --secondary-color: #c2185b; /* Secondary accent color */
    /* ... other variables */
}
```

### Adding Your Photos
Replace the placeholder images in `photos.html` with your own images. You can also update the profile image in `index.html`.

### Updating Contact Information
Edit the contact details in `contact.html` to include your actual email, phone, and social media links.

## Deploying to GitHub Pages

Follow these steps to publish your portfolio on GitHub:

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up.

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - This special naming format enables GitHub Pages automatically
   - Alternatively, you can use any repository name
4. Make it **Public** (required for free GitHub Pages)
5. **Don't** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### Step 3: Initialize Git in Your Project
Open your terminal/command prompt in the project folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Make your first commit
git commit -m "Initial commit: Portfolio website"
```

### Step 4: Connect to GitHub
```bash
# Add your GitHub repository as remote (replace with your repository URL)
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

### Step 5: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select **main** branch
5. Select **/ (root)** folder
6. Click **Save**

### Step 6: Access Your Live Site
Your portfolio will be available at:
- `https://yourusername.github.io` (if you named it `yourusername.github.io`)
- OR `https://yourusername.github.io/repository-name` (if you used a different name)

**Note:** It may take a few minutes for your site to go live after enabling GitHub Pages.

## Updating Your Portfolio

Whenever you make changes:

```bash
# Add your changes
git add .

# Commit with a message
git commit -m "Description of your changes"

# Push to GitHub
git push
```

Your changes will automatically update on GitHub Pages within a few minutes.

## Tips

- **Custom Domain**: You can add a custom domain in the GitHub Pages settings
- **HTTPS**: GitHub Pages automatically provides SSL certificates
- **Free Hosting**: GitHub Pages is free for public repositories
- **Version Control**: All your changes are tracked with Git

## Browser Support

This portfolio works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your own portfolio!

