### Social Links App

## Overview
# The challenge
<u>Users should be able to:</u>

- View the optimal layout for the site depending on their device's screen size

- See hover and focus states for all interactive elements on the page

- Access all social media links with proper styling and functionality

<u>Screenshot</u>
https://imgur.com/GCwtKU1

Links  

Live Site URL: (http://tysonad64.github.io/social-links-app/)

## My process
# Built with:
- Semantic HTML5 markup

- CSS custom properties

- Flexbox

- Mobile-first workflow

- CSS Grid for layout structure

- Font Awesome icons for social media links

# What I learned
Through this project, I deepened my understanding of several key web development concepts:

CSS Custom Properties (Variables): I implemented a comprehensive color system using CSS variables, making it easy to maintain consistent theming throughout the project.

css
:root{
    /** Deep space colors */
    --clr-deep-space-a0: #000000;
    --clr-deep-space-a10: #0A0A2A;
    --clr-deep-space-a20: #1A1A3A;
    /* ... more color variables */
}
Responsive Design: I created a fully responsive layout that works seamlessly across mobile, tablet, and desktop devices using media queries and flexible units.

css
@media (max-width: 480px) {
    .card {
        padding: 20px 15px;
        margin: 20px auto;
    }
    
    .profile-picture {
        width: 90px;
        height: 90px;
    }
    
    /* ... more responsive adjustments */
}
Interactive Elements: I implemented smooth hover and focus states for all interactive elements, enhancing the user experience.

css
.link:hover {
    background-color: var(--clr-primary-a30);
    box-shadow: 0 6px 12px var(--clr-surface-a0);
    transform: translateY(-2px);
}

.link:focus {
    background-color: var(--clr-primary-a30);
    box-shadow: 0 6px 12px var(--clr-surface-a0);
    transform: translateY(-2px);
    outline: none;
}
External Resource Integration: I successfully integrated Font Awesome icons via CDN and ensured they displayed correctly across all devices.

## Useful resources
- Font Awesome Documentation - Helped with properly implementing and styling icons.

- CSS-Tricks Guide to Flexbox - Excellent resource for understanding flexbox layout.

- MDN Web Docs - Comprehensive reference for HTML and CSS properties.

