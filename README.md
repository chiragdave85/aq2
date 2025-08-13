# My Personal Homepage

A simple, elegant personal homepage built with HTML and CSS featuring a modern glass morphism design.

## Features

- **Beautiful Blue Gradient Background**: Diagonal gradient from blue to purple for a modern look
- **Responsive Design**: Adapts seamlessly to different screen sizes and devices
- **Glass Morphism UI**: Semi-transparent container with backdrop blur effects
- **Circular Profile Photo**: Perfect circle crop for your profile image
- **Interactive Elements**: Smooth hover animations and transitions
- **Clean Typography**: Easy-to-read fonts with proper spacing

## Files Structure

```
my-homepage/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with all CSS rules
└── README.md          # This file
```

## Getting Started

1. **Clone or download** this repository to your local machine
2. **Add your photo**:
   - Place your photo file in the same directory as `index.html`
   - Edit `index.html` and uncomment the `<img>` tag in the profile photo section
   - Update the `src` attribute with your photo filename (e.g., `"my-photo.jpg"`)
   - Remove or comment out the placeholder text
3. **Open `index.html`** in your web browser

## Customization

### Adding Your Photo
```html
<!-- In index.html, replace this: -->
<span>Add Your Photo Here</span>

<!-- With this: -->
<img src="your-photo.jpg" alt="Your Name">
```

### Customizing Colors
Edit `styles.css` to change:
- **Background gradient**: Modify the `background` property in the `body` selector
- **Button colors**: Update the `background` property in the `.contact-button` selector
- **Container styling**: Adjust colors in the `.container` selector

### Updating Content
- **Name/Title**: Edit the `<h1>` tag in `index.html`
- **Description**: Modify the `<p>` tag content
- **Button text**: Change the text inside the `<button>` element

## Browser Compatibility

This homepage works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients, backdrop filters, and flexbox
- **Vanilla JavaScript**: Simple button interaction

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

Feel free to customize this homepage to make it your own!
