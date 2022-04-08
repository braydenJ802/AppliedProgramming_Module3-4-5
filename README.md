# AppliedProgramming_Module3-4-5


This is a multi-faceted project combining modules 3, 4, and 5 (Networking, Mobile App, Game Platform). This is a small game app that can be run on mobile via the apk file or on windows via the exe file. This was created with the Godot game engine.

# Overview

This small application features simple game mechanics, mobile app interface and input, and networking. I created this to improve my skills in creating a small game/app and exporting it for android. I believe this project has helped me increase my knowledge with this game engine and has also provided an opportunity for me to learn how I might be able to develop games for the google play store.

The goals of the project were to make an object move, get a score, and connect to a network wirelessly. I was only able to connect on the local, internal ip addresss, "127.0.0.1", but the way I did so proves that a network connection was happening though I didn't connect to some other device via the internet. My testing didn't confirm that other connection types were possible, however my base server/client code is robust enough to handle those connections so long as the correct ports and addresses are provided. Everyone would have to supply their own addresses anyway, so I don't think this a major concern.

The game itself is very simple at the moment. It consists of a single red block that starts on a light blue ground pane. The block is constrained to vertical motion and so the player can jump and fall back to the same position on the ground. Each jump increments the score, which is stored in a singleton. The score label continuously updates the text displayed. The only other label is a test of the network connection, which displays "Network Connected: true" if the server has connected properly, and displays "Network Connected: false" if the server is not yet connected.


[Software Demo Video](https://youtu.be/gRTyXrCHCgo)

# Development Environment

* Godot v3.4.4 stable
* AndroidStudio (version: 2021.1.1 Patch 2 for Windows 64-bit)
* OpenJDK (version: jdk-17.0.2+8)

# Useful Websites

* [JDK Installation](https://adoptium.net/?variant=openjdk8)
* [Godot Docs](https://docs.godotengine.org/en/stable/index.html)
* Youtube

# Future Work

* Adapt code for wide-reaching internet connection
* Communication; send scores and receive score board. (Send score from game (client) to server, and send back all scores (from all clients) to every game/client involved).
* Add to game; new game mechanics

*Note: I had intended to make a tetris game with a leaderboard. The server would store the list of all the player scores and the player could access the updated leaderboard from the server. Even though I didn't complete that idea, I may work on something similar in the future, especially in regards to game play. (This is what I meant by the "Communication" bullet point above* 
