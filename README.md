# My Trimui Smart Pro Games
![DownloadCountTotal](https://img.shields.io/github/downloads/joyrider3774/trimui_smart_pro_games/total?label=total%20downloads&style=plastic) ![DownloadCountLatest](https://img.shields.io/github/downloads/joyrider3774/trimui_smart_pro_games/latest/total?style=plastic) ![LatestVersion](https://img.shields.io/github/v/tag/joyrider3774/trimui_smart_pro_games?label=Latest%20version&style=plastic) ![License](https://img.shields.io/github/license/joyrider3774/trimui_smart_pro_games?style=plastic)

Builds of my games running on Trimui smart Pro

## Installing
In general on the trimui smart pro, enable usb disk mode and connect your trimui smart pro to your pc.
On the drive that appears from it there should be an `Apps` folder, extract the zips you download from the 
[Release Section](https://github.com/joyrider3774/trimui_smart_pro_games/releases) in this folder.
For example if you open `checkers - Trimui_Smart_Pro.zip` there will be a folder inside, in this example named
`checkers` you need to copy that folder to the `Apps` folder of your trimui smart pro disk. 

## Generic Game controls

| Key | Action |
| ------ | ------ |
| Dpad or Joystick | movement, selecting in menu's etc |
| A | A Button as mentioned in the games for functionality of each game please check each game's repository |
| B | B Button as mentioned in the games for functionality of each game please check each game's repository |
| LB | In Playdate games simulate crank move backwards movement, in my games usually used in the level editors to select previous piece. In other games consult game's repository to know the functionality |
| RB | In Playdate games simulate crank move forwards movement, in my games usually used in the level editors to select next piece. In other games consult game's repository to know the functionality |
| Y | In (Playdate) games starting up in black and white, reboot and use colored version of graphics, some games have multiple colored graphics so you can press it again to see more options. The button basically makes you cycle through all possibilities |
| Menu | Quit game and return to menu |

---

## Games
Please see respective repo of each game to get more information about the games by clicking on the `Game Info` links

## Blockdude (Playdate)
![Blockdude Screenshot 1](https://raw.githubusercontent.com/joyrider3774/blockdude_playdate/main/metadata/screenshots/screenshot1.png) ![Blockdude Screenshot 2](https://raw.githubusercontent.com/joyrider3774/blockdude_playdate/main/metadata/screenshots/screenshot9.png)

Blokdude is a remake of the well known TI Caluculator game from Brandon Sterner as well as the blockman game from Soleau Software. This version of the game is based on the GP2X port of blockdude i made over a decade ago.

[Game Info](https://joyrider3774.github.io/blockdude_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/blockdude.-.Trimui_Smart_Pro.zip)

---

## Crisp Game Library Portable SDL(2) Port
![Crisp Game Library Portable SDL(2) Port Screenshot 1](https://raw.githubusercontent.com/joyrider3774/crisp-game-lib-portable-sdl/main/docs/screenshotMenu.gif) ![Crisp Game Library Portable SDL(2) Port Screenshot 2](https://raw.githubusercontent.com/joyrider3774/crisp-game-lib-portable-sdl/main/docs/screenshotTrimuiSmartPro.gif)

This is contains the sdl(2) port i did, of the crisp games library portable which is a Minimal C-lang library for creating classic arcade-like mini-games running on devices and browsers. Re-implemented version of crisp-game-lib for smaller devices. I ported extra games to this portable library, added extra options like small overlays (pixel grid, glow, crt etc), ability to switch between darkmode and no darkmode, ability to save highscores, overlays and darkmode per game, ...

Note: 

- I did not create these games nor the library itself or any of the game idea's, this was created by user [AbaGames](https://github.com/abagames/) i'm only portraying my sdl port here with added extras and newly ported games from the Javascript versions to this portable library.
- I had to enable No Scaled Drawing mode for trimui because of the 1280x720 screen and the trimui smart pro not being able to run the games fullspeed otherwise, this means overlays like glow, pixel grid and crt effect are also disabled !
- A and B Button are swapped on the trimui smart pro (it follows xbox controller layout)

[Game Info](https://joyrider3774.github.io/crisp-game-lib-portable-sdl) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/cglpsdl2.-.Trimui_Smart_Pro.zip)

---

## Checkers (Playdate)
![Checkers Screenshot 1](https://raw.githubusercontent.com/joyrider3774/checkers_playdate/main/metadata/screenshots/Checkers-screenshot1.gif) ![Checkers Screenshot 2](https://raw.githubusercontent.com/joyrider3774/checkers_playdate/main/metadata/screenshots/Checkers-screenshot5.png)

Checkers is the well known board game with four difficulties and a jump heuristic. This version is port of my gp2x version made to work with the Trimui Smart pro handheld.

[Game Info](https://joyrider3774.github.io/checkers_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/checkers.-.Trimui_Smart_Pro.zip)

---

## Dynamate (Playdate)
![Dynamate Screenshot 1](https://raw.githubusercontent.com/joyrider3774/dynamate_playdate/main/metadata/screenshots/Dynamate-screenshot1.gif) ![Dynamate Screenshot 2](https://raw.githubusercontent.com/joyrider3774/dynamate_playdate/main/metadata/screenshots/Dynamate-screenshot4.png)

Dynamate is a puzzle game invented by Björn Kalzen and Jonas Norberg, a couple of years ago i contacted them to make a port for the gp2x handheld. This version is port of my gp2x version made to work with the Trimui Smart pro handheld.

[Game Info](https://joyrider3774.github.io/dynamate_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/dynamate.-.Trimui_Smart_Pro.zip)

---

## Formula 1 Game & Watch (Playdate)
![Formula 1 Screenshot 1](https://raw.githubusercontent.com/joyrider3774/formula1_playdate/main/metadata/screenshots/Formula%201%20Game%20%26%20Watch%20screenshot%201.png) ![Formula 1 Screenshot 2](https://raw.githubusercontent.com/joyrider3774/formula1_playdate/main/metadata/screenshots/Formula%201%20Game%20%26%20Watch%20screenshot%204.png)

Formula 1 Game & Watch is a small, fictive formula 1 game & watch style lcd game with high score keeping. The Game was initially created over a decade ago for a small retrogame competition, after which it got ported to the gp2x. This version is based on the gp2x version but with added high score saving.

[Game Info](https://joyrider3774.github.io/formula1_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/formula_1.-.Trimui_Smart_Pro.zip)

---

## Mazethingie (Playdate)
![Mazethingie Screenshot 1](https://raw.githubusercontent.com/joyrider3774/mazethingie_playdate/main/screenshots/screenshot1.png) ![Mazethingie Screenshot 2](https://raw.githubusercontent.com/joyrider3774/mazethingie_playdate/main/screenshots/screenshot2.png)

Mazethingie which is a maze generator / player.

[Game Info](https://joyrider3774.github.io/mazethingie_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/mazethingie.-.Trimui_Smart_Pro.zip)

---

## Rubido (Playdate)
![Rubido Screenshot 1](https://raw.githubusercontent.com/joyrider3774/rubido_playdate/main/metadata/screenshots/Rubido-screenshot3.gif) ![Rubido Screenshot 2](https://raw.githubusercontent.com/joyrider3774/rubido_playdate/main/metadata/screenshots/Rubido-screenshot6.png)

Rubido is a little chinese checkers or solitaire game with four difficulties.

[Game Info](https://joyrider3774.github.io/rubido_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/rubido.-.Trimui_Smart_Pro.zip)

---

## Puzzle Land (Playdate)
![Puzzle Land Screenshot 1](https://raw.githubusercontent.com/joyrider3774/puzzleland_playdate/main/metadata/screenshots/Puzzleland-screenshot1.png) ![Puzzle Land Screenshot 2](https://raw.githubusercontent.com/joyrider3774/puzzleland_playdate/main/metadata/screenshots/Puzzleland-screenshot8.png)

Puzzle Land is a remake of the gameboy game Daedalian opus also known as puzzle road in japan. The gameplay and levels are the same but the graphics, music sounds have changed. It's a puzzle game with 36 levels. It is a tribute to a game i spend endless hours playing as a child.

[Game Info](https://joyrider3774.github.io/puzzleland_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/puzzleland.-.Trimui_Smart_Pro.zip)

---

## Puztrix (Playdate)
![Puztrix Screenshot 1](https://raw.githubusercontent.com/joyrider3774/puztrix_playdate/main/metadata/screenshots/puztrix-screenshot1.gif) ![Puztrix Screenshot 2](https://raw.githubusercontent.com/joyrider3774/puztrix_playdate/main/metadata/screenshots/puztrix-screenshot10.png)

Puztrix is a remake of the Gravnic game from inside the NES Puzznic game.

[Game Info](https://joyrider3774.github.io/puztrix_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/puztrix.-.Trimui_Smart_Pro.zip)

---

## RetroTime
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/joyrider3774/RetroTime/master/metadata/bubblebuster.png"><img src="https://raw.githubusercontent.com/joyrider3774/RetroTime/master/metadata/bubblebuster.png" alt="Retrotime Screenshot 1" width="400"></a> <a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/joyrider3774/RetroTime/master/metadata/fasterdave.png"><img src="https://raw.githubusercontent.com/joyrider3774/RetroTime/master/metadata/fasterdave.png" alt="Retrotime Screenshot 2" width="400"></a>

RetroTime is a game containing 8 retro based games playable in 3 game modes being Retro Carousel, Time Attack and Lives mode. The game is a port from my competetion entry for Fuze 4 for Nintendo switch, in colleboration Wireframe magazine.

[Game Info](https://joyrider3774.github.io/RetroTime) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/retrotime.-.Trimui_Smart_Pro.zip)

---

## Waternet (Playdate)
![Waternet Screenshot 1](https://raw.githubusercontent.com/joyrider3774/waternet_playdate/main/metadata/screenshots/Waternet-screenshot1.gif) ![Waternet Screenshot 2](https://raw.githubusercontent.com/joyrider3774/waternet_playdate/main/metadata/screenshots/Waternet-screenshot7.png)

Waternet is a multiplatform puzzle game written for old consoles and handhelds like Game Boy (Color), Game Gear, Master System, Analogue Pocket and Mega Duck and now also Trimui Smart Pro! It's a combination of the net and netslide games from the simon tatham's puzzle collection!

[Game Info](https://joyrider3774.github.io/waternet_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/waternet.-.Trimui_Smart_Pro.zip)

---

## Worm (Playdate)
![Worm Screenshot 1](https://raw.githubusercontent.com/joyrider3774/worm_playdate/main/screenshots/screenshot1.png)

Worm is a copter / worm game remake with 5 game modes and a seed system written for playdate

[Game Info](https://joyrider3774.github.io/worm_playdate) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/worm.-.Trimui_Smart_Pro.zip)

---

## Znax
<img src="https://raw.githubusercontent.com/joyrider3774/Znax/master/images/znaxscreenshot1.png" alt="Znax Screenshot 1" width="400"> <img src="https://raw.githubusercontent.com/joyrider3774/Znax/master/images/znaxscreenshot4.png" alt="Znax Screenshot 2" width="400">

Znax is a cross platform puzzle / arcade game using SDL2 libraries. It has skin support and can be played using a keyboard, mouse, joypad or touchscreen. You select 4 of the same colored pieces forming a rectangle to gain scores and remove the pieces inside the rectangle!

[Game Info](https://joyrider3774.github.io/Znax) - [Download for Trimui Smart Pro](https://github.com/joyrider3774/trimui_smart_pro_games/releases/latest/download/znax.-.Trimui_Smart_Pro.zip)


