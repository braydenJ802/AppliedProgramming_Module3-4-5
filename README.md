# AppliedProgramming_Module3-4-5


This is a multi-faceted project combining modules 3, 4, and 5 (Networking, Mobile App, Game Platform). This is a small game app that can be run on mobile via the apk file or on windows via the exe file. This was created with the Godot game engine.

# Overview

This small application features simple game mechanics, mobile app interface and input, and networking. I created this to improve my skills in creating a small game/app and exporting it for android. I believe this project has helped me increase my knowledge with this game engine and has also provided an opportunity for me to learn how I might be able to develop games for the google play store.

The app consists of making an object move, getting a score, and connecting to a network wirelessly. I was only able to connect on the local, internal ip addresss, "127.0.0.1", but the way I did so proves that a network connection was happening though I didn't connect to some other device via the internet. My testing didn't confirm that other connection types were possible, however my base server/client code is robust enough to handle those connections so long as the correct ports and addresses are provided. Everyone would have to supply their own addresses anyway, so I don't think this a major concern.

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
