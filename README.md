# Responsive YouTube UI Clone

> A static front-end clone of YouTube's homepage built with HTML and CSS — focused on layout, Flexbox, and CSS Grid practice.

## Overview

This project replicates the core visual layout of YouTube's homepage using pure HTML and CSS. It includes a fixed navigation header, a sidebar with section links, and a responsive video thumbnail grid. No JavaScript or APIs are used — the focus is entirely on building layouts with Flexbox and CSS Grid.

Best viewed on a laptop or desktop screen.

## Features

- Fixed header with search bar, navigation icons, and user profile section
- Sidebar with Home, Explore, Subscriptions, and Library links
- CSS Grid-based responsive video thumbnail gallery
- Thumbnail cards showing title, channel name, views, and upload time
- Materialize CSS for consistent base styling and icons
- Desktop-optimized layout

## Technologies Used

- **HTML5** — Page structure and semantic layout
- **CSS3** — Styling, spacing, and visual design
- **CSS Flexbox** — Header and sidebar alignment
- **CSS Grid** — Video thumbnail grid layout
- **Materialize CSS** — Component styling and icons


## How It Works

Static HTML structures each page section. CSS Flexbox handles the header and sidebar. CSS Grid organizes the video card layout. Materialize CSS provides base styles and icon support. All content is hardcoded — no backend or API.


## Installation & Setup

No build tools required.
```bash
git clone https://github.com/your-username/youtube-ui-clone-html-css.git
cd youtube-ui-clone-html-css

# Open in browser
open index.html
```

Or simply double-click `index.html` to open it in your browser.

> **Note:** Best viewed on a desktop or laptop screen.


## Usage

Open `index.html` in a browser to view the interface. All content is static.

## Future Improvements

- Add responsive breakpoints for mobile and tablet
- Integrate YouTube Data API v3 for real video thumbnails
- Add dark/light mode toggle using CSS variables
- Add a functional search results page with JavaScript filtering

## What I Learned

- How CSS Grid and Flexbox solve different layout problems
- Building a multi-section page layout from scratch
- How to use a CSS framework (Materialize) without over-relying on it
- Importance of fixed positioning for navigation headers
