# LFGBuddy

LFGBuddy addon is designed to help you find buddies for dungeon groups efficiently with an automated whisper queue using /who or a filter.

[Download LFGBuddy](https://github.com/hjortmar/lfgbuddy/raw/main/LFGBuddy.zip)

## 📖 Usage

1. Open the Who tab.

  **From the LFGBuddy interface:**
  
2. Choose your filter by class and level range.
   
3. Click "Refresh" to send a /who
   This creates a whisper queue based on the result from the /who.
   If you write your own /who command, the whisper queue will then be built from that result as long as LLFGBuddy is visible.
   
4. (Optional) Click "Whisper who?" to see to who the addon intends to send your message to.
   
5. Click "Send" to start whispering everyone in the queue, pause whispers or reset the queue if needed.

## ✨ Features

  - Builds a whisper list through a class/lvl filter.  
  - Skips players in instances, on your ignore list and battlegrounds (optional).  
  - Keep track of recently sent messages for quick reuse.
  - By default, the addon will only send a message to a player once every 10 minutes to avoid being a nuissance.
  - Positions itself next to the Who tab for easy access.

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

