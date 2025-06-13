# Frogger Game

A modern recreation of the classic Frogger arcade game built with HTML5 Canvas and JavaScript.

## Features

- 🐸 Classic Frogger gameplay with pixel-perfect collision detection
- 🚗 Multiple lanes of traffic with varying speeds and directions
- 🏆 Level progression with increasing difficulty
- ❤️ Lives system (3 lives per game)
- 🎯 Score system with bonus points for forward movement
- ⌨️ Keyboard controls (Arrow keys or WASD)
- 🎮 Clean, responsive design optimized for viewport
- 🌙 Dark mode interface with accessibility considerations

## How to Play

1. Open `index.html` in your web browser
2. Click "Start Game" to begin
3. Use arrow keys or WASD to move the frog
4. Navigate through traffic lanes to reach the goal at the top
5. Avoid cars and reach the top safely to complete the level

## Controls

- **Arrow Keys** or **WASD**: Move the frog in four directions
- **Start Game**: Begin a new game
- **Restart**: Start over after game over
- **Next Level**: Proceed to the next level after completing current one

## Game Rules

- **Objective**: Guide the frog from the bottom to the top goal area
- **Scoring**: 
  - 10 points for each step forward
  - 100 points × level number for completing a level
- **Lives**: Start with 3 lives, lose one when hit by a car
- **Levels**: Each level increases car speed and difficulty
- **Safe Zones**: Bottom spawn area, middle rest area, and top goal area

## Game Layout

- **Goal Zone** (Top): Green area with "GOAL" text - reach here to win
- **Traffic Lanes**: 5 lanes with cars moving left and right
- **Safe Zone** (Middle): Green rest area between traffic
- **Spawn Zone** (Bottom): Starting position

## Technical Details

- Built with vanilla HTML5, CSS3, and JavaScript
- Uses Canvas API for smooth 60fps rendering
- 600x600 pixel game board with 50px grid system
- Real-time collision detection
- Progressive difficulty scaling
- Viewport-optimized design

## Development

This game was developed as part of the tyler-game-hub project, focusing on creating engaging single-player experiences with potential for multiplayer expansion.

## Future Enhancements

- Real-time multiplayer with WebSockets
- Ghost mode for watching other players
- Power-ups and special items
- Different vehicle types (trucks, motorcycles)
- Water levels with logs and turtles
- Leaderboards and high scores
- Mobile touch controls
- Sound effects and music