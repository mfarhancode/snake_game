# Screen-Wrapping Snake Game

A classic 2D Snake game built in Python using Object-Oriented Programming (OOP) and the native `turtle` graphics module.

## Features
- **Screen Wrapping:** Custom coordinate tracking teleports the snake's head to the opposite side of the screen instead of ending the game on wall impact.
- **Dynamic Growth:** Eating food automatically triggers new body segments to append at the snake's exact trailing position.
- **Object-Oriented Architecture:** Separate, decoupled modules manage gameplay state (`snake.py`), randomized item spawning (`food.py`), and live UI rendering (`scoreboard.py`).
- **Self-Collision Detection:** Continuously calculates distance vectors across all active segments to trigger a game-over if the snake hits its own tail.
