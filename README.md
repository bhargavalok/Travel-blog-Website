Apna Safar — Travel Blog Website
A travel blog website built from scratch using pure HTML and CSS as part of my web development learning journey. No frameworks, no libraries — just fundamentals.

🌍 About the Project
Apna Safar (meaning "Our Journey" in Hindi) is a multi-page travel blog website that helps users discover hidden destinations, plan trips, and explore the world. Built as a learning project to practice real-world HTML and CSS concepts.

📄 Pages
Home (index.html)

Full screen hero section with background image and dark overlay
Showcase section with alternating image-text destination cards
Features section with icon cards explaining what the site offers
Footer with social media links

About (about.html)

About Us section with two-column checklist layout
Statistics counter section showing traveler numbers
CTA banner linking to contact page
Footer

Contact (contact.html)

Two-column layout with company address and contact form
Form with validation using HTML required attribute
Company image inside address card
Footer


🛠️ Built With

HTML5
CSS3
Font Awesome 6.5 (icons)
Google Fonts — Montserrat


📚 HTML Concepts Used

Semantic HTML tags — header, nav, section, footer, main
Anchor tags with smooth scroll using id and href="#section-id"
HTML forms — input, textarea, label, button
Form attributes — required, placeholder, type, name, id
target="_blank" for external social media links
loading="lazy" on images for performance
alt attributes on all images for accessibility and SEO
meta tags for charset, viewport, and description
Font Awesome icons using <i> tags
&copy; HTML entity in footer


🎨 CSS Concepts Used
Layout

Float-based layouts for navbar, showcase rows, feature boxes
Clearfix using ::after pseudo-element
overflow: hidden as clearfix technique
Container pattern with max-width and margin: 0 auto for centering
Two-column layouts using float: left and float: right

Positioning

position: relative and position: absolute for hero content centering
transform: translate(-50%, -50%) for perfect centering regardless of element size

Typography

Google Fonts import using @import
Font size scale using rem units
letter-spacing and line-height for readability
text-transform: uppercase for headings and buttons

Visual Design

Linear gradients using linear-gradient()
Background image with dark overlay for hero section
background-size: cover and background-position: center
object-fit: cover for images inside fixed height containers
box-shadow using rgba for soft card shadows
border-radius for rounded cards and pill-shaped buttons
::after pseudo-element for decorative underlines on headings

Utility Classes

Color utilities — .text-red, .text-orange, .text-grey, .text-black
Button utilities — .btn, .btn-primary, .btn-secondary
Background utilities — .bg-dark

Interactions

CSS transition for smooth hover effects
Hover states on navbar links, buttons, social icons, and feature cards
Focus states on form inputs with brand color border

Responsive Design

Media queries using @media screen and (max-width)
Two breakpoints — 768px for tablet, 480px for mobile
Stacked layouts on mobile using float: none and width: 100%
Fluid font scaling using html { font-size } combined with rem units


📱 Responsive Breakpoints
Screen SizeBreakpointChangesDesktop1200px+Default layoutTablet≤ 768pxStacked navbar, single column showcase and contactMobile≤ 480pxSmaller fonts, fully stacked layout

🗂️ Project Structure
Travel-blog-Website/
│
├── html-files/
│   ├── index.html
│   ├── about.html
│   └── contact.html
│
├── Css-files/
│   └── style.css
│
└── images-files/
    ├── travel-hd.jpg
    ├── logo-transparent-wow.png
    ├── Company_Logo.jpg
    └── (destination images)

🚀 What I Learned
This project taught me how to think in layouts — breaking every design into nested boxes before writing a single line of code. I learned why floats need clearfix, how position: absolute works with a relative parent, and why rem units combined with a base html font-size make responsive scaling much easier.
The biggest lesson was understanding that clean, readable code matters just as much as working code — especially when you come back to fix something three days later.

🔗 Live Demo
https://travel-blog-website-wheat.vercel.app/

👤 Author
Alok Bhargav

GitHub: @bhargavalok
Instagram: @alok_bhargav_
