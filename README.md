# Personal Portfolio Website

A clean, modern, and responsive single-page portfolio website hosted on GitHub Pages.

## Live Site

Visit the live site at: `https://divyakrishnaa.github.io`

## Features

- Modern, clean design with smooth scrolling
- Fully responsive (mobile, tablet, desktop)
- Sections for About, Skills, Projects, Experience, and Contact
- Easy to customize and maintain
- No build process required - just HTML and CSS

## How to Customize

### 1. Update Personal Information

Edit `index.html` to add your personal information:

**Hero Section (lines 26-33)**
- Change your name, title, and description
- Update the subtitle with your role/expertise

**About Section (lines 40-42)**
- Write about yourself and your background
- Add your interests and goals

**Contact Links (lines 164-167)**
- Replace `your.email@example.com` with your actual email
- Update LinkedIn, Twitter, and other social media links

### 2. Add Your Skills

Edit the Skills section (lines 50-79):
- Modify the three categories: Frontend, Backend, Tools & Others
- Add or remove skills based on your expertise
- You can add more categories by copying the `.skill-category` div

### 3. Add Your Projects

Edit the Projects section (lines 88-119):
- Replace the placeholder projects with your actual projects
- For each project, update:
  - Project name
  - Description
  - Links to live demo and GitHub repository
- Add more projects by copying a `.project-card` div

### 4. Add Your Experience

Edit the Experience/Timeline section (lines 130-153):
- Update with your work experience and education
- For each item, include:
  - Date range
  - Job title or degree
  - Company or university name
  - Description of responsibilities or achievements
- Add more items by copying a `.timeline-item` div

### 5. Customize Colors

Edit `style.css` to change the color scheme (lines 7-14):

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #1e40af;    /* Darker shade */
    --text-color: #1f2937;         /* Main text color */
    --text-light: #6b7280;         /* Secondary text */
}
```

## How to Deploy

### Option 1: GitHub Pages (Recommended)

1. Push your changes to GitHub:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push
   ```

2. GitHub Pages will automatically publish your site to `https://yourusername.github.io`

### Option 2: Local Testing

Simply open `index.html` in your web browser to preview locally before pushing to GitHub.

## File Structure

```
.
├── index.html          # Main portfolio page
├── style.css          # Stylesheet
└── README.md          # This file
```

## Optional Enhancements

Once you're comfortable with the basics, consider adding:

- A profile photo in the hero section
- Project screenshots or images
- A dark mode toggle
- Contact form functionality
- Google Analytics tracking
- Custom domain name

## Old Jekyll Files

You can safely delete these Jekyll-related files if you want to clean up:
- `_config.yml`
- `_layouts/` directory
- `_posts/` directory
- `about/` directory
- `blog/` directory
- `css/main.css`

The new portfolio doesn't need them!

## Support

If you need help or have questions, feel free to open an issue on GitHub.

## License

Free to use and modify for your personal portfolio.
