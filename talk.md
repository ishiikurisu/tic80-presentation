# Introduction to TIC-80

This is TIC-80.

Its name means "Tiny Computer 80" and it is an open source fantasy
console.

Hopefully most of you are used to the concept of "open source", which in 
itself already makes TIC-80 a project that should be worth your attention.
However, I imagine most of you do not know what "fantasy console" means.

You see, one of the worst problems about distributing videogames is that
they are often too tied with the platform they are developed with. This
is because videogames often push the boundaries of what is possible to be
done with a certain machine. And one can't push the boundaries of what is
possible with a machine without knowing it so well that one can even
explore its bugs and defects. The best of example of this boundary pushing
software development certainly is the _demoscene_, where hackers and
enthusiasts constantly amaze their audiences by taking apart every nook
and cranny of their computers and their code and their task at hand to
redefine the boundaries of their platforms. Again, the thing is that, aside
from watching their videos, demos are often bound to a particular kind of
computer, sometimes even to a particular machine that not everyone has
access to, which makes enjoying these kinds of creations very hard at times.

There certain ways of mitigating this problem. One of the most popular ones
is to develop on top a _game engine_. Nowadays, game engines such as 
Unity, Unreal, and Godot allow thousands of game developers around the
world to ship their creations in record time and budget compared to 
historical standards. The idea of the game engine is that development can
be split into 2 parts: engine devs focus on porting the engine to as many
computers as desired by the studio while game devs are allowed to be as free
as possible with their art. In other words: by adding this layer of 
abstraction, game devs are now basically free from the particular details
of whatever machine is running their games. Of course, they might still
need to think about some technical limitations here and there, these are
natural to anything related to computers. We still don't have infinite
memory and hard drives after all. Aside from that, this layer of abstraction
is fundamental for the existence of the current game development industry.

Another way is to do the opposite: instead of trying to reach as many
platforms as possible, one could try to focus on a single machine. 

<!-- 
I'm not liking the direction this talk is taking.

It should have a WTF moment.

Right now I'm only talking about random stuff. This is a really
bad introduction to the topic right now.
-->



# Metadiscussion

Maybe I should do it like this?

- [x] ~~Outline talk structure~~
- [x] ~~Write paragraphs as required~~

## Talk Structure

What points I want to make?
- fantasy consoles are cool
  - why? they look retro, they have a lot of history packed into them
  - unexpected cool stuff: different and novel dev environment
- fantasy consoles are an interesting challenge if you want to push it to
  its extreme
- small is cool too
  - too big and it's hard to focus on what really matters


# Talk, 2nd try

This is probably the least appropriate place to talk about this, but hear 
me out. Fantasy consoles are cool. Their own existence is an exercise in 
both absurdity and creativity.

If you don't know what it is, a fantasy console is like an emulator. If 
you don't know about it, an emulator is a computer program that simulates 
the hardware of another. This is one of the many forms of virtualization, 
a technology most of us (people who work with software) deal with 
everyday; an example being Docker. Using virtualization or emulators allow 
developers to write code for a single architecture and deliver the same 
code everywhere given the architecture can be sucessfully virtualized. 
This introduces a useful layer of abstraction for software development. 
The thing for this talk though is that fantasy consoles flip this 
usefulness on its head: what if we invent an architecture? What if this 
architecture doesn't really exist? In other words: if one could invent any 
computer they would like, how would one do that? Fantasy consoles are 
"emulators" for computers that do not necessarily exist but that allow for 
a certain set of experiences. And these experiences are the focus of 
today's talk.

Today, we are focusing on TIC-80, an open source fantasy console. It's 
designed to have this small screen resolution; a limited colour palette; 
limited sound; not many sprites; and some other limitations so it 
everything on it looks retro. However, its development cycle and tooling 
are nothing close to retro: it can be programmed in a variety of languages 
(from LISP and WASM to Lua and Javascript); its programs can be download 
from the internet without too much of a hassle; and it already includes 
many of the software development apparatus with it. For those who are 
already familiar with it, it's similar to the PICO-8 (any Celeste players 
out there?) but with the benefit of being open source. 

A TIC-80 game plays out a bit like this...

Now, the question is: why would someone do that? Aside from the previously 
mentioned "write once, ship everywhere" benefit, this kind of environment 
was made with a particular experience in mind, and to understand it, we 
have to look it from a particular perspective. You see, musicians often 
say that limitations breed creativity. In other words, if you want to 
solve a problem and you are restrained on how you can solve it, chances 
are you are going to be creative in some way. You have to put your mind 
around the problem, think about it in different ways, and come up with a 
solution that's novel and unique. This perspective is particularly 
interesting if we try to see from the other end of the spectrum: if we can 
solve a problem with any solution (if there aren't limitations to the 
solution), we will certainly come up with something that's not really 
cohesive, or something that's not really a solution to the *particular* 
problem we have, or we might not even solve the problem since we might get 
stuck in the planning phase. Being limited solves this by letting you 
focus on a single problem and make the best use of what you have right 
now. That's why the TIC-80 is so popular with the demoscene, for example. 
(Maybe include a demo here?)

TIC-80's selling point is that its limitations were carefully thought out 
so it looks retro but it's not completely retro. If you have coded for a 
computer in the 80s or 90s, you know it wasn't easy. TIC-80 has made the 
development part simple enough so it's nearly too comfortable. This kind 
of cosy environment reminds of the concept of "Hygge", a danish word 
that's hard to translate but very easy to feel. If this words sounds like 
the english word "hugging", it's because this is the feeling we are 
looking for.

These limitations combined with this cosiness invite the developer and the 
player to a basic mindset. Basic in the sense of "back to basics". Basic 
in the sense of "what is the most essential thing here? What should I 
focus on?" This is a kind of minimalism that's hard to come by but that 
provides a mental framework that lets you think about what you really need 
in your game and make it work properly.

If this is something that interests you, I recommend visiting TIC-80's 
Github repository if you want to get started coding; or the TIC-80's 
website if you want to check what creations people have been coming up 
with using these limitations.

That's all for today!


## Topics for Presentation

- Introduction (from virtualisation to Docker and back to virtualisation)
- TIC-80
- (TIC-80 game?)
- Limitations breed creativity
- Cosy environments foster cosy memories (Hygge?)
- Back to basics
- Conclusion
