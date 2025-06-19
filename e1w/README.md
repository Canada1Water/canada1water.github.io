# Just the Class - GitHub Pages Setup

This is a complete duplication of the "Just the Class" Jekyll theme for course websites. This template provides a robust foundation for creating academic course websites with the following features:

## Features

- **Announcements**: Course announcements with automatic date formatting
- **Course Calendar**: Module-based content organization 
- **Staff Directory**: Instructor and TA profiles with contact information
- **Weekly Schedule**: Visual schedule with time slots and locations
- **About Page**: Course information and policies
- **Modern Design**: Built on the Just the Docs theme with responsive design

## Structure

```
e1w/
├── _announcements/     # Course announcements
├── _layouts/          # Custom Jekyll layouts
├── _includes/         # Reusable template components
├── _modules/          # Course modules/weeks
├── _sass/             # Custom styling
├── _schedules/        # Weekly schedules
├── _staffers/         # Staff profiles
├── assets/            # Images, CSS, and other assets
├── _config.yml        # Jekyll configuration
├── index.md           # Home page
├── about.md           # About/course info page
├── announcements.md   # Announcements listing
├── calendar.md        # Course calendar
├── schedule.md        # Weekly schedule
└── staff.md           # Staff directory
```

## Customization

### 1. Update Site Information
Edit `_config.yml` to customize:
- `title`: Your course title
- `description`: Course description
- `author`: Your name
- `url`: Your GitHub Pages URL
- `baseurl`: Should remain `/e1w`

### 2. Add Staff Members
Create new files in `_staffers/` directory:
```yaml
---
name: Your Name
role: Instructor
email: your.email@institution.edu
website: https://your-website.com
photo: your-photo.jpg
meta:
  Office Hours: "Mon/Wed 2-3 PM"
---

Brief bio or additional information.
```

### 3. Add Course Modules
Create new files in `_modules/` directory:
```yaml
---
title: Week 1 - Introduction
---

Jan 15
: [Course Introduction](#)
  : [Slides](#)

Jan 17
: **Lab**{: .label .label-purple } [Setup Lab](#)
```

### 4. Create Weekly Schedules
Edit `_schedules/weekly.md` to match your course times and locations.

### 5. Add Announcements
Create new files in `_announcements/` directory:
```yaml
---
title: Welcome to the Course
date: 2025-01-15
---

Welcome message content here.
```

### 6. Add Staff Photos
Place staff photos in `assets/images/` directory and reference them in staff profiles.

## Local Development

To test the site locally:

1. Install Jekyll and dependencies:
   ```bash
   bundle install
   ```

2. Serve the site:
   ```bash
   bundle exec jekyll serve --baseurl=""
   ```

3. Visit `http://localhost:4000/e1w/`

## GitHub Pages Deployment

The site is automatically deployed to GitHub Pages at:
`https://canada1water.github.io/e1w/`

Any changes pushed to the main branch will trigger a rebuild.

## Theme Documentation

This template is based on:
- **Just the Class**: https://github.com/kevinlin1/just-the-class
- **Just the Docs**: https://just-the-docs.github.io/just-the-docs/

Refer to these resources for advanced customization options.
