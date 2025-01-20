Kali Cafe Webpage Documentation

Overview

The Kali Cafe webpage is a simple yet visually appealing website designed to present the cafe’s menu, about section, and contact details.
The page employs HTML for structure and CSS for styling, ensuring a user-friendly interface with a modern design.

1. HTML Structure

1.1 Document Setup

The webpage is defined as an HTML5 document (<!DOCTYPE html>).

The language is set to English (<html lang="en">).

The meta tags define character encoding (UTF-8) and viewport settings for responsiveness.

The page title is set as Kali Cafe.

1.2 Navigation Bar

A fixed navigation bar (<nav>) is positioned at the top of the page.

Includes a logo (<img> inside .logo div).

Navigation links (#home, #menu, #about, #contact).

Uses a flexbox layout for spacing and alignment.

1.3 Home Section

Contains a background image (pastry1.avif).

Displays a welcome message (WELCOME TO KALI CAFE).

Descriptive text introduces the cafe’s theme.

1.4 About Section

Includes a heading (About Us) styled with a colored background.

Describes the cafe’s location, mission, and specialty offerings.

1.5 Menu Section

Lists drinks and pastries in a grid layout.

Each menu item is wrapped in #menu-card, containing:

An image (<img class="drinkimage">).

The name of the item (<p> tag).

The price (<p> tag).

#menu-card has hover effects to scale up and add shadow.

1.6 Contact Section

Displays contact details with an emphasis on social media icons.

Uses flexbox for alignment.

Includes a working contact form for user inquiries.

1.7 Footer Section

Includes three sections (footer-left, footer-center, footer-bottom).

Displays social media links with interactive hover effects.

Fixed at the bottom of the page.

2. CSS Styling

2.1 Global Styles

Sets default margin, padding, and font-family (Arial, sans-serif).

Applies box-sizing: border-box for consistent element sizing.

2.2 Navigation Bar Styles

Fixed positioning with a white background and box shadow.

Flexbox used for spacing (gap: 42px).

Logo is circular (border-radius: 50%).

Hover effects added to links (text-decoration: underline).

2.3 Home Section Styles

Full viewport height (height: 100vh).

Background image covers the entire section (background-size: cover).

z-index ensures welcome text overlays the background.

2.4 Menu Section Styles

Background color set to light gray (#f8f8f8).

Grid layout for drinks and pastries (grid-template-columns: repeat(auto-fit, minmax(200px, 1fr))).

#menu-card includes:

Rounded corners (border-radius: 10px).

Shadow effects (box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1)).

Hover animations (transform: scale(1.05)).

2.5 Footer Styles

Background color set to dark gray (#333).

Text color set to white.

Flexbox used for layout (display: flex; flex-direction: column).

Social media icons have hover scaling effects.

2.6 Responsive Design

Media queries adjust padding and font sizes for smaller screens (max-width: 768px).

Ensures optimal readability and layout on mobile devices.

Implements a dark mode toggle for improved accessibility.

3. Features

3.1 Features Implemented

✔ Fixed navigation bar for easy access.
✔ Grid-based menu layout.
✔ Hover effects for interactive UI.
✔ Social media icons in the footer.
✔ Box-shadow and hover animations for enhanced visuals.
✔ Careful selection of images and placement.
✔ Structured layout with clear navigation.


4. Conclusion

The Kali Cafe webpage provides a visually appealing and functional cafe website. 
With a structured layout, clean navigation, and interactive features, it creates an engaging experience for visitors. 
