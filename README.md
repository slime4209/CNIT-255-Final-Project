# CNIT-255-Final-Project
Escape - Role Playing Game made with Java


CNIT 25501 Project Abstract
This project focuses on making a simple GUI game with Java. This game, titled
Escape, is about an alien that got abducted by a spaceship of researchers. The goal of
the player is to help the alien escape from the spaceship without getting caught by the
security guards. The code has four packets: Main, Human, Object, and Tile. The Main
packet contains all the backbone classes of the game. The Human packet contains an
interface that serves as the cookie-cutter tool for the two security guards that appear in
the game. The Object packet contains all the classes for any objects that appear
throughout the game. Lastly, the Tile packet has a TileManager class that determines
which image will go inside the Tile class and draw the game map with the image of the
tiles.

Brief Story of the Game
 The main character, named Yam Ginseng, is a baby alien abducted by a
suspicious researcher named Helen Tai. The player will have to take control of Yam to
get the card keys, unlock each door in the room, and get out of the spaceship. However,
in the process of doing so, Yam encounters two security guards, Casey Whitesell and
Mary Marrison. If Yam gets in contact with either one of those guards, it will be game
over.

Main Packet
The Main packet has nine classes that serves as the backbone of the game.
Each of them serves a different purpose to make the game run smoother.

Human Packet
The Human packet has an interface named Humans that contains all the
methods that will be used by the Casey and Mary classes. Since both Casey and Mary
share the same methods, an interface was implemented to organize the methods used
for the characters.

Object Packet
The Object packet contains all the classes for each object used in the game. For
example, there are classes for the card keys that Yam has to collect to unlock the doors.
There are two types of objects: one can interact with the player while the other one is
immobile. An example of an interactable object would be Helen’s table since it
describes all the stacked papers on top of the table. An example of an immobile object
would be the glass case because it does not do anything even when the player presses
enter near it.

Tile Packet
The Tile packet contains two classes that draws the tiles used in the game. Just
like objects, tiles can be divided to two types: one type can be passed through while
other type will have collision with the player. While the floor tiles can be walked through,
the wall tiles will cause collision with the player.
