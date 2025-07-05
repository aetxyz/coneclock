# 🕐 ConeClock

A simple web-based progress clock utility for tabletop gaming, inspired by the progress clocks from [Blades in the Dark](https://bladesinthedark.com/progress-clocks).

## What is ConeClock?

ConeClock helps Game Masters track ongoing situations, complex obstacles, and developing threats during tabletop RPG sessions. Whether you're running a heist where guards are getting suspicious, tracking a ritual's completion, or managing faction movements, ConeClock provides a visual way to represent progress that both you and your players can understand at a glance.

## Features

- **Visual Progress Tracking**: Create circular clocks with 2-24 segments
- **Customizable Colors**: Choose different colors for different types of clocks
- **Level System**: When a clock fills up, it automatically advances to the next level
- **Multiple Clocks**: Track several situations simultaneously
- **Clean Interface**: Minimal design that won't distract from your game
- **Instant Use**: No installation required - just open in your browser

## How to Use

1. **Open the file**: Simply open `index.html` in any modern web browser
2. **Create a clock**: Click the + button to open the creation panel
3. **Fill in details**: 
   - Give your clock a descriptive name
   - Choose how many segments (2-24)
   - Pick a color that makes sense for the situation
4. **Track progress**: Use the + and - buttons to fill or empty segments
5. **Level up**: When a clock fills completely, it automatically advances to the next level

## Examples in Play

**Stealth Mission**: Create a 6-segment "Guard Alert" clock. Each time the players make noise or act suspiciously, tick it up. When it fills, the guards are fully alerted and the situation escalates.

**Ritual Interruption**: The villain needs 8 segments to complete their dark ritual. Each round they're uninterrupted, tick it up. The players need to stop it before it completes!

**Faction War**: Create separate clocks for different factions' influence in the city. Advance them based on the players' actions and choices throughout the campaign.

## Technical Notes

- Pure HTML/CSS/JavaScript - no dependencies
- Works offline once loaded
- State is saved in browser local storage

## License

This project is released under CC0 1.0 Universal - see the LICENSE file for details.
