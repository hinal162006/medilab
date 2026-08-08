# Medilab

A responsive healthcare clinic landing page built with HTML, CSS, and Bootstrap 5. Designed for medical clinics, hospitals, and healthcare practices that need a clean, professional web presence — no backend or build tools required.

**Live demo:** https://hinal162006.github.io/medilab/

---

## Features

- **Hero section** with a clear call-to-action for booking appointments
- **About Us** section highlighting the clinic's values and experience
- **Stats counters** — doctors, departments, research labs, and awards
- **Services** overview with icon-based service cards
- **Appointment booking form** with department and doctor selection
- **Departments** section with a tabbed interface (Cardiology, Neurology, Hepatology, Pediatrics, Eye Care)
- **Doctor profiles** with photos, roles, and social links
- **FAQ accordion** for common patient questions
- **Testimonials carousel** with patient reviews
- **Photo gallery** of the facility and staff
- **Contact section** with an embedded map and contact form
- Fully responsive layout — works on mobile, tablet, and desktop
- Smooth scrolling navigation with an active-link indicator

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom styling with CSS variables
- **[Bootstrap 5.3.3](https://getbootstrap.com/)** — layout, grid, and components (loaded via CDN)
- **[Bootstrap Icons 1.11.3](https://icons.getbootstrap.com/)** — icon set (loaded via CDN)
- **Google Fonts** — Poppins & Jost (loaded via CDN)
- Vanilla JavaScript for navbar scroll effects and mobile menu behavior

No build step, no package manager, no server-side code — it's a single static `index.html` file plus an `images/` folder.

## Getting Started

### View it live

This repo is deployed with **GitHub Pages**. Visit:

```
https://hinal162006.github.io/medilab/
```

### Run it locally

Clone the repo and open `index.html` directly in a browser:

```bash
git clone https://github.com/hinal162006/medilab.git
cd medilab
open index.html   # or double-click the file
```

For a more accurate local preview (some browsers restrict local file access), serve it with a simple HTTP server instead:

```bash
# Python 3
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

## Project Structure

```
.
├── index.html      # the entire site — HTML, CSS, and JS in one file
├── images/         # all photos used across the site
└── README.md
```

## Deployment

This site is deployed with GitHub Pages, deploying straight from the `main` branch (`/root`). To deploy your own copy:

1. Fork or clone this repo
2. Push your changes to `main`
3. In your repo, go to **Settings → Pages**
4. Under **Build and deployment → Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save

GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Notes

- All content (doctor names, testimonials, statistics) is sample/placeholder content for demonstration purposes.
- Fonts and icons are loaded from external CDNs (Google Fonts, jsDelivr) — an internet connection is required for them to display correctly.

## License

This project is free to use for personal and commercial projects.
