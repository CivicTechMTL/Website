# Civic Tech Montréal Website

A bilingual (English/French) community website for Civic Tech Montréal — connecting residents, technologists, and designers to strengthen civic life in the city.

## Features

- 🌐 **Bilingual Support**: Full EN/FR language switcher with localStorage persistence
- 📱 **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- ✨ **Smooth Animations**: Scroll-triggered reveal animations for visual hierarchy
- 🎨 **Custom Design System**: Carefully crafted color palette and typography
- 📊 **Event Integration**: Embedded Luma calendar for event management
- 💬 **Community Links**: Direct connections to Slack, GitHub, and Luma

## Project Structure

```
CivicTechMontrealWebsite/
├── index.html          # Complete website (single-file for simplicity)
├── netlify.toml        # Netlify deployment config
├── README.md           # This file
```

## Quick Start

1. **Local Testing**:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Or Node.js
   npx http-server
   ```
   Then visit `http://localhost:8000`

2. **Deploy to Netlify**:
   - Connect your GitHub repo to Netlify
   - Netlify will auto-detect `netlify.toml`
   - Push to `main` branch to deploy

## Configuration

### Language Switcher
The site defaults to English. Language preference is saved in localStorage as `civic-tech-lang`.

### Contact Email
Update the contact link in the footer (currently: `hello@civictechmontreal.org`)

### Color Scheme
CSS variables defined in `:root`:
- `--teal`: Primary color
- `--ink`: Text color
- `--bg`: Background
- See `<style>` block for full palette

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

This is an open-source project. Contributions are welcome! Please:
1. Test on both languages (EN/FR)
2. Check mobile responsiveness
3. Maintain accessibility standards

## License

Open source always — [add specific license here]
