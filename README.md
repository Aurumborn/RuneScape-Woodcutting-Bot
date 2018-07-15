# RuneScape-Woodcutting-Bot
--------------------------------------------------------------------------------
Automate the gruesome task of cutting trees in the famous MMORPG Runescape!
--------------------------------------------------------------------------------

Technologies:
--------------------------------------------------------------------------------
- The script identifies trees in Runescape using the OpenCv library.
- The animation of cutting trees is achieved by clicking the identified tree. 
- Automated mouse positioning and clicks are handled using PyAutoGUI.

Description: 
--------------------------------------------------------------------------------
After each succesful woodcutting attempt the player recieves experience points in the skill of woodcutting along with a log item in their inventory. The script automates woodcutting unitl the player's inventory is full. In the event that the inventory is full, the script clears the inventory and repeats the woodcutting process.

Areas to Improve:
--------------------------------------------------------------------------------
- Tree detection: Most trees are detected, however depending on lighting, brightness and or camera angle trees may go unidentified.
- Falsely identified trees: During certain instances, objects in the game with similar contour shapes may be falsely identified as trees.
- Adapt to other displays: Remove hard coded values subject to personal display. 
