# Word Search Quest 🔤

A modern, vibrant Android word search puzzle game with neon-styled UI and engaging gameplay mechanics.

## 🎮 Game Overview

Word Search Quest is an interactive word puzzle game where players find hidden words in a grid of letters. The game features a colorful neon aesthetic, smooth animations, and intuitive touch controls.

### Key Features

- 🌈 **Unique Color System** - Each found word is highlighted with a different vibrant color
- 🎯 **Smart Selection** - Clean rounded rectangle highlighting for horizontal, vertical, and diagonal word selections
- 💡 **Hint System** - 2 hints per level with automatic word selection animation
- 📊 **Progress Tracking** - Visual progress indicators and score system
- 🎵 **Themed Levels** - Music-themed words like GUITAR, POP, JAZZ, DRUM, HARP, MOONWALK
- 📱 **Responsive Design** - Optimized for various Android screen sizes
- 🎨 **Modern UI** - Neon color scheme with smooth animations and rounded design elements

## 🚀 Installation

### Method 1: Install Pre-built APK

1. **Download the APK**
   - Get the latest `app-debug.apk` from the releases section
   - File size: ~6.5 MB

2. **Enable Unknown Sources**
   - Go to Settings → Security → Unknown Sources (enable)
   - Or Settings → Apps & Notifications → Special App Access → Install Unknown Apps

3. **Install**
   - Transfer APK to your Android device via USB, email, or cloud storage
   - Open file manager and tap the APK file
   - Follow installation prompts

### Method 2: Build from Source

```bash
# Clone the repository
git clone https://github.com/Csprajwal/Word-Search-Quest
cd word-search-quest

# Build debug APK
./gradlew assembleDebug

# APK will be generated at: app/build/outputs/apk/debug/app-debug.apk
```

## 🎯 How to Play

1. **Select Words**: Touch and drag across letters to select words
2. **Find All Words**: Locate all hidden words shown in the word list at the bottom
3. **Use Hints**: Tap the hint button (2 available per level) for automatic word selection
4. **Track Progress**: Found words appear as colored pills in the header
5. **Complete Level**: Find all words before time runs out

### Game Controls

- **Touch & Drag**: Select words in any direction (horizontal, vertical, diagonal)
- **Hint Button**: Auto-selects a random unfound word
- **Pause Button**: Pause/resume game timer
- **Back Button**: Return to level selection

## 📱 Screenshots

### Game Interface
- **Header**: Level info, score, timer, and found words display
- **Grid**: Interactive letter grid with colorful word highlighting  
- **Word List**: Shows all words to find with fade effect when found
- **Controls**: Hint, pause, and navigation buttons

### Color System
- 🟢 First word: Neon Green
- 🔵 Second word: Neon Blue  
- 🟣 Third word: Neon Pink
- 🟡 Fourth word: Neon Yellow
- 🟪 Fifth word: Neon Purple
- 🟠 Sixth word: Neon Orange
- And more vibrant colors for additional words!

## 🛠️ Technical Details

### Built With
- **Language**: Java
- **Platform**: Android (API 21+)
- **Build System**: Gradle
- **Architecture**: Custom Views with Canvas drawing
- **Dependencies**: AndroidX libraries

### Project Structure
```
app/src/main/
├── java/com/example/wordsearchquest/
│   ├── GameActivity.java          # Main game logic
│   ├── WordGridView.java          # Custom grid view with touch handling
│   ├── LevelManager.java          # Level data management
│   ├── WordListAdapter.java       # Word list RecyclerView adapter
│   ├── FoundWordsAdapter.java     # Found words display adapter
│   └── WordGridGenerator.java     # Grid generation algorithm
├── res/
│   ├── layout/                    # XML layouts
│   ├── values/                    # Colors, strings, styles
│   └── drawable/                  # UI graphics and backgrounds
└── assets/
    └── *.json                     # Level data files
```

### Key Classes

- **`WordGridView`**: Custom view handling word selection, highlighting, and touch events
- **`GameActivity`**: Main game controller managing timer, scoring, and UI updates  
- **`LevelManager`**: Handles level progression, scoring, and data persistence
- **`WordGridGenerator`**: Generates word grids and places words in various directions

## 🎨 Design Features

### Visual Elements
- **Neon Color Palette**: Vibrant colors with transparency effects
- **Rounded Corners**: Consistent rounded rectangle design throughout
- **Smooth Animations**: Word selection, found word celebrations, and UI transitions
- **Modern Typography**: Clean, readable fonts with proper contrast

### UI Components
- **Header Bar**: Level title, hint button, pause functionality
- **Stats Display**: Score, timer, and progress indicators
- **Found Words Pills**: Colorful horizontal scrolling display
- **Word Grid**: Interactive letter grid with smart highlighting
- **Word List**: Bottom panel showing all target words with fade states

## 🔧 Development

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK API 21+
- Java 8+

### Setup Development Environment
```bash
# Clone repository
git clone https://github.com/MdZaheen/word-search-quest.git

# Open in Android Studio
# Sync project with Gradle files
# Run on device or emulator
```

### Building
```bash
# Debug build
./gradlew assembleDebug

# Release build
./gradlew assembleRelease

# Run tests
./gradlew test
```

## 📝 Game Mechanics

### Word Placement Algorithm
- Words can be placed horizontally, vertically, or diagonally
- Random letter filling for remaining grid spaces
- Ensures all words are findable and don't overlap incorrectly

### Scoring System
- **+10 points** per word found
- **+5 points per second** remaining as time bonus
- Progressive difficulty increases potential scores

### Hint System
- **2 hints per level**
- Automatic word highlighting and selection
- Visual animation shows word location
- Hint counter decreases with usage

## 🎵 Level Themes

### Level 1: Music Theme
- GUITAR, POP, JAZZ, DRUM, HARP, MOONWALK
- 8x8 grid, 5 minute time limit

### Future Themes
- Sports, Animals, Food, Technology, Nature
- Increasing grid sizes and word counts
- Special challenge levels

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow Java coding conventions
- Add comments for complex algorithms
- Test on multiple screen sizes
- Maintain consistent UI/UX patterns

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic word search puzzles
- Neon design aesthetic influenced by modern mobile game trends
- Built with Android's powerful Canvas and Paint APIs

## 📞 Contact

- **Developer**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [@yourusername](https://github.com/MdZaheen)

---

⭐ **Star this repository if you found it helpful!**

🐛 **Found a bug or have a feature request?** [Open an issue](https://github.com/MdZaheen/word-search-quest/issues)
