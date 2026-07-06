# Geography Puzzle

An interactive world geography puzzle game where players solve puzzles at different levels: world, continent, country, or state.

## Features

- **Multiple Difficulty Levels**
  - World Level: Arrange all continents
  - Continent Level: Select a continent, then arrange its countries
  - Country Level: Select a country and continent, then arrange its states/regions
  - State Level: Select a country, then arrange states within that country

- **Interactive Gameplay**
  - Drag and drop puzzle pieces
  - Real-time feedback on correct placement
  - Progress tracking

## Project Structure

```
geography-puzzle/
├── index.html          # Main entry point
├── styles/
│   └── style.css       # Styling
├── js/
│   ├── main.js         # Main app logic
│   ├── puzzle.js       # Puzzle game logic
│   ├── ui.js           # UI interactions
│   └── data.js         # Geographic data
├── assets/
│   ├── svg/            # SVG map shapes
│   └── data/           # GeoJSON files
└── README.md
```

## Getting Started

1. Clone the repository
2. Open `index.html` in a web browser
3. Select your puzzle level and begin!

## Technologies

- HTML5
- CSS3
- JavaScript (Vanilla)
- SVG for map shapes
- GeoJSON for geographic data

## Development

Run a local server:
```bash
python -m http.server 8000
# or
npx http-server
```

Visit `http://localhost:8000`
