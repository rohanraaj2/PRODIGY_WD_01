# Interactive Navigation Menu

A modern, responsive navigation menu with scroll and hover effects built with HTML, CSS, and JavaScript.

## Features

### 🎨 **Visual Effects**
- **Scroll-triggered style changes**: Navigation background becomes darker and more opaque when scrolled
- **Smooth hover animations**: Menu items have animated hover effects with color transitions and scaling
- **Active link highlighting**: Current section is highlighted in the navigation menu
- **Backdrop blur effects**: Modern glassmorphism design with backdrop filters

### 📱 **Responsive Design**
- **Mobile-friendly**: Hamburger menu for mobile devices
- **Flexible layout**: Adapts to different screen sizes
- **Touch-friendly**: Optimized for mobile interactions

### ⚡ **Interactive Features**
- **Fixed positioning**: Navigation stays visible on all pages
- **Smooth scrolling**: Clicking navigation links smoothly scrolls to sections
- **Section detection**: Automatically highlights the current section in view
- **Loading animations**: Smooth entrance effects when page loads
- **Theme toggle**: Bonus dark/light mode toggle button

## Files Structure

```
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript functionality
└── README.md          # Documentation
```

## How It Works

### HTML Structure (`index.html`)
- **Navigation bar**: Fixed position navbar with logo and menu items
- **Content sections**: Multiple sections with different content
- **Mobile toggle**: Hamburger menu for mobile navigation

### CSS Styling (`styles.css`)
- **Base styles**: Reset and typography
- **Navigation styles**: Fixed positioning, transitions, and hover effects
- **Scroll effects**: Different styles for scrolled state
- **Responsive design**: Media queries for mobile devices
- **Animations**: Smooth transitions and hover effects

### JavaScript Functionality (`script.js`)
- **Scroll detection**: Monitors scroll position to change navbar style
- **Active link tracking**: Updates active navigation link based on scroll position
- **Mobile menu**: Handles hamburger menu toggle
- **Smooth scrolling**: Implements smooth scroll behavior for navigation links
- **Intersection Observer**: Animates sections as they come into view
- **Theme toggle**: Optional dark mode functionality

## Key Features Explained

### 1. Scroll-Triggered Changes
When the user scrolls down more than 50 pixels:
- Background changes from light to dark
- Text color inverts for better contrast
- Padding reduces for a more compact look
- Hover effects change color scheme

### 2. Hover Effects
Each navigation link features:
- **Background animation**: Sliding gradient background on hover
- **Transform effects**: Slight upward movement and scaling
- **Color transitions**: Smooth color changes
- **Box shadows**: Glowing effect on hover

### 3. Active Link Detection
- Uses Intersection Observer API to detect which section is in view
- Automatically highlights the corresponding navigation link
- Smooth transitions between active states

### 4. Mobile Responsiveness
- Hamburger menu appears on screens smaller than 768px
- Touch-friendly navigation with proper spacing
- Backdrop blur maintains modern aesthetic on mobile

## Customization

### Colors
Modify the color scheme by changing these CSS variables:
- Primary blue: `#3498db`
- Dark blue: `#2980b9`
- Red accent: `#e74c3c`
- Dark red: `#c0392b`
- Text dark: `#2c3e50`

### Scroll Trigger Point
Change when the navbar style changes by modifying the scroll threshold in `script.js`:
```javascript
const scrolled = window.scrollY > 50; // Change 50 to desired pixel value
```

### Animation Timing
Adjust animation speeds by modifying the CSS transition durations:
```css
transition: all 0.3s ease; /* Change 0.3s to desired duration */
```

## Browser Support
- Modern browsers with CSS Grid and Flexbox support
- Backdrop filter support (Safari, Chrome, Firefox, Edge)
- Intersection Observer API support

## Usage
1. Open `index.html` in a web browser
2. Scroll through the page to see the navigation changes
3. Hover over menu items to see hover effects
4. Try the mobile view by resizing your browser window
5. Use the theme toggle button in the bottom-right corner

## Live Demo
Simply open the `index.html` file in your web browser to see the interactive navigation menu in action!
