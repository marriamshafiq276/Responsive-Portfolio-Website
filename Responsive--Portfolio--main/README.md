# Responsive Portfolio Website

A modern, responsive personal portfolio website for **Marriam Shafiq**, a frontend web developer and designer. The site presents an introduction, services, selected projects, testimonials, and a contact form in a single-page layout.

## Features

- Fully responsive layout for desktop, tablet, and mobile screens
- Sticky navigation with active-section highlighting
- Mobile navigation menu
- Light and dark mode toggle
- Animated profession display on the home section
- Scroll-reveal animations
- Project cards with hover overlays
- Testimonial carousel with pagination and navigation controls
- Contact form interface and social-media links

## Built With

- HTML5
- CSS3, including custom properties, media queries, animations, Flexbox, and Grid
- JavaScript
- [Boxicons](https://boxicons.com/) for icons
- [Swiper](https://swiperjs.com/) for the testimonial slider
- [ScrollReveal](https://scrollrevealjs.org/) for scroll animations

## Project Structure

```text
.
├── index.html      # Main page structure
├── style.css       # Site styling, animations, and responsive breakpoints
├── script.js       # Navigation, theme, carousel, and reveal interactions
├── portfolio.png   # Profile image
├── pf1.png         # Portfolio project image
├── plants.png      # Plants project image
├── movies.png      # Movies project image
├── test1.jpg       # Testimonial image
├── test-2.jpg      # Testimonial image
└── test-3.jpg      # Testimonial image
```

## Run Locally

No installation or build step is required.

1. Download or clone this repository.
2. Open `index.html` in a web browser.

For the best development experience, run the project using a local development server such as VS Code's Live Server extension.

## Customization

- Update the text, links, and contact details in `index.html`.
- Replace the images in the project root while retaining the same filenames, or update their `src` attributes in `index.html`.
- Adjust the visual theme in `style.css` through the variables under `:root`.
- Add real destinations to the social, CV, project, and contact links, which currently use placeholder `#` links.

## Notes

The contact form is currently a front-end interface only (`action="#"`). Connect it to a form service or backend endpoint to receive submissions.

## Author

**Marriam Shafiq**
