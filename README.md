# game_networking_resources

So netcode is hard. It's like crypto except not so critical when it fails, just totally unfun.

Wouldn't it be great if there was just one standard library to import that just handles it for you? Or at least a common resource that explains different approaches?

The most important thing to start with is that having to deal with multiple machines/computers it that it complicates things a lot. You can't just 

controller.getInput()
game.applyInput()

anymore. You have deal with who gets what input, when, how it's formatted, what to do when the input doesn't get there, how to communicate stuff back to the "server" and just... messy stuff.

When I was still looking into more new games, the question often was "oh but does it have multiplayer" and the answer was often "no" because it's just such a big can of worms.

Here are some resources:

no experience with these

C#

# godot

https://docs.godotengine.org/en/stable/tutorials/networking/high_level_multiplayer.html

python

# panda

https://docs.panda3d.org/1.10/python/programming/networking/datagram-protocol/client-server-connection

https://github.com/panda3d/panda3d/tree/371e60c768cfd1a1383c5b05f1cab2078014ccea/panda/src/net


# blender

blender's game engine is bascially dead, but in the long long before, a guy I have great respect for made a really good tutorial on sockets:

https://www.youtube.com/watch?v=4xZRfzOtxzA

# pygame 

has nothing except basic sockets for python I think?

Cpp

# c&c remastered open source

8000 lines of full package. Not sure how it works, but it *does* work. And 80% of it is comments, so that's good.

https://github.com/electronicarts/CnC_Remastered_Collection/blob/master/REDALERT/NETDLG.CPP

# widelands

Is a working, open source game with a multiplayer component. The project is actively being worked on too.

https://www.widelands.org/

https://github.com/widelands/widelands

https://github.com/widelands/widelands/tree/master/src/network
