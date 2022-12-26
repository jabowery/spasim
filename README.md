# spasim
[Source code](https://github.com/jabowery/spasim/blob/main/xspasim) for [SPASIM](https://en.wikipedia.org/wiki/Spasim) (*SP*ace *SIM*ulation), the world's first (1974) 3D networked game.  

[Here's a video demonstrating how it worked.](https://youtu.be/nMZv5Akcum8)

![spasimtshirtx1024](https://user-images.githubusercontent.com/57646/209396006-a67948eb-a5a3-4641-89ba-225d94338f3f.png)

[The file "xspasim"](https://github.com/jabowery/spasim/blob/main/xspasim) contains [the TUTOR programming language](https://en.wikipedia.org/wiki/TUTOR) source code, rendered as if output by a Control Data Corporation line printer.

Toward the end there is also a rendering of stored data structures required by the game in the form of "common blocks".

Common blocks were called "common" because they were shared [core memory](https://en.wikipedia.org/wiki/Magnetic-core_memory) regions -- data shared in real-time in common by multiple users of the program -- which is how they shared a dynamic model of the universe being simulated.  Frame rates?  Well... that depended on what time of day you were playing.  At night you could get 32 people interacting with 10FPS universe updates.

The '=' sign around =spasim= was a convention used on the PLATO network to designate programs executable by PLATO users.  Such programs were called "lessons" since the original purpose of PLATO was as a computer-based education system.  Although it was not originally intended to permit users to interact with each other over the network, it turned out to be one of the main applications of the PLATO network.

The Computer History Museum has an excellent [5 hour interview with Don Bitzer, "The Father of PLATO" and inventor of the plasma display](https://youtu.be/5qytDtHZHp4).

For an in depth history of PLATO read "The Friendly Orange Glow" by Brian Dear.  "Orange" was the color of the neon pixels of the first plasma displays.  The plasma display was invented for the PLATO system by the father of PLATO, Don Bitzer.

Believe it or not, you can still play =spasim= on an emulator of the CDC Cyber series computers, running a copy of the Cyber's operating system, running a copy of the PLATO system -- and you can even do so with other users in real time.  It takes some work to get to know the key conventions and how to navigate but as can be seen in the screenshot above, which was taken just the week before the first commit of this repository, it does still work.

[cyber1.org](https://cyber1.org/) is the place to find out about the PLATO system that is currently running =spasim= and many other legendary games from the 1970s.
