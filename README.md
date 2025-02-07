# Reflex Game

## Project Overview

This project involves the development of a two-player reflex game using the ATmega328P microcontroller. The game features an OLED display, 7-segment indicators, score tracking, adjustable timers, and a turn-based scoring system. The objective is to test and improve players' reaction times.

## Features

- **Two-Player Mode:** Players compete to achieve the highest score.
- **OLED Display:** Displays game status and instructions.
- **Score Tracking:** Keeps track of each player's score.
- **Adjustable Timers:** Configure reaction timing intervals.
- **Turn-Based System:** Players alternate turns for fair competition.

## Components Used

- **Microcontroller:** ATmega328P (8-bit AVR MCU, 32KB Flash, 2KB SRAM)
- **Display:** OLED Display (128x64 resolution)
- **7-Segment Indicators:** For player score display
- **Buttons:** Start, Player 1, and Player 2 controls
- **Power Supply:** 5V regulated supply

## File Structure

```
.
├── Debug/                     # Build files
├── ReflexGame.atsln           # Solution file
├── ReflexGame.cproj           # Project file
├── display.c                  # OLED display module source file
├── display.h                  # OLED display module header file
├── game_logic.c               # Game logic source file
├── game_logic.h               # Game logic header file
├── main.c                     # Main application code
├── timer.c                    # Timer configuration source file
├── timer.h                    # Timer configuration header file
├── gpio.c                     # GPIO module source file
├── gpio.h                     # GPIO module header file
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open `ReflexGame.atsln` in your preferred IDE.
3. Build and flash the project onto the ATmega328P microcontroller.
4. Connect the buttons and OLED display as per the schematic.
5. Power the circuit and start playing.

## How It Works

1. Players press their respective buttons as quickly as possible when prompted by the OLED display.
2. The system measures reaction time and updates the score.
3. The winner is determined by the player with the highest score after a set number of rounds.

## Dependencies

- Microchip Studio or similar IDE compatible with AVR MCUs
- OLED driver library (if needed)

## Future Improvements

- Add support for wireless communication between player stations
- Improve graphical interface on the OLED display
- Implement difficulty levels and game variations

## Contact

Developed by Davut Beyazkaya

For any questions, please reach out via [your contact email, if desired].

---

