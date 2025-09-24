# NeedScope Visualization

An interactive pie chart visualization showing different territories of freshness needs, built with vanilla HTML, CSS, and JavaScript.

## 🎯 Overview

NeedScope displays 6 territories of freshness:
- **Playful Freshness** - Fun, novelty, flavor, variety
- **Invigorating Freshness** - Switch-on energy, alertness, stamina
- **Elevated Freshness** - Curated, ritual, sophistication, aesthetic
- **Focused Freshness** - Problem-solver, control, precision, efficacy
- **Calming Freshness** - Balance, wellbeing, mindfulness
- **Comforting Freshness** - Safety, protection, reassurance, worry-free

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone <your-repo-url>
cd needscope-visualization

# Install dependencies
npm install
```

### Development
```bash
# Start development server
npm run dev
# Opens http://localhost:3000

# Alternative simple server
npm run serve
# Opens http://localhost:8080
```

### Build & Deploy
```bash
# Build for production
npm run build

# Format code
npm run format

# Lint JavaScript
npm run lint
```

## 📁 Project Structure

```
needscope-visualization/
├── index.html          # Main visualization page
├── package.json        # Dependencies & scripts
├── .eslintrc.json     # ESLint configuration
├── .prettierrc        # Prettier configuration
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## 🎨 Features

- **Interactive SVG pie chart** with elliptical wedges
- **Smooth hover animations** with scaling and shadow effects
- **Click-to-expand panels** showing detailed needs for each territory
- **Responsive design** with modern CSS styling
- **Color-coded territories** with themed visual identity

## 🐛 Known Issues

1. **No panel close functionality** - Panels remain open once clicked
2. **Missing accessibility features** - No keyboard navigation or screen reader support
3. **Empty territory data** - Calming Freshness has no needs listed
4. **Hard-coded dimensions** - Not fully responsive on all screen sizes
5. **Color inconsistency** - Wedge colors don't match the data palette

## 🛠️ Technical Details

- **Vanilla JavaScript** - No external frameworks
- **SVG-based visualization** - Scalable and crisp rendering
- **CSS3 animations** - Smooth transitions and hover effects
- **Modern ES6+** - Arrow functions, const/let, template literals

## 📊 Data Structure

The visualization uses a JSON data structure with:
- **Meta information** - Title, version
- **Style configuration** - Theme, colors, fonts
- **Layout settings** - Canvas size, pie dimensions
- **Territory definitions** - Labels, angles, colors, needs

## 🎯 Usage

1. **View territories** - The pie chart displays all 6 freshness territories
2. **Hover for preview** - Wedges scale and highlight on hover
3. **Click to explore** - Click any wedge to see detailed needs in the side panel
4. **Visual feedback** - Color-coded separators and smooth animations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔧 Development Notes

- Uses CSS custom properties for theming
- SVG paths generated dynamically with JavaScript
- Elliptical pie chart for better visual proportion
- Modern CSS with backdrop-filter and drop-shadows
- Optimized for Chrome/Safari (webkit features)

---

**Built with ❤️ for data visualization**