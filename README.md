# [Pong Game](https://streamable.com/55w2j5)

Table tennis themed 2D game with the option to play against the CPU or against another player.

Program is split into three sections:
- Input Handling - detect keystrokes from the user and move game components accordingly.
- Game Simulation - update gameplay with user input, ex. detect ball collision at borders, update score when the opposing player misses.
- Ouput Rendering - display results of game simulation functions on a window built with base components upon execution of the program.

Program is also divided into platform dependent layer and platform independent layer:
- Platform dependent layer in this program contains code specific to the Windows platform layer.
  - Used the [WinMain](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-winmain) function which serves as the base for a graphical Windows-based application, fetched from Microsoft's [Win32 API](https://docs.microsoft.com/en-us/windows/win32/).
- Platform independent layer deals with logical parts of the game (assets, physics, objects), not including graphics-rendering functions that interface with the OS.

<p align="center">
  <img src="/media/game-home.JPG" alt="home_menu" width="60%" align="center"> 
 </p>
 
<p align="center">
  <img src="/media/game-snip.JPG" alt="game_play" width="60%" align="center">
 </p>
 
 [link to the original author](https://danzaidan.itch.io/pong-learn-programming)
