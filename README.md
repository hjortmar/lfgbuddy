# LFGBuddy

LFGBuddy is a lightweight World of Warcraft addon designed for **Epoch WoW 3.3.5 (Wrath of the Lich King)**. It helps you manage and automate your `/who` queries, whisper queues, and group finding so you can connect with players efficiently.

## Features

- **Custom /who Queries** – Filter by class, level range, and location.
- **Queue Whispers** – Automatically send messages to players matching your criteria.
- **Lock to Who Frame** – Position LFGBuddy next to the Who tab for easy access.
- **City and PvP Filtering** – Restrict your queue to players in cities or avoid PvP zones.
- **Spam Lockout** – Avoid repeatedly messaging the same players within a configurable time frame.
- **Recent Messages** – Keep track of recently sent messages for quick reuse.
- **Toggle Addon Notifications** – Enable or disable chat messages from LFGBuddy.
- **Save/Reset Settings** – Persistent configuration between sessions, with buttons to reset defaults or queues.

## Installation

1. Download the `LFGBuddy` folder.
2. Place it in your `World of Warcraft\Interface\AddOns` directory.
3. Ensure the folder structure looks like this:
Interface\AddOns\LFGBuddy\LFGBuddy.toc
Interface\AddOns\LFGBuddy\Main.lua
4. Launch WoW and enable LFGBuddy on the character selection screen.

## Usage

- **Command:** `/lb show`  
Opens the LFGBuddy interface. If “Lock to Who” is enabled, it will position itself next to the Who tab.  

- **Options Tab:**  
- Enable/disable features like city-only queues, PvP zone filtering, spam lockout, and addon notifications.  
- Reset queues and recent messages.  
- Adjust spam lockout time with the slider.  

- **Main Tab:**  
- Choose your class and level range for `/who` queries.  
- Set and reuse messages to whisper queued players.  
- Refresh Who results and start/stop sending whispers.

## Configuration

LFGBuddy saves your settings in `LFGBuddyOptions`. Key options include:

| Option                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `queueCitiesOnly`              | Only include players in default cities.                                     |
| `togglePvPZones`               | Exclude players in PvP zones from the queue.                                 |
| `ignoreRecipientLockout`       | Ignore the lockout timer when sending whispers.                              |
| `spamLockoutMins`              | Time in minutes before a player can be whispered again.                     |
| `recentMessageRecipients`      | Tracks recent recipients to prevent spam.                                    |
| `disableAddonNotifications`    | Suppress LFGBuddy messages in chat.                                          |
| `lockToWho`                    | Lock the frame next to the Who tab.                                          |
| `showOnWho`                    | Auto-show LFGBuddy when opening the Who tab.                                 |

## Notes

- LFGBuddy is optimized for **Epoch WoW 3.3.5**; some features may not work in newer versions.  
- Messages and queues are **local to your character**.  
- LFGBuddy respects Blizzard’s API and automatically filters players already in your ignore list.

## License

This addon is provided as-is. Modify and share freely, but please credit the original author.

