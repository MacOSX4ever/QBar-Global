QBar - Quest Item Button Bar
----------------------------
Ever been questing and had to find all those usable quest items in your bags all the time, then this addon is for you. No longer will you have to keep your bags open to do daily bombing quests!

This addon will automatically create a dynamic buttonbar for all those usable quest items, it also checks if your equipped gear for usable quest items.
As using items is a secure function, QBar is not able to update the bar or the set keybinding when in combat. This will only be changed outside of combat.

You may ask, why use this over the buildin quest item buttons? Well, the buildin buttons will only show items you receive when you accept the quest,
any usable quest items you loot during a quest will not be shown, QBar will however. QBar will also show items which starts a quest, so you wont miss them in between all the cluttered loot.
The default buttons also goes away once you complete the quest, but the item is not actually removed until you turn the quest in, and you may want to use the item even after the quest is complete.

If you do not wish to show a certain item on QBar, you can ignore it by holding down Shift and clicking on it.

Button Facade Support
---------------------
https://www.curseforge.com/wow/addons/qbar-global

QBar-Global Slash Commands
==========================

Entry points: /qb or /qbar

/qb                         Print version, memory usage, and help to chat
/qb toggle                  Enable or disable the addon
/qb scale <value>           Set button scale (default: 1)
/qb size <value>            Set button size in pixels (default: 36)
/qb padding <value>         Set space between buttons (default: 1)
/qb tips                    Toggle item tooltips on hover
/qb vertical                Toggle vertical vs horizontal layout
/qb mirror                  Toggle anchor direction (left/right or top/bottom)
/qb lock                    Toggle frame lock for repositioning (also: unlock, move)
/qb reset                   Reset bar position to center of screen
/qb bind                    Open keybinding dialog (also: key)
/qb add <itemlink>          Force-add an item to the bar (also: additem)
/qb clearignore             Show all items again, clearing the ignore list
/qb clearuser               Clear the manual add list

Notes:
- SHIFT-Click any button to add it to the ignore list (hide it from the bar)
- SHIFT-Click an item in the user list to remove it from that list instead
- /qb add accepts either an item link or a numeric item ID

Lacking Features, Problems & Ideas
----------------------------------
- Manage the update of keybinding, no need to unbind and rebind if it stays the same as before.