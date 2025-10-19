# LFGBuddy

Tired of writing /who commands or copy/pasting the same message to 15 people to find dungeon buddies? ME TOO! <br>

**LFG Buddy** is designed to do that task for you.

The addon adds an easy-to-use filter to find players using /who commands and offers sending a message to all players in the result that are not already in instances, on your ignore list or in battlegrounds (optional).

##[Download LFGBuddy](https://github.com/hjortmar/lfgbuddy/raw/main/LFGBuddy.zip)##

## ✨ Features and usage

  **You will find LFG Buddy when you open the Who tab**
  
1. Choose your filter by class and level range.
<br><br>
2. Write a poem in the messagebox, this is the message that the addon will send to players when you click "Send".
   - Once you have sent a message, it will be saved for quick reuse.
   - You can select roles (Tank, Healer, DPS) from the class dropdown to /who several classes in one sweep.
<br><br>
3. Click "Find players", this will send a /who command based on your filter and capture the result to a whisper queue.
   - If you write your own /who command, the whisper queue will then be built from that result.
   - The whisper queue will not capture players in instances, on your ignore list or in battlegrounds (optional). 
<br><br>
4. Click "Send" to start sending messages to all players that were captured into the whisper queue.
   - Click "Whisper who?" to see to who the addon intends to send your message to.
     - Clicking "Whisper who?" will also show a reason explaining why a player was not captured into the whisper queue.
   - By default, the addon limits you to one message to the same player on a 10 minute timeout.
   - Click "Pause" if you want the addon to stop sending messages.

## 🖼️ Screenshots
![Main](images/lfgbuddimg3.png)

Updated the UI a tiny bit, couldn't be bothered to take a new screenshot.. some paint action going on. :P

## ⚙️ Installation

1. [Download LFGBuddy](https://github.com/hjortmar/lfgbuddy/raw/main/LFGBuddy.zip).
2. Extract in your `World of Warcraft\Interface\AddOns` directory.
3. Ensure the folder structure looks like this:<br>
   - `Interface\AddOns\LFGBuddy\LFGBuddy.toc`<br>
   - `Interface\AddOns\LFGBuddy\Main.lua`
4. Launch WoW and enable LFGBuddy on the character selection screen.

## 📝 Notes

LFGBuddy is only tested with a WotLK 3.3.5 (2009) client on **Epoch WoW 3.3.5**.  

## 📜 License

This addon is provided as-is. Modify and share freely, but please credit the original author.

