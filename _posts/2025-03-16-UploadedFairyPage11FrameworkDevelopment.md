---
title: "Uploaded Fairy Page 11, Why I Cant Stand Framework Development For Those Whom Despise Innovation"
author: "S.R. Weaver / Numerhex / L.W. Flouisa"
tags: roguelikes rpslikes webcomic
---
## Uploaded Fairy Page 11
![Uploaded Fairy Page 11]()

## Why I Cant Stand Framework Development For Those Whom Despise Innovation
Object-oriented-programming does not work for my specific use case. Technically the way that it’s suppose to work is that you have four Biome modules, and in each biome you have classes for each object relevant to your specific biome: plants, animals, and Rocks. Cats would do everything an animal cat, plus their own unique functions. Bananas everything a plant can. So the theory goes that you only use instance variables that pertain to each class, and local variables for specific functions.

The underlying problem with this that it creates for extremely bloated code, when having one file whose specialty is a specific functions works just fine for the vast majority of use cases. The only time you really need to do object-oriented programming is when you need to create a bunch of libraries used for a game design framework. But for the actual game you would generally do all this work, rather you would rely on existing libraries that have already created specific functions for your job.

The underlying problem is for my specific programming task, I’m having to essentially build an entire library for my specific task, because apparently nobody has made a comprehensible game library geared toward making roguelikes in Ruby. There is absolutely plenty of this in C++ and Python. 

Or rather, I was going to go the Roguelike route, except that’s the other issue. The cult of the roguelike is so profoundly stuck in their ways, that it really does not make it an absolute joy to program for these types of people, but they seem to have an extreme disdain for new innovations in computer games, for instance:

I’m wanting to create a map structure for Hexagonal map navigation, to be more in line with graphical Strategy games, which means having a map that looks slightly different from your standard Roguelike. This would essentially mean going against the grain. In other words, i would have to subject myself to object-oriented programming, just to appease a crowd that is notorious for not being pleased about anything.


This is why I’m going to be moving more in the direction of RPS-Like rather than Rogue-Likes, which would have its own genre-specifics for how it implements things. As at this point I’m mainly developing this framework for my own specific needs, which is rapidly diverging from the needs of Roguelike development.

I’ll do an article on the specific ways RPS-Likes differ from Roguelikes at a later point.
