# Real-Time-Web-Application
Build with Node JS, HTML, CSS and JS.

## Text Based Game

Repository for a Text Based Game in the class of Real Time Web Application

1. Task 1 - You will start with a single-player, chat-like client-server system, using node.js and javascript. 
The goal of task is mainly to use javascript to create a chat-like game. Libraries like jQuery should be used.
To complete this task you need to do the following:
    ◦ The HTML page containing the game should be loaded from a node.js server. 
    ◦ Some settings and data in the game (such as the initial state of the game or initial player salutation) should be loaded via AJAX from a JSON file on the server.
    ◦ Implement a highscore table in the client, by storing data in local storage. 
    ◦ You will add 3 rooms and provide basic navigation commands to the player, in the client. I.e. the player should start in the “main” room each time the game is loaded, and be able to move from room to room via simple text-based commands. 
It is not important at this stage that the player’s avatar is able to interact with items or NPCs that might exist in the rooms. 

2. Task 2 - Now your game will be extended to multiple players, and the players will be able to interact with few simple items in each room. To complete this task you need to do the following:
    ◦ When a player enters the game she decides a username; a simple system to log in and out will be necessary here, with many players, each of them will need a specific and unique username.
    ◦ Players do not have to interact directly with each other in this version of the game. However, every player should be able to pick-up or drop an item in his/her room. Items can be moved (picked up, then dropped in a different room).  Perhaps you can give your characters the capability to create and destroy an item. 
    ◦ You should use web-sockets to implement your multiplayer chat.
    ◦ The state of the items in the room will be stored (persistency) on the node.js server, using a NoSQL DB. Also the passwords and usernames need to be stored on the NoSQL DB. 
    ◦ When a player leaves the game, its state remains the same (on the server), so the next time the same player logs in, she will continue as she never left. 

3. Task 3 – This task does not need to be done in code. This version could have a bit of graphics and sounds in the user-interface, if you want to do that. You can decide to deliver just a mood board to show how you imagine your game GUI to look, when the game is finished. If you like, instead you could implement a few social elements, such as gifts or attacks among players (cooperative/competitive play), or perhaps special powers such as the capability of creating new rooms from within the game. To complete this task you need to do the following:
    ◦ deliver just a mood board
    ◦ Or… implement a few social elements, and a more complete gameplay.

While developing your game, you would design some (simple) HTML-based GUI, using javascript. Simple static graphics can be used in the GUIs, for example to show a map of the rooms, or the state of the current room, or perhaps show score/health/energy in a HUD (https://en.wikipedia.org/wiki/Head-up_display_(video_gaming) ).
