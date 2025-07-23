# Joint Centre for Disaster Research - PhD Portfolio

This is a Jekyll-based GitHub Pages website showcasing PhD student research portfolios at the Joint Centre for Disaster Research (JCDR), a collaborative research centre between Massey University and GNS Science.

## Features

- Responsive design optimized for all devices
- Student portfolio pages with comprehensive research information
- Blog functionality for research updates and news
- Professional styling with modern UI components
- SEO-optimized with meta tags and structured data
- Easy content management through Markdown files

## Structure

```
├── _config.yml              # Site configuration
├── _layouts/                 # Page templates
│   ├── default.html
│   ├── student.html
│   ├── post.html
├── _includes/                # Reusable components
│   ├── head.html
│   ├── header.html
│   └── footer.html
├── _students/                # Student portfolio collection
│   ├── sarah-johnson.md
│   ├── michael-chen.md
│   └── emma-rodriguez.md
├── _posts/                   # Blog posts
├── assets/
│   ├── css/style.css        # Custom styles
│   └── images/              # Site images
├── pages/                   # Static pages
│   ├── about.md
│   ├── research.md
│   ├── students.md
│   └── contact.md
└── index.html               # Homepage
```

## Setup Instructions

### Local Development

1. **Install Ruby and Jekyll**
   ```bash
   # Install Ruby (if not already installed)
   # On macOS with Homebrew:
   brew install ruby
   
   # Install Jekyll and Bundler
   gem install jekyll bundler
   ```

2. **Clone and Setup**
   ```bash
   git clone <your-repo-url>
   cd jcdr-phd-portfolio
   bundle install
   ```

3. **Run Locally**
   ```bash
   bundle exec jekyll serve
   ```
   
   The site will be available at `http://localhost:4000`

### GitHub Pages Deployment

1. **Repository Setup**
   - Create a new repository on GitHub
   - Push this code to the repository

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Set Source to "Deploy from a branch"
   - Select the `main` branch
   - The site will be available at `https://yourusername.github.io/repository-name`

3. **Update Configuration**
   - Edit `_config.yml` to update the `url` and `baseurl` settings
   - Update site title, description, and contact information

## Adding New Students

To add a new student portfolio:

1. Create a new file in `_students/` directory (e.g., `john-doe.md`)
2. Use the following template:

```yaml
---
name: "Student Name"
research_area: "Research Focus Area"
supervisor: "Supervisor Name"
year: "Year Started"
institution: "Institution"
email: "email@domain.com"
image: "/assets/images/students/student-photo.jpg"
publications:
  - title: "Paper Title"
    journal: "Journal Name"
    year: 2024
    url: "https://link-to-paper.com"
conferences:
  - title: "Presentation Title"
    event: "Conference Name"
    year: 2024
awards:
  - title: "Award Name"
    organization: "Organization"
    year: 2024
skills:
  - "Skill 1"
  - "Skill 2"
social_links:
  - platform: "linkedin"
    url: "https://linkedin.com/in/profile"
---

## Research Description

Write the student's research description here using Markdown formatting...
```

## Adding Blog Posts

Create new files in `_posts/` directory with the naming convention: `YYYY-MM-DD-title.md`

Example frontmatter:
```yaml
---
layout: post
title: "Post Title"
date: 2024-07-24 10:00:00 +1200
author: "Author Name"
categories: research publications
---

Post content here...
```

## Customization

### Styling
- Main styles are in `assets/css/style.css`
- Colors, fonts, and layout can be customized here
- The design uses a professional blue color scheme with modern typography

### Navigation
- Update navigation links in `_includes/header.html`
- Add new pages by creating Markdown files and updating navigation

### Content
- Update site information in `_config.yml`
- Modify page content in the respective Markdown files
- Add images to `assets/images/` directory

## Student Portfolio Features

Each student portfolio includes:
- Professional profile with photo
- Research overview and current projects
- Publications list with links
- Conference presentations
- Awards and recognition
- Skills and expertise tags
- Social media links (LinkedIn, ResearchGate, etc.)
- Contact information

## Technical Features

- **Responsive Design**: Mobile-first approach with grid layouts
- **SEO Optimization**: Meta tags, structured data, sitemap
- **Performance**: Optimized CSS and minimal JavaScript
- **Accessibility**: Semantic HTML and ARIA labels
- **Social Integration**: Font Awesome icons for social platforms

## Contributing

To contribute to this website:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Support

For technical support or questions about the website, contact the JCDR web team at jcdr@massey.ac.nz.

## License

This project is licensed under the MIT License - see the repository for details.
