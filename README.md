# Godot-Inventory-System

A comprehensive and interactive inventory system for Godot Engine, featuring item drops, tool management, and a robust inventory UI. This project demonstrates an in-depth approach to handling items in a game environment, from picking up and managing various items to using tools and managing an inventory UI.

## Overview

The project is structured around several key scripts, each contributing to the functionality of the inventory system:

- **RandomLoot**: Manages the random generation of loot items based on rarity percentages, providing a weighted loot table functionality.
- **ItemResource**: Defines the properties of in-game items, including type, stackability, and associated resources like icons and tools.
- **Toolbar**: Manages the player's toolbar, allowing for the selection and use of different tools and items within the game.
- **Drop**: Handles the dropping of items in the game world, allowing players to collect them.
- **Inventory**: Manages the storage, addition, swapping, and removal of items in the player's inventory.

### Features

- **Weighted Item Drops**: Items drop based on a weighted system, where item rarity influences the likelihood of an item drop.
- **Dynamic Inventory Management**: Add, swap, and remove items dynamically from the inventory.
- **Tool and Item Use**: Equip and use tools from the inventory, with support for different item types like consumables and resources.
- **Customizable UI**: The inventory system comes with a customizable UI, adaptable to different game styles and requirements.
- **Robust Item Definition**: Items are defined with various attributes, including stack size, type, and visual representation.

## Getting Started

To use this inventory system in your Godot project, follow these steps:

1. Clone this repository or download the project files.
2. Open the project in Godot Engine.
3. Explore the scripts to understand the structure and functionality of the inventory system.

## Usage

- **Inventory Management**: Use the `Inventory` script to manage in-game items.
- **Item Interaction**: Implement the `RandomLoot` and `Drop` scripts to handle item drops and collection.
- **Tool Usage**: Utilize the `Toolbar` script to manage the player's toolbar and tool usage in the game.

## Contributing

Contributions to improve the inventory system, add new features, or optimize existing functionality are welcome. Feel free to fork this repository and submit your improvements or new ideas.

---
