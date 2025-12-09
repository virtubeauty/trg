# Triggen Website

A simple, clean, and modern landing page for Triggen NFT project with token launch integration on Virtuals.io.

## Features

- **Clean Design**: Minimalist and modern UI with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Token Launch Integration**: Direct links to Virtuals.io token launch
- **Project Purpose**: Clear explanation of the project's mission and goals
- **Fast Loading**: Pure HTML/CSS/JavaScript with no heavy frameworks

## Structure

- `index.html` - Main landing page
- `styles.css` - All styling and responsive design
- `script.js` - Interactive features and animations
- `README.md` - Project documentation

## Customization

### Update Project Launch Link

Edit `script.js` and update the `launchUrl` variable in the project launch button handler:

```javascript
const launchUrl = 'YOUR_LAUNCH_URL_HERE';
```

### Update Social Media Links

Edit the footer section in `index.html` to add your social media links:

```html
<a href="YOUR_TWITTER_URL" target="_blank" aria-label="Twitter">Twitter</a>
<a href="YOUR_DISCORD_URL" target="_blank" aria-label="Discord">Discord</a>
<a href="YOUR_TELEGRAM_URL" target="_blank" aria-label="Telegram">Telegram</a>
```

### Customize Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... */
}
```

## Usage

Simply open `index.html` in a web browser or deploy to any static hosting service.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2026 Triggen. All rights reserved.

