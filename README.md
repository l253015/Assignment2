Seed (Project Concept)
Essence is a luxury perfume e-commerce website designed to showcase premium fragrances with elegance and sophistication. The concept was born from the idea of creating an immersive digital experience that mirrors the refined nature of high-end perfumery. The website aims to capture the emotional connection between fragrance and identity, presenting perfumes not just as products, but as personal statements.
Target Audience: Fashion-conscious individuals aged 25-45 who appreciate luxury products and seek unique, high-quality fragrances that reflect their personality and lifestyle.
Primary Goals:

Create an elegant, minimalist design that reflects luxury branding
Provide an intuitive shopping experience with a pre-order system
Showcase the product line through an interactive dropdown gallery
Build trust through customer testimonials and brand storytelling
Ensure responsive design for seamless browsing across all devices

Design Rationale
Color Palette

Primary Color: #79a9a6 (Sage Green) - Chosen to evoke natural elegance, sophistication, and tranquility. This muted teal represents the organic, sustainably-sourced ingredients mentioned in the brand philosophy.
Secondary Color: #e7ebed (Soft Gray-Blue) - Creates a clean, airy atmosphere that doesn't compete with the product imagery. Provides a subtle backdrop that enhances readability.
Accent Color: #2d2d2d / #131212 (Charcoal Black) - Used for text and borders to provide strong contrast and convey premium quality and timelessness.
Background: #ffffff (Pure White) - Emphasizes cleanliness, purity, and luxury while allowing other elements to stand out.

Why these colors? The color scheme was carefully selected to communicate luxury without being ostentatious. Sage green is trending in high-end design and connects to the brand's emphasis on natural ingredients and sustainability. The muted palette creates a spa-like, calming experience that aligns with the sensory nature of perfume shopping.
Typography

Brand Name: Times New Roman - A classic serif font that communicates timeless elegance and established luxury. The letter-spacing of 4px adds sophistication and breathing room.
Hero Heading: Segoe Script - A flowing script font for "Own your essence" creates an emotional, personal connection. Script fonts are traditionally associated with signatures and personal identity, reinforcing the brand message.
Body Text: Times New Roman - Maintains consistency and readability while preserving the classic, editorial feel of luxury magazines.
Navigation: Times New Roman - Keeps the interface clean and professional with a universally readable serif font.

