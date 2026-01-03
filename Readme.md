A responsive travel website for Sedona, Arizona, developed as the main project for Bootcamp's professional web development course. This project demonstrates semantic HTML markup, modern CSS techniques, and pixel-perfect implementation of provided designs without relying on frameworks.

# 📋 Project Overview  
Sedona is a two-page website (homepage + catalog) that showcases tourism services in Sedona, Arizona. The project emphasizes semantic HTML, accessible markup, and progressive enhancement principles.

## Key Features  
✅ **Semantic HTML** markup with proper document structure  
✅ **Pixel-perfect** implementation of provided designs  
✅ **Cross-browser** compatibility (Chrome, Firefox, Safari)  
✅ **Interactive elements** with proper states and feedback   
✅ **Form validation** with server submission handling  
✅ **Responsive typography** using PT Sans font  
✅ **Shadow effect** implementation around content area  

# 🎯 Technical Requirements Met  
## Layout & Design  
•	Fixed-width centered layout (non-responsive)  
•	Precise grid implementation as per mockups  
•	PT Sans font from local files and Google Fonts  
•	Style guide compliance for all UI states  
•	Gray background with subtle shadow effect on sides  

## Homepage Features  
•	Header Navigation: Interactive favorites counter (12+), search icon, and "I want to go" button  
•	Hero Section: Full-width photo with white gradient mask, decorative text image  
•	Service Sections: Decorative icons for "Housing", "Food", and "Souvenirs"  
•	Interactive Modal: Hotel search modal triggered by CTA button  
•	Newsletter Form: Validation preventing empty submissions, posts to HTML Academy echo server  
•	Footer: Clickable phone number (tel: link), Academy logo linking to course page  

## Catalog Page Features  
•	Breadcrumbs: Home icon linking to main page  
•	Active States: "Hotels" link marked as current page  
•	Filter System:  
    -	Form-based filtering with "Apply" button (posts to echo server)    
    -	"Reset" button returning form to initial state     
    -	Interactive range slider for price filtering    
•	View Toggles: Tile/Card/List view with GET parameter implementation  
•	Hotel Cards:    
    -	"Add to favorites"/"In favorites" buttons (visual states)    
    -	"More details" links for hotel pages    
•	Pagination: Active page state without hover/focus interactions  

# 🛠️ Technologies & Tools  
## Core Stack:  
•	**HTML** - Semantic markup with proper document structure  
•	**CSS** - Modern styling with flexbox/float layout  
•	**PT Sans Font** - Typography as specified in design  
  
## Development Tools:  
•	**Visual Studio Code** - Primary code editor  
•	**Git & GitHub** - Version control and deployment  
•	**Pixel Perfect** - Chrome extension for design accuracy  
•	**Browser DevTools** - Debugging and testing  
  
## Design Compliance:  
•	**Style Guide** - Highest priority for UI states  
•	**Mockup Files** - Adobe Photoshop designs provided  
•	**Cross-browser Testing** - Chrome, Firefox, Safari  

# 📁 Project Structure  
text  
sedona/  
├── index.html              # Homepage  
├── catalog.html           # Catalog page  
├── css/  
│   ├── style.css         # Main stylesheet  
│   └── normalize.css     # CSS reset  
├── fonts/  
│   └── ptsans/           # PT Sans font files  
├── img/                  # All images and icons  
│   ├── sprites/         # Sprite images  
│   ├── content/         # Content images  
│   └── decorative/      # Decorative elements  
├── js/                   # JavaScript for interactivity  
│   ├── script.js        # Main scripts  
│   └── modal.js         # Modal window functionality  
└── README.md            # Project documentation  

# 🚀 Getting Started
## Prerequisites
- Any modern web browser (Chrome, Firefox, Safari)
- Text editor or IDE
- Git (optional)
  
## Installation

```bash
# Clone repository
git clone https://github.com/yourusername/sedona.git

# Navigate to project
cd sedona

# Open in browser (or use Live Server extension)
open index.html

Local Development  
No build process required - this is a static HTML/CSS project.  
Simply open the HTML files in your browser or use a local server for the best experience.    
```

# 🎨 Design Implementation Details  
## Layout Principles  
•	**Centered Container:** Fixed-width content area centered horizontally  
•	**Shadow Effect:** Subtle shadow on both sides of content area  
•	**Typography:** PT Sans with precise font sizes, weights, and line heights  
•	**Color Scheme:** Exact colors from style guide and mockups  
  
## Interactive Elements  
•	**Hover/Focus States:** All interactive elements have proper visual feedback  
•	**Form Validation:** Client-side validation with meaningful error states  
•	**Modal Windows:** Smooth open/close transitions with overlay  
•	**Range Slider:** Custom-styled price filter with dual handles  
  
## Performance Optimizations  
•	**CSS Sprites:** Combined icons into sprite sheets  
•	**Font Optimization:** Local font loading with fallback to Google Fonts  
•	**Image Optimization:** Compressed images without quality loss  

# 🔍 Key Learning Outcomes  
## Technical Skills Developed  
1.	**Semantic HTML:** Proper use of HTML elements for accessibility and SEO  
2.	**CSS Mastery:** Advanced selectors, positioning, and layout techniques  
3.	**Pixel-Perfect Development:** Precise implementation of design specifications  
4.	**Cross-Browser Testing:** Ensuring consistent experience across browsers  
5.	**Form Handling:** Validation, submission, and user feedback implementation
     
## Professional Practices  
•	Style Guide Compliance: Adherence to provided design specifications  
•	Code Organization: Clean, maintainable, and commented code  
•	Progressive Enhancement: Core functionality without JavaScript  
•	Accessibility Considerations: Semantic markup and ARIA labels  

# 📱 Browser Support  
| Browser | Version | Status             |  
|:---------:|:----------:|:--------------------:|  
| Chrome  |	90+	   | ✅ Fully supported |  
| Firefox	| 88+     | ✅ Fully supported |  
| Safari  | 14+     | ✅ Fully supported |  

# 🧪 Testing Checklist  
•	All links are functional and lead to correct pages  
•	Forms validate input and submit properly  
•	Modal windows open/close correctly  
•	Interactive elements have proper hover/focus states  
•	Design matches mockups at 100% zoom  
•	Cross-browser consistency verified  
•	No console errors in browser DevTools  
•	HTML validation passes W3C standards  
•	CSS validation passes W3C standards  

# 📄 Project Context  
This project was developed as the capstone project for a Bootcamp's "Professional HTML & CSS" course. It represents approximately 80 hours of focused development work, including:  
•	**Design Analysis:** Studying mockups and style guides  
•	**Semantic Markup:** Planning and implementing HTML structure  
•	**Styling Implementation:** CSS development with attention to detail  
•	**Testing & Debugging:** Cross-browser testing and issue resolution  
•	**Code Review:** Incorporating feedback from mentor reviews  

# 👨‍💻 Author  
Student Software Developer  
________________________________________
Note: This is an educational project developed for a professional web development course. All designs and specifications were provided as part of the curriculum.
