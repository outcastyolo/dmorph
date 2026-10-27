# dmorph

Client-side appearance changer for World of Warcraft 3.3.5a (build 12340). Only you see the changes.

## Run

1. Keep `Injector.exe` and `dmorph.dll` in the same folder. Any folder is fine. They do not go in the WoW folder.
2. Start WoW and log in to a character, or leave it at the login screen.
3. Run `Injector.exe`.
4. Enter the world. Chat shows `dmorph: v2.0 loaded`.
5. Type `.help` in chat.

Restart WoW before injecting again if it was already injected.

## Commands

`0` or `off` restores that one thing. `.reset` restores everything.

| Command | Effect |
|---|---|
| `.morph <id>` | Your model. `.morph target` copies your target. |
| `.race <1-11>` | 1 human, 2 orc, 3 dwarf, 4 night elf, 5 undead, 6 tauren, 7 gnome, 8 troll, 9 goblin, 10 blood elf, 11 draenei. Uses your current gender. |
| `.gender` | Swaps male and female. |
| `.scale <size>` | Size. `1` is normal. |
| `.item <slot> <itemId>` | How a gear slot looks. `0` hides it. Slots: 1 head, 3 shoulders, 4 shirt, 5 chest, 6 waist, 7 legs, 8 feet, 9 wrists, 10 hands, 15 back, 16 main hand, 17 off hand, 18 ranged, 19 tabard. |
| `.enchant <16\|17\|18> <id>` | Weapon enchant glow. |
| `.mount <id>` | Mount model while you are mounted. `.mount target` copies a mounted target. |
| `.pet <id>` | Pet model. `.pet target` copies your target. |
| `.shapeshift <id>` | The form you are currently in. |
| `.title <id>` | A title, by wowhead title id. `0` hides yours. |
| `.skin` `.face` `.hair` `.haircolor` `.facial <n>` | Character customization. |
| `.hotkeys on\|off` | F5 resets model and scale. F10 resets everything. Only while WoW is the active window. |

Your look is saved per character next to the DLL, in `profiles`, and comes back when you log in. That folder and `dmorph.ini` are created automatically. Do not copy someone else's `profiles` folder. Each person gets their own when they use a command.
