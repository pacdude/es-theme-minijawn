# MiniJawn
A theme for EmulationStation specifically designed for small screens (like the RetroFlag GPi Case). 

![MiniJawn 1.0 Title Screen](https://c10.patreonusercontent.com/3/eyJwIjoxfQ%3D%3D/patreon-media/p/post/27746437/a62326ef3c034d24a4cbb4f080ca2dc0/1.jpeg?token-time=1562112000&token-hash=b8XWjP5zZAkBGBuVzrvAsTvqQCIIKMuUzwJgfdkmu2c%3D "MiniJawn 1.0 Title Screen")

## About
MiniJawn is a small theme I put together to have a nice-looking theme for my RetroFlag GPi. The screen is small and not that high-definition, so having a big, bold UI was a must. And since this is running on a Raspberry Pi Zero, I didn't feel like doing a whole lot. View more images at [my Patreon page](https://www.patreon.com/posts/27746437).

![MiniJawn 1.0 Collage](https://preview.redd.it/nq9uypzhsi531.png?width=960&crop=smart&auto=webp&s=e3635d75cbaab23a8ed079357b3e74b5e5a4600e "MiniJawn 1.0 Collage")

## Installation Instructions
SSH into your Pi, or exit Emulation Station to the command prompt. Type the following lines, one at a time:

`cd /opt/retropie/configs/all/emulationstation/`

`mkdir themes`

`cd themes`

`git clone https://github.com/pacdude/minijawn.git`

Or, you can download as a ZIP file, unzip the thing, then stick the minijawn folder in /configs/all/emulationstation/themes. (If that folder doesn't exist, create it.)

## Supported Consoles & Collections
Version 1.5 of this theme supports:
- Amiga
- Arcade/Mame
- Atari 2600
- Atari 5200
- Atari 7800
- Commodore 64
- Dreamcast
- Famicom Disk System
- Game Gear
- Game Boy
- Game Boy Advance
- Game Boy Color
- Sega Master System
- Megadrive / Genesis
- NES
- Neo Geo Pocket Color
- Nintendo 64
- PC Engine / TurboGraphix16
- PlayStation
- PlayStation Portable
- SNES / Super Famicom
- Ports

- Retropie Menu
- Auto Collection: All Games
- Auto Collection: Last Played
- Auto Collection: Favorites
- User-Defined Custom Collections
- Custom Collection: Super Mario (mario)
- Custom Collection: Sonic the Hedgehog (sonic)
- Custom Collection: Pokemon (pokemon)
- Custom Collection: The Legend of Zelda (zelda)
- Custom Collection: Tetris (tetris)
- Custom Collection: Game Shows (gameshows)

## Add a Custom Collection
![MiniJawn 1.5 Custom Collection](https://i.imgur.com/0aH2ICO.png "MiniJawn 1.5 Custom Collection")

There are 6 custom collections supported by MiniJawn, with more coming upon request. To add them to your EmulationStation install, follow these directions:

1. Press `Start` on your device to bring up the EmulationStation Main Menu. 
2. Select __Game Collection Settings__.
3. Select __Create New Custom Collection from Theme__.
4. Select the custom collection you want to install.
5. Filter through your games list and press the Y button to add a game to the collection.
6. After adding the games you want in your collection, you can finish editing the collection by either going to any game list, pressing `Select` and selecting __Finish Editing Collection__, or going to __Game Collections Settings__ menu and then select __Finish Editing Collection__.

## Not Implemented Yet
- Grid mode is not implemented yet. Once I understand how it works a little more, I'll do something with it, I guess.\
- I haven't tried this theme out on a screen resolution larger than 320x240. The theme's raw files are designed at 320x240 right now. I guarantee it will look like ass on a larger display. I may spruce it up in a future update.

## Suggested Settings
In Emulation Stations' UI settings, I would set Carousel Transitions to ON, Transition Style to Fade, Gamelist View Style to Detailed, and On-Screen Help to OFF.

## Home Page Full Screen
![MiniJawn 1.2 Full Screen](https://i.imgur.com/7J0JrHQ.png "MiniJawn Full Screen")

If you'd like a full-screen experience, edit line 12 of the `theme.xml` file from

`<include>./home.xml</include>`

to say 

`<include>./home_full.xml</include>`

## Screenshot-Friendly Detailed Screen
![MiniJawn 1.5 Screenshot Detailed List](https://i.imgur.com/fzkX2Gm.png "MiniJawn Detailed List")

If you've scraped screenshots, this view is going to look great on the small screen. Edit line 15 of the `theme.xml` file from

`<include>./detailed.xml</include>`

to say

`<include>./detailed_more.xml</include>`

## Changelog
1.5: Detailed Screenshot-Friendly Mode and Custom Collections added.

1.2: Added a Full-Screen Option, as well as more consoles.

1.1: Theme now has a fallback for logos that don't exist. It's not great but it works. Ports, Final Burn Alpha, PCEngine and TurboGraphix16 now have support for icons and marquees.

1.0: Initial Release
