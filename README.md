# Nebula Crisis: Overlord Showdown

## Overview

**Nebula Crisis: Overlord Showdown** is a web-based terminal game set aboard an intergalactic spaceship that has been 
overrun by a deadly Alien Overlord. As the player, your mission is to explore the ship, gather critical items, and 
activate the ship’s defense system before the Alien Overlord catches you. Each playthrough is unique due to randomized 
starting positions, item locations, and the alien’s whereabouts, ensuring unpredictability and replayability.

This game is hosted on AWS and utilizes GateOne to provide an immersive terminal-based gameplay experience accessible 
via any modern web browser.

## Gameplay

You begin the game in a random room on the spaceship, while the Alien Overlord starts in another room. Your objective
is to navigate through different rooms, collect six essential items, and activate the ship’s defense system before
encountering the Alien Overlord.

The six essential items are:

- Power Cell
- Shield Generator
- Command Keycard
- Energy Converter
- Nano Repair Kit
- Laser Cannon Blueprint

The location of these items, as well as the Alien Overlord, will change with every playthrough. If you encounter the
Alien Overlord before collecting all the necessary items, you will be defeated, and the game will end.

### Clues and Danger:

- As you explore the spaceship, you may receive hints if the Alien Overlord is in an adjacent room. Pay attention to
  these clues to avoid entering dangerous areas unprepared!

## Features

- Web-based Terminal Interface: Play the game via a terminal emulation accessible through any web browser, offering an 
- authentic command-line experience powered by GateOne and hosted on AWS.
- **Randomized Start and Item Locations**: Both your starting point and the location of the essential items and the
  Alien Overlord are randomized with each new game, ensuring replayability and unpredictability.
- **Item Collection**: Explore different rooms on the spaceship to collect the essential items.
- **Replayability**: Each playthrough is different, adding a layer of challenge and excitement as you explore the ship.

## Installation (for Local Development)

1. Clone this repository to your local machine using:
   ```bash
   git clone https://github.com/yourusername/nebula-crisis.git
   ```

2. Navigate to the project directory:
    ```bash
    cd nebula_crisis
    ```

3. Run the game:
    ```bash
    python main.py
    ```

## AWS Deployment and GateOne Integration

This project is hosted on AWS, utilizing GateOne to provide terminal-based gameplay accessible via the web. Follow 
these steps to deploy the game on AWS:

1. Set up an AWS EC2 instance and install the necessary Python dependencies.
2. Install and configure GateOne for terminal emulation.
3. Deploy the game code to the server and ensure the game runs properly within the GateOne interface.
4. Access the game via the provided URL to experience Nebula Crisis: Overlord Showdown in your web browser.

## How to Play

1. Move between rooms: Use simple commands like go north, go south, go east, and go west to navigate through the ship.
2. Collect items: When you enter a room containing one of the essential items, use the take item command to collect
   it.
3. Check inventory: Type inventory at any time to see which items you’ve collected.
4. Avoid the Alien Overlord: If you enter the Alien Overlord’s location before collecting all six items, you will be
   defeated, and the game will end.
5. Win condition: Once all six items have been collected, the ship’s defense system will activate, and you’ll
   successfully defeat the Alien Overlord.

## Game Commands

- Movement:
    - go [direction] – Moves the player to a new room. (e.g., go north)
- Item Management:
    - get [item] – Collects the item in the current room.
    - inventory – Shows a list of all collected items.
- Quit:
    - exit – Ends the game.

## Rooms in the Game

- Crew Quarters
- Control Room
- Storage Bay
- Observation
- Engine Room
- Medical Bay
- Weaponry Room
- Cargo Hold

These rooms will be explored as you attempt to find the six critical items while avoiding the Alien Overlord.

## Future Enhancements

- Adding more rooms and challenges.
- Implementing a combat system for direct confrontation with the Alien Overlord.
- Adding different types of aliens for increased difficulty.
- Introducing a health or stamina system for the player.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE.md) file for details.

## Contact

For questions, suggestions, or bug reports, please contact:

Rick Goshen
Email: rick.goshen@gmail.com
GitHub: https://github.com/rickgoshen
