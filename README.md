# DeckSkripts

A collection of scripts that I use to keep my Steam Deck "daily-driver" ready.

## Table

- [Goals](#Goals)
- [Usage](#Usage)
- [Special Thanks](#Special_Thanks)
- [Contributing](#Contributing)

### Goals
- The script should do what it says on the tin.
- Prioritize dependencies already included in SteamOS, rather than pulling new ones in (when possible).
- Provide graphical feedback. Scripts should only *require* Konsole if debugging.
- Share the love. Public, forkable, and permissive to adaption.

### Usage

They're bash scripts, so it's pretty simple.

1) Download the scripts you want (git, zip, or raw)
2) Make them executable
   - `chmod +x /path/to/script`, or, open the file properties menu and mark them as "Is executable".
      ![image](https://github.com/TheFlagCourier/DeckSkripts/assets/2712890/d09cb216-8859-47e2-955c-801ff2779d91)
3) Run as needed.
   - Run them from the Desktop / File Browser
   - or, run them in the terminal: `/path/to/CUPS_INSTALL`

### Special Thanks
- Deckplosion.de - The script CUPS_INSTALL is adapted from.
- LittleJawa (Steam Community) - Originator of the script featured on Deckplosion.

### Contributing
These scripts are created with the Bourne Shell (bash) in mind, and are verified with ShellCheck. PRs will not be merged unless they pass linting.
Other than that, if you have a script you use regularly for your Steam Deck, or see where one can be improved, feel free to open that PR!
