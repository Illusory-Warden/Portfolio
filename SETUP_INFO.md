# Rushi Daulatkar - Portfolio

A minimalist, professional portfolio showcasing my projects, skills, and achievements in Computer Science and Software Development.

## About

This portfolio features a clean, no-nonsense design philosophy focused on content over decoration. Built with pure HTML, CSS, and vanilla JavaScript - no frameworks, no bloat, just efficient code that works.

**Philosophy:** _"A real portfolio isn't defined by fancy CSS or beautiful decorations. A real portfolio is one that showcases great projects, real solutions, and meaningful impact. The work speaks for itself."_

## Project Structure

```
Portfolio/
├── index.html                          # Main portfolio homepage
├── project-pivate-cloud.html           # Pi-Vate Cloud project page
├── project-aroguard.html               # AroGuard project page
├── project-browser-automation.html     # Browser Automation 3.0 project page
├── project-template.html               # Template for new projects
├── README.md                           # This file
├── resume/
│   └── Rushi_Daulatkar_Resume.pdf     # Downloadable resume
└── images/
    └── (project screenshots)           # Project images and screenshots
```

## Features

- **Minimal Design**: Clean, bordered boxes with subtle scroll animations
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile
- **Fast Loading**: No external dependencies, pure vanilla HTML/CSS/JS
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Accessibility**: Keyboard navigation and screen reader friendly
- **Easy Maintenance**: Simple structure, easy to update

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with animations
- **JavaScript**: Vanilla JS for interactions
- **No Frameworks**: Pure web technologies

## Pages Overview

### index.html

Main portfolio page featuring:

- Professional summary
- Education background
- Technical skills
- Work experience
- Featured projects
- Publications & achievements
- Certifications
- Contact information

### Project Pages

Each project page includes:

- Project overview with duration and tech stack
- Detailed description
- Key features and achievements
- Technical architecture breakdown
- Image placeholders for screenshots
- Technical challenges and solutions
- Real-world impact
- Technologies used
- Links to live demos and repositories

## ➕ Adding a New Project

### Step 1: Create Project Page

1. Copy `project-template.html` and rename it:

   ```bash
   cp project-template.html project-your-project-name.html
   ```

2. Replace all placeholders (marked with `[BRACKETS]`):

   - `[PROJECT NAME]` - Your project title
   - `[Month Year – Month Year]` - Project duration
   - `[List all technologies used]` - Tech stack
   - `[Project category/domain]` - Category
   - Fill in all description sections
   - Add features, challenges, and solutions

3. Customize sections:
   - Keep relevant sections
   - Comment out or delete optional sections you don't need
   - Adjust number of subsections based on your project

### Step 2: Add Images

1. Take screenshots of your project
2. Save them in the `images/` folder with descriptive names:

   ```
   images/your-project-main.jpg
   images/your-project-feature1.jpg
   images/your-project-architecture.jpg
   ```

3. Uncomment image tags in your project HTML file:

   ```html
   <!-- Change this: -->
   <div class="image-placeholder">...</div>

   <!-- To this: -->
   <img src="images/your-project-main.jpg" alt="Description" />
   <p class="image-caption">Caption text</p>
   ```

### Step 3: Update index.html

Add your project to the Projects section:

```html
<div class="subsection">
  <strong><a href="project-your-project-name.html">Your Project Name</a></strong
  ><br />
  <em>Tech Stack | Month Year – Month Year</em>
  <ul>
    <li>Key feature or achievement 1</li>
    <li>Key feature or achievement 2</li>
    <li>Key feature or achievement 3</li>
  </ul>
</div>
```

### Step 4: Test and Deploy

1. Open your project page in a browser
2. Check all links work correctly
3. Verify images load properly
4. Test responsiveness on mobile
5. Commit and push to GitHub

## Image Guidelines

### Recommended Image Sizes:

- **Full-width screenshots**: 1920x1080px
- **Interface screenshots**: 1200x800px
- **Mobile screenshots**: 750x1334px

### Best Practices:

