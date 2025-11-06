# Tombola - Italian Bingo

A simple web-based Italian Tombola (Bingo) game with win tracking functionality.

This code is mostly AI generated.

## Features

- 📋 **6 Bingo Cards** with numbers 1-90 distributed across them
- 🎯 **Click to Extract** - Click on any number to mark it as extracted
- 📜 **Extraction History** - View all extracted numbers in reverse chronological order
- 🏆 **Win Tracking** - Track predefined wins (Ambo, Terna, Quaterna, Cinquina, Tombola)
- ➕ **Custom Wins** - Add your own custom win types
- 🎊 **Confetti Animation** - Celebrate when Tombola is checked
- 💾 **Auto-Save** - Game state is automatically saved to localStorage
- 🔗 **Shareable Links** - Share game state via URL parameters
- 🎨 **Customizable Colors** - Use URL parameter to change the extraction color

## Getting Started

Simply open `index.html` in a web browser. No build process or dependencies required!

## How to Use

### Extracting Numbers
- Click on any number to mark it as extracted
- Click again to unmark it
- Extracted numbers appear in the history on the right sidebar

### Managing Wins
- Check off wins as they occur
- Add custom wins using the input field at the bottom of the sidebar
- Delete custom wins by clicking the × button next to them

### Resetting the Game
- Click the "Reset" button to clear all extracted numbers and wins

### Customizing Colors
Add a `color` parameter to the URL with a hex color code (without #):
```
index.html?color=e74c3c
```

### Sharing Game State
The game state is automatically encoded in the URL, so you can share your current game by copying the URL from your browser's address bar.

## Technical Details

- **Pure JavaScript** - No frameworks or libraries required
- **Responsive Design** - Works on desktop and mobile devices
- **LocalStorage** - Game state persists across browser sessions
- **URL State Management** - Share game state via URL parameters

## File Structure

```
├── index.html    # Main HTML structure
├── style.css     # Styling and animations
└── app.js        # Game logic and state management
```

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- CSS Grid
- LocalStorage API

