# Image Gallery

A sleek and interactive horizontal image gallery built with vanilla JavaScript, HTML, and CSS. This project showcases a collection of images with smooth scrolling, navigation controls, and engaging hover effects.

## Features

### Core Functionality
- **Horizontal Scrolling Gallery**: Displays images in a horizontally scrollable container
- **Navigation Controls**: Previous and next buttons for easy navigation
- **Mouse Wheel Support**: Scroll through images using the mouse wheel for intuitive interaction
- **Smooth Animations**: CSS transitions for seamless scrolling and hover effects

### Visual Effects
- **Grayscale to Color Transition**: Images start in grayscale and reveal color on hover
- **Scale Animation**: Images enlarge slightly when hovered over
- **Glow Effect**: Blue glow and border appear on hover for visual feedback
- **Hidden Scrollbar**: Clean design with no visible scrollbars

### Technical Features
- **Responsive Design**: Adapts to different screen sizes
- **Cross-browser Compatibility**: Works across modern web browsers
- **Lightweight**: No external dependencies, pure vanilla JavaScript
- **Performance Optimized**: Smooth 60fps animations using CSS transforms

## Live Demo

Experience the gallery in action: [https://itsiamdev.github.io/Image-Gallery/](https://itsiamdev.github.io/Image-Gallery/)

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with grid layout, transitions, and transforms
- **Vanilla JavaScript**: DOM manipulation and event handling
- **Font**: Poppins from Google Fonts

## Project Structure

```
Image Gallery/
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # JavaScript functionality
├── images/             # Image assets
│   ├── back.png        # Previous button icon
│   ├── next.png        # Next button icon
│   ├── picture.png     # Favicon
│   ├── image-1.png     # Gallery images
│   ├── image-2.png
│   ├── image-3.png
│   ├── image-4.png
│   ├── image-5.png
│   └── image-6.png
└── README.md           # Project documentation
```

## How to Run

1. Clone or download the repository
2. Open `index.html` in any modern web browser
3. Use the navigation buttons or mouse wheel to browse through images
4. Hover over images to see the interactive effects

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Customization

### Adding Images
1. Place your images in the `images/` directory
2. Update the HTML in `index.html` to include new image elements
3. Adjust the scroll distance in `script.js` if needed (currently set to 900px)

### Styling Modifications
- Colors and effects can be customized in `style.css`
- Grid layout can be adjusted for different numbers of images per row
- Animation timings and effects are easily modifiable

## Development

This project uses no build tools or package managers. Simply edit the files directly and refresh your browser to see changes.

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional features.

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