- Use high-quality screenshots
- Blur sensitive information (IPs, emails, personal data)
- Add descriptive alt text for accessibility
- Optimize images for web (compress to reduce file size)
- Use consistent image formats (JPG for photos, PNG for UI)

### Tools for Screenshots:

- **Windows**: Snipping Tool, Win + Shift + S
- **macOS**: Cmd + Shift + 4
- **Linux**: Flameshot, GNOME Screenshot
- **Browser**: DevTools device toolbar for responsive views

## Design Philosophy

This portfolio follows a **minimalist, content-first approach**:

### Design Principles:

1. **Clarity over decoration**: Simple borders, clean typography
2. **Content is king**: Projects and achievements take center stage
3. **Subtle animations**: Gentle scroll animations for polish
4. **Consistent styling**: Uniform design across all pages
5. **Fast and efficient**: No bloat, pure HTML/CSS/JS

### Color Scheme:

- **Background**: White (#ffffff)
- **Text**: Black (#000000)
- **Borders**: Light gray (#cccccc)
- **Accents**: Dark gray (#dddddd)
- **Links**: Blue (#0066cc)
- **Subsections**: Off-white (#fafafa)

### Typography:

- **Font**: Arial, sans-serif (universal, readable)
- **H1**: 28px
- **H2**: 22px
- **H3**: 18px
- **Body**: 16px, line-height 1.6

## 🔧 Customization

### Changing Colors:

Edit the CSS variables in each HTML file's `<style>` section:

```css
body {
  background: #ffffff; /* Page background */
  color: #000000; /* Text color */
}

.container {
  border: 1px solid #cccccc; /* Border color */
  background: #ffffff; /* Box background */
}
```

### Adjusting Animations:

Modify the transition timing in `.container`:

```css
.container {
  transition: opacity 0.6s ease, transform 0.6s ease;
}
```

### Changing Layout Width:

Adjust the max-width in `body`:

```css
body {
  max-width: 900px; /* Change to your preferred width */
}
```

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints at:

- **Desktop**: > 600px
- **Mobile**: ≤ 600px

Mobile optimizations include:

- Reduced padding
- Stacked contact buttons
- Adjusted font sizes
- Touch-friendly button sizes

## Deployment

### GitHub Pages (Recommended):

1. Create a new repository named `your-username.github.io`
2. Push your portfolio files:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```
3. Go to Settings > Pages
4. Select "main" branch and "/" root
5. Your portfolio will be live at `https://your-username.github.io`

### Alternative Hosting Options:

- **Netlify**: Drag and drop deployment
- **Vercel**: Git integration with auto-deploy
- **Cloudflare Pages**: Fast CDN with free SSL
- **Traditional hosting**: Any web host via FTP

## Maintenance Checklist

### Regular Updates:

- [ ] Add new projects as you complete them
- [ ] Update experience section with new roles
- [ ] Refresh certifications and achievements
- [ ] Update resume PDF regularly
- [ ] Review and update technical skills
- [ ] Check all external links work
- [ ] Optimize and compress images
- [ ] Test on different browsers and devices

### Annual Review:

- [ ] Refresh design if needed
- [ ] Archive old/less relevant projects
- [ ] Update contact information
- [ ] Review SEO and meta descriptions
- [ ] Check for broken links
- [ ] Update copyright year in footer

## 🔗 Contact & Links

- **Email**: rushidaulatkar@proton.me
- **LinkedIn**: [linkedin.com/in/rushi-daulatkar-43669b299](https://www.linkedin.com/in/rushi-daulatkar-43669b299/)
- **GitHub**: [github.com/Illusory-Warden](https://github.com/Illusory-Warden)
- **Phone**: +91 7559495612

## License

© 2024 Rushi Daulatkar. All rights reserved.

This portfolio is for personal use. Feel free to use the template structure for your own portfolio, but please don't copy content or claim the projects as your own.

## Acknowledgments

Built with dedication to simplicity and functionality. No frameworks were harmed in the making of this portfolio.

---

**Last Updated**: December 2024

**Version**: 1.0

**Status**: Active & Maintained
