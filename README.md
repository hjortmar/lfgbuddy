# LFGBuddy

LFGBuddy addon is designed to help you find buddies for dungeon groups efficiently with an automated whisper queue using /who or a filter.

[Download LFGBuddy](https://github.com/hjortmar/lfgbuddy/raw/main/LFGBuddy.zip)

## ✨ Features and usage

  **Open the Who tab to see the LFGBuddy interface**
  
1. Choose your filter by class and level range.
<br>
2. Click "Refresh", this will send a /who command based on your filter and capture the result to a whisper queue.
   - If you write your own /who command, the whisper queue will then be built from that result as long as LFGBuddy is visible.
   - The whisper queue will not capture players in instances, on your ignore list and battlegrounds (optional). 
<br>
3. *(Optional)* Click "Whisper who?" to see to who the addon intends to send your message to.
<br>
4. Write a poem in the messagebox, this is the message that the addon will send to players when you click "Send".
   - Once you have sent a message, it will be saved for quick reuse.
<br>
5. Click "Send" to start sending messages to all players that were captured into the whisper queue.
   - Click "Pause" if you want the addon to stop sending messages.
   - Click "Reset" if you want the stop and clear the whisper queue.
   - By default, the addon is only able to send a message to a player once every 10 minutes to avoid being a nuissance.

## 🖼️ Screenshots
![Main](images/lfgbuddy-mainwindow.png)
![Whispers](images/lfgbuddy-spam.png)
![Options](images/lfgbuddy2.png)

## ⚙️ Installation

1. [Download LFGBuddy](https://github.com/hjortmar/lfgbuddy/raw/main/LFGBuddy.zip).
2. Extract in your `World of Warcraft\Interface\AddOns` directory.
3. Ensure the folder structure looks like this:
Interface\AddOns\LFGBuddy\LFGBuddy.toc
Interface\AddOns\LFGBuddy\Main.lua
4. Launch WoW and enable LFGBuddy on the character selection screen.

## 📝 Notes

LFGBuddy is only tested with a WotLK 3.3.5 (2009) client on **Epoch WoW 3.3.5**.  

## 📜 License

This addon is provided as-is. Modify and share freely, but please credit the original author.

