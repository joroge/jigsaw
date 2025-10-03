# Sliding Puzzle Game - README

## 🧩 Overview

The Sliding Puzzle Game is an interactive web-based puzzle game where players can upload their own images and solve them as sliding puzzles. This project combines classic puzzle mechanics with modern web technologies to create an engaging user experience.

## ✨ Features

- **Custom Image Upload**: Drag and drop or click to upload any image
- **Multiple Difficulty Levels**: 3×3, 4×4, 5×5, and 6×6 grid sizes
- **Real-time Statistics**: Track moves and completion time
- **Visual Feedback**: Highlighting, animations, and confetti celebration
- **Responsive Design**: Works on desktop and mobile devices
- **Game Controls**: Shuffle, reset, and difficulty selection
- **Original Image Preview**: See the target image while solving

## 🚀 How to Use

1. **Upload an Image**: Click the upload area or drag and drop an image file
2. **Select Difficulty**: Choose from 3×3 (easy) to 6×6 (challenging)
3. **Start Playing**: Click the "Shuffle Puzzle" button to begin
4. **Solve the Puzzle**: Click tiles adjacent to the empty space to move them
5. **Track Progress**: Monitor your moves and time in the statistics panel
6. **Celebrate**: Enjoy the confetti animation when you complete the puzzle!

## 🛠️ Technical Implementation

### HTML Structure
- Semantic HTML5 elements for accessibility
- Responsive layout with flexbox and grid
- Proper meta tags for SEO and mobile optimization

### CSS Features
- CSS custom properties (variables) for consistent theming
- Responsive design with mobile-first approach
- Smooth transitions and animations
- Confetti animation using pure CSS

### JavaScript Functionality
- Image processing and puzzle generation
- Game state management
- Move validation and puzzle solving logic
- Timer and move counter functionality
- Drag and drop file upload support

## 🎮 Game Mechanics

- The puzzle consists of a grid with one empty space
- Players move adjacent tiles into the empty space
- The goal is to reconstruct the original image
- The game tracks the number of moves and completion time
- Puzzle is automatically checked for completion after each move

## 📱 Browser Compatibility

This game works on all modern browsers including:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🔧 Customization

The game can be easily customized by modifying the CSS variables in the `:root` selector:

```css
:root {
    --primary-color: #4a6fa5;
    --secondary-color: #6b8cbc;
    --accent-color: #ff6b6b;
    /* Add your own color scheme */
}
```

## 🔮 Future Enhancements

- Leaderboard system with local storage
- Additional puzzle patterns and shapes
- Save/load game functionality
- Social sharing capabilities
- Puzzle solver algorithm demonstration
- Sound effects and background music

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

*Inspired by Dr. Chao Mbogo's interest in creating a puzzle out of any art piece

This sliding puzzle game embodies this philosophy by providing an interactive platform where users don't just solve puzzles, but create their own from personal images, transforming abstract problem-solving into a meaningful, personalized experience.

---

**Developed with ❤️ for puzzle enthusiasts and lifelong learners**
