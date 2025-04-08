# Ming Network

All-in-one Minecraft plugin based on the Spigot API, bringing multiple games into a single server. Designed for seamless gameplay, this plugin ensures an engaging experience with various game modes and custom mechanics.

> [!WARNING]
> This repository is for **reading purposes only**. No code is shared. More info in [License](#License-).

> However, you can join the related server to see the result.
> IP address : `mingnetwork.feathermc.gg`. Minecraft Version : `1.21`.

## What I Learned from Developing This Plugin
- Using `.yml` files to **store data persistently** between server restarts.
- Making API requests to **communicate with Minecraft servers**, such as retrieving player skins.
- Developing plugins with a focus on **user experience**.
- Learning and improving my skills in the **Java programming language**.

## Games Included

### 🏹 BattleBox
- 12 players fight on randomly selected maps.
- Kits are chosen in the first round, containing custom items (Boosts, Time Machine, Grenades, etc.).

### 🏃‍♂️ Manhunt
- One or more **Runners** must either complete the game by killing the Ender Dragon or survive.
- **Hunters** must stop them before they succeed.

### 🐺 Wolf Game
- A certain number of Wolves are randomly selected among players.
- Killing a Sheep swaps the roles between Wolf and Sheep.
- Wolves lose if they do not eliminate all Sheep before time runs out.

### 🛏️ BedWars
- Each player has a bed, allowing respawn upon death.
- Destroying an opponent's bed removes their ability to respawn.
- The last player standing wins the game.

### 🎲 Random Item Challenge
- Players receive a random item every **n** seconds in a default world.
- Players can fight using the items they get.
- The last player alive wins.

### ⚔️ Arena
- Players can create their own **Arenas**.
- They can design their own **Kits**.
- Players can invite others into their Arena for duels and battles.

## Features
- **Smart Inventory Management:** Players’ item slot preferences are saved even after server restarts, providing a smoother gaming experience.
- **Pause System:** Players can pause the game they are currently in.
- **Crash & Disconnection Recovery:** Some games support automatic state saving in case of an unexpected crash or disconnection, ensuring fair play when the player returns.
- **Dynamic Interfaces (GUI):** Custom graphical interfaces allow players to quickly configure the plugin, kits, and game maps without using commands.
- **Command Autocompletion:** All commands are fully integrated with a TabCompleter, making it easier for players to access them without needing to remember exact syntax.

## Upcoming Features 🚀
- **Rank System:** A structured ranking system for all players.
- **In-game Store:** Buy cosmetics, ranks, and more to help fund the server.
- **Unique New Games:** Exclusive game modes never seen before on European Minecraft servers.

## License ❌
**No License Provided** – This software is protected by copyright. No code is shared.
However, you can join `mingnetwork.feathermc.gg` in 1.21 to see the result.

For any inquiries regarding licensing or access, please contact me.

