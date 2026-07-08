# Blackjack (Python + Pygame)

A graphical Blackjack card game built as a course project, implemented in
Python with Pygame. The project covers full game logic, card dealing and
animation, sound effects, and automated tests for the core rules.

## Tech Stack
Python 3.8+ · Pygame

## Features
- Full deck creation, shuffling, and dealing logic (`blackjack_deck.py`)
- Card movement animations (`card_animation.py`)
- Score counting and win/loss determination
- Sound effects for player actions (card flip, deal)
- Automated tests for game rules (`test_blackjack.py`)

## Project Structure
```
├── blackjack_pygame.py   # Entry point — runs the game
├── blackjack_deck.py      # Deck creation & management
├── card_animation.py       # Card movement animation
├── constants.py            # Colors, sizes, fonts
├── img/                     # Card and background images
├── sounds/                  # Sound effects
└── test_*.py                # Unit tests
```

## Getting Started
```bash
git clone https://github.com/AndriiYefremov123/blackjack-pygame.git
cd blackjack-pygame
pip install pygame
python blackjack_pygame.py
```

## Author
Andrii Yefremov — Computer Science student, Łódź University of Technology