Layout Decisions
Hero Section Strategy:
The layout features a large hero section (#box) with an absolute-positioned perfume bottle on the left and text content on the right. This creates visual balance and immediately showcases the product while communicating brand values.
Asymmetric Balance:
Rather than centering all content, the design uses left-aligned text with the perfume bottle image positioned on the left side. This creates visual interest and mimics high-end magazine layouts commonly seen in luxury advertising.
Fixed Navigation:
The horizontal navigation menu at the top uses flexbox for even spacing and remains accessible throughout the browsing experience. The hover effect (color change + increased font-weight) provides clear visual feedback.
Whitespace Philosophy:
Generous margins and padding throughout the design prevent visual clutter. The hero section uses min-height: 85vh to create an impactful, full-screen experience that doesn't feel cramped.
User Experience (UX)
Interactive Product Dropdown:
Hovering over "Products" reveals a full-screen overlay with a grid of product images. This approach:

Keeps the main page clean and focused
Provides visual product preview without leaving the page
Uses CSS :hover and position: fixed for smooth transitions
Includes a dark overlay (rgba(0, 0, 0, 0.6)) to maintain focus on products

Modal Form Design:
The pre-order form uses CSS target pseudo-class (:target) to appear as a modal popup:

Prevents page refresh and maintains user context
Full-screen overlay ensures focus on form completion
Close button (×) positioned top-right for intuitive dismissal
Scrollable content ensures accessibility on smaller screens

Form Structure:
The pre-order form collects comprehensive customer data:

Text inputs for name, email, address (basic information)
Checkboxes for previous product experience (builds customer profile)
Radio buttons for bottle size selection (ensures single choice)
Dropdown menu for occasion selection (helps with product recommendations)
Textarea for custom messages (encourages customer communication)

Accessibility Considerations:

Semantic HTML with proper heading hierarchy (h1, h2, h3)
Form labels wrapped around inputs for larger click targets
High contrast ratios for text readability
Hover states on all interactive elements
required attributes on critical form fields


Features

Elegant Hero Section with absolute-positioned product imagery
Interactive Product Gallery triggered by hover dropdown
Modal Pre-Order Form with multiple input types (text, email, checkboxes, radio buttons, dropdown, textarea)
Smooth Hover Interactions on navigation, buttons, and product images
CSS-Only Modal System using :target pseudo-class (no JavaScript required)
Consistent Brand Identity through color palette and typography
Customer Testimonials with star ratings for social proof
Responsive Navigation using Flexbox
Anchor Link Navigation for seamless page scrolling
Semantic HTML5 structure for accessibility


Technologies Used

HTML5 - Semantic structure with modern elements
CSS3 - Advanced selectors, Flexbox, Grid, pseudo-classes, transitions
Pure CSS Modals - No JavaScript required for interactive elements
Git & GitHub - Version control and collaboration
GitHub Pages - Live deployment



Technical Skills Gained:
Throughout this project, I deepened my understanding of CSS positioning, particularly the difference between relative, absolute, and fixed positioning. The perfume bottle image required careful positioning to maintain visual balance across the hero section, teaching me how absolute positioning interacts with relative parent containers.
I also learned to create interactive UI components using pure CSS without JavaScript. The product dropdown and modal form both use CSS pseudo-classes (:hover and :target) to create dynamic user experiences. This approach keeps the code lightweight while maintaining functionality.
Design Insights:
Creating a luxury brand aesthetic taught me the importance of restraint in design. The muted color palette, generous whitespace, and limited font families work together to communicate sophistication. I learned that "less is more" in high-end design—every element must serve a purpose.
Challenges Faced:

Image Path Issues - Initially used absolute file paths (C:\Users\...) which won't work on GitHub Pages. Solution: Convert to relative paths (assets/images/filename.png)
Form Overlay Positioning - The modal form initially wouldn't scroll on smaller content. Solution: Added overflow-y: auto and padding to the overlay container to ensure scrollability.
Dropdown Hover Stability - The product dropdown would flicker when moving the mouse. Solution: Used pointer-events and opacity transitions to create a smooth hover experience.

Skills Improved:

CSS Grid and Flexbox for complex layouts
Form design with multiple input types and validation
Color theory and typography for brand identity
CSS transitions and hover effects
Semantic HTML structure and accessibility considerations


Future Improvements

Add Mobile Responsiveness - Implement media queries to stack content vertically on mobile devices, resize the perfume bottle, and create a hamburger menu
Create Custom SVG Logo - Design a unique vector logo to replace the text-based brand name
JavaScript Form Validation - Add client-side validation with error messages for better UX
Shopping Cart Functionality - Build a full e-commerce experience with add-to-cart and checkout
Product Detail Pages - Create individual pages for each perfume with detailed descriptions and notes
Animation Effects - Add subtle scroll animations and parallax effects for enhanced interactivity
Dark Mode Toggle - Implement a theme switcher for user preference
Fix Image Paths - Convert all absolute paths to relative paths for proper GitHub Pages deployment


Aliha Saeed

GitHub: @l253015 
Email: l253015@lhr.nu.edu.pk
Course: BS-SE 1B


Project Timeline
Started: November 7, 2025 
Completed: November 14, 2025
Submitted: November 16, 2025



## 🎥 Demo Video

**Video Link:** (https://drive.google.com/file/d/1srKjBzkSUIERUly7Lf4_fS2JlCLifhhd/view?usp=drive_link)

**Video demonstrates:**
- ✅ Responsive design (resizing browser)
- ✅ Navigation through all sections
- ✅ Product dropdown hover interaction
- ✅ Form modal opening and interaction
- ✅ All form input types demonstrated