#DubuEngine

A simple 2D game engine with socket support. Written in C++ using the Allegro library.

Tehnically this was my "first" C++ project. However it was so unstable and incomplete that I had to put it to use in order to find issues and make improvements. The project that was written on top of this engine was called ["Enso"](https://github.com/snorbertas/Enso
). The base of the engine was changed drastically so I had to strip away all the Enso code to leave myself with the new "improved" DubuEngine. So here it is.

I apologize for some of the files being really messy (such as Interfaces.cpp and InputHandler.cpp), the switch cases aren't actually part of the Engine itself. That messy code can be removed and rewritten as desired. I simply wanted to keep the main menu and other stuff to demonstrate how those functions work. They are not essential to the Engine.

I didn't really expect anyone to read this or use this, so keep that in mind while reading the code. If you wish, feel free to do so (just credit would be appreciated). I learnt alot from working on this Engine, if I was to rewrite it completely it would be much tidier, readable and friendlier.

I am planning on using DubuEngine for future projects for fun :)
![DubuEngine Client](http://puu.sh/svT0X.jpg)
TODO:
* MP3 playing/volume control (BASS libray)
* Organize fonts and sizes
Those things aren't really finished yet, though they're easy to fix.
