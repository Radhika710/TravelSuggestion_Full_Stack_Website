## Website Overview:

Travel Buddy is a user-friendly travel recommendation website designed to inspire and assist travelers in discovering amazing destinations. The site features five HTML pages, each dedicated to a specific aspect of travel, including top destinations for the current year, picturesque spots for Instagram enthusiasts, and subscription plans for personalized assistance.

Key Features:

- Interactive Navigation: Easily explore various categories and pages through an intuitive navigation pane.
- Diverse Content: From the latest travel hotspots to curated lists of aesthetic locations, Travel Buddy offers a wealth of information for every traveler.
- Subscription Plans: For users seeking more personalized support, we offer subscription options that provide closer assistance and tailored recommendations.

## Brief description of 5 HTML Pages:

- index.html: This is the landing page for the Travel Buddy website, providing an overview of what the site offers. It features a concise introduction to the platform, along with links to various HTML pages that cater to different travel categories, allowing users to easily navigate their options.

- Instagram.html: This page curates a collection of stunning destinations that are perfect for enhancing travelers' Instagram aesthetics. It features picturesque spots that are sure to captivate followers and elevate any traveler's social media presence. Additionally, by clicking on 'Show Gallery,' you can explore creative pose suggestions that you can easily mimic at each location for stunning travel photos.

- TopPlaces_2024.html: This page showcases a curated selection of the top destinations recommended by Travel Buddy experts for the current year. Each location is highlighted to inspire users with the best travel choices.

- Plans.html: This page outlines the various subscription plans available through Travel Buddy. It provides details on how users can enroll for personalized support and travel assistance, helping them choose the best option for their needs.

- Europe.html: This page suggests popular destinations specifically within Europe, offering insights into must-visit locations. It serves as a guide for travelers looking to explore the diverse experiences Europe has to offer.

## HTML Elements Used:

- **<span>**: Used to emphasize city names within the paragraphs in the Europe.html file.

- **<div>**: Divisions are used to group content and apply styles or layout properties, helping to organize the structure of the page (e.g., .wrapper, .content, .card-container).

- **Card**: Used as an advanced feature with div; the card elements enhance the user experience by organizing content in a visually appealing and interactive manner.

- **<img>**: Images visually enhance the content, making it more engaging. The alt attribute improves accessibility and provides descriptions if the image fails to load.

- **<a>**: Anchor tags create hyperlinks for navigation between different pages, enhancing user experience.

- **<button>**: Used for interactive elements, such as toggling galleries, allowing users to engage with the content.

- **<footer>**: This semantic element is used for footer content, providing a clear structure and denoting the end of the main content.

- **<table>**: Tables display structured data (subscription features) in a clear and organized manner.

- **<ol> and <li>**: Ordered lists present a list of destinations, indicating a sequence and improving readability.

- **<nav>**: This element facilitates navigation links, making it easy for users to move between different pages, specifically navigating back to the home page.

## CSS Styles Applied:

1. Color Scheme: Custom CSS variables define a consistent color palette across the site (light gray, background, accent, etc.).
2. Typography: A clean font-family and centered, responsive layout for text elements.
3. Wrapper and Content Layout: Flexbox and grid are used for centering content and adjusting layout across different screen sizes.
4. Header/Footer Styling: Light gray background color for both the header and footer for a subtle design.
5. Title Section: Large font size with a background image and text accent color for the title.
6. Buttons: Custom button styling with padding, border-radius, and hover effects.
7. Cards and Containers: Flexbox-based card layouts for items like galleries and pricing cards, with box-shadows for depth and visual separation.
8. Dark Mode: A toggleable dark mode alters background color and text styling to white when activated.
9. Image Styles: Full-width, responsive images with a "cover" object fit for layout elements like galleries.
10. Tables: Styled with padding, borders, and hover effects for a clean, modern look.
11. Navigation Links: Transition effects applied to hover states, with padding and border-radius for a button-like feel.

## W3C Validations link:

- for front-page HTML: https://validator.w3.org/nu/?doc=https%3A%2F%2Frogue-sudden-lemon.glitch.me%2Findex.html
- for front-page CSS: https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Frogue-sudden-lemon.glitch.me%2Findex.html#textarea

## Javascript code to add interactivity:

Here's a brief summary of the key points:

1. Dark Mode Toggle: An event listener is attached to the "Dark Mode" button, which toggles the dark-mode class on the body of the webpage, allowing users to switch between light and dark themes.
2. Gallery Display Toggle: Multiple event listeners are attached to the gallery buttons, enabling users to show or hide the associated image gallery by toggling the display property between none and flex when clicked.

