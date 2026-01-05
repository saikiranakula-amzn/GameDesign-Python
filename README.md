# Python Game Collection

A collection of classic games implemented in Python using SimpleGUI, originally developed in 2014.

## Games Included

### 🚀 Asteroids (RiceRocks)
Navigate your spaceship through an asteroid field, shooting asteroids while avoiding collisions.

### 🏓 Pong
Classic two-player paddle game where players hit a ball back and forth.

### 🃏 BlackJack
Digital implementation of the classic BlackJack card game against a dealer.

### 🧠 Memory Game
Concentration-style memory game where you match pairs of cards.

## Quick Start

### Prerequisites
- Python 3.6 or higher
- pip (Python package installer)

### Installation

1. Clone or download this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running Games

Each game can be run independently:

```bash
# Asteroids
cd games/asteroids
python main.py

# Pong
cd games/pong
python main.py

# BlackJack
cd games/blackjack
python main.py

# Memory Game
cd games/memory
python main.py
```

## Project Structure

```
├── games/
│   ├── asteroids/
│   │   ├── main.py
│   │   └── README.md
│   ├── pong/
│   │   ├── main.py
│   │   └── README.md
│   ├── blackjack/
│   │   ├── main.py
│   │   └── README.md
│   └── memory/
│       ├── main.py
│       └── README.md
├── requirements.txt
├── .gitignore
└── README.md
```

## Technical Details

- **Language**: Python 3.6+
- **GUI Framework**: SimpleGUI (with SimpleGUICS2Pygame for desktop compatibility)
- **Original Platform**: CodeSkulptor (online Python environment)
- **Desktop Compatibility**: Achieved through SimpleGUICS2Pygame wrapper

## Dependencies

All games use the SimpleGUICS2Pygame library, which provides desktop compatibility for games originally written for CodeSkulptor's SimpleGUI. The games automatically handle the import fallback.

## Development Notes

These games were originally developed for the CodeSkulptor online Python environment. The SimpleGUICS2Pygame library allows them to run on desktop Python installations while maintaining the original SimpleGUI API.

## License

Educational project - feel free to use and modify for learning purposes.

## Contributing

This is a historical project from 2014. While not actively maintained, feel free to fork and improve upon the games for your own learning and enjoyment.
