# PONG V1.2
Pong made in python using [pygame library](https://www.pygame.org/)

Download and extract .zip and run Run.bat

The songs are from soulknight

Turns out pygame-gui exists, I hate myself

## Dependencies:

*pygame, pygame.mixer, sys, math, numpy, random, cv2*

## Features

- Entirely made using pygame

- Includes a starting screen

- 1 player mode and 2 player mode

- The bot has 3 different difficulties

- The buttons change your mouse cursor when you hover

- Pause and exit buttons in-game

- And I actually made it look nice for the first time.

- *NEW:* I ADDED A SETTINGS MENU

For an .exe self-extracting zip file go to my [Pong.exe Github Page](https://github.com/Kai-Guan/PONG-exe) (may not be newest version)

## To-do List
- [x] Add an options menu to toggle sound effects and music.
- [x] Add a music volume controller.
- [ ] Add a bot v bot mode.
- [ ] Add gamemodes.

## Known Issues
- Sometimes when loading the game there will be an error: 'pygame.error: ModPlug_Load failed'
  
    This is due to .mp3 files being weird in pygame.

    Try running the game a few times again, it may not work on Linux.

- Sometimes the volume option is broken.
  
    For Windows,

    - Right click on the speaker icon in the taskbar

    - Select Playback Devices

    - Select Speakers and Properties

    - Go to Enhancements tab and uncheck Equalizer and Loudness Equalization
