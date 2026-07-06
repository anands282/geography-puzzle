# How to Run Geography Puzzle

## Quick Start

### Option 1: Direct Browser (Easiest)
1. Clone or download the repository
2. Open `index.html` directly in your browser
   - On Windows: Double-click `index.html`
   - On Mac: Right-click → Open With → Your Browser
   - On Linux: `xdg-open index.html`

### Option 2: Local Server (Recommended)

#### Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Using Node.js:
```bash
npx http-server
```

#### Using Ruby:
```bash
ruby -run -ehttpd . -p8000
```

Then open your browser and visit:
- `http://localhost:8000`
- `http://127.0.0.1:8000`

### Option 3: GitHub Pages (Free Hosting)
1. Go to your repository settings
2. Enable GitHub Pages
3. Set branch to `main`
4. Your app will be live at: `https://anands282.github.io/geography-puzzle`

## Game Flow

```
Start
  ↓
Level Selection
  ├─→ World Level → Puzzle Game (arrange 6 continents)
  ├─→ Continent Level → Select Continent → Puzzle Game (arrange countries)
  └─→ Country Level → Select Country → Puzzle Game (arrange states)
  ↓
Drag & Drop pieces
  ↓
All pieces placed → Completion message ✨
```

## Browser Compatibility
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Android)

## What You'll See

### Screen 1: Level Selection
```
🌍 Geography Puzzle
Learn world geography through interactive puzzles

[🌎 World]  [🏔️ Continent]  [🏛️ Country]
```

### Screen 2: Drag & Drop Puzzle
```
Left Side (Outline):          Right Side (Pieces):
     🌍                        🌎 Africa  🌎 Asia
                              🌎 Europe  🌎 N.America
                              🌎 S.America  🌎 Oceania

Progress: ████░░░░░░ 2/6 pieces placed
```

### Screen 3: Completion
```
🎉 Puzzle Complete!
Great job! You've successfully completed the puzzle.
[← Back to Levels]
```

## Features Included
✅ Drag and drop interface
✅ Touch support for mobile
✅ Real-time progress tracking
✅ Responsive design (works on all devices)
✅ Multiple difficulty levels
✅ Smooth animations
✅ Reset puzzle button
✅ Back navigation

## Next Steps for Enhancement
- Add actual SVG maps
- Import GeoJSON for accurate borders
- Add difficulty levels with hints
- Create scoring system
- Add sound effects
- Save progress to localStorage
