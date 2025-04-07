---
title: "Uploaded Fairy Page 11, Why I Cant Stand Framework Development For Those Whom Despise Innovation"
author: "S.R. Weaver / Numerhex / L.W. Flouisa"
tags: roguelikes rpslikes webcomic
---
## Uploaded Fairy Page 11
![Uploaded Fairy Page 11](https://github.com/LWFlouisa/UFBlog/blob/main/images/Pages/page11.jpg?raw=true)

## Anne Boleyn At Vampire Non
A riff on Anna Boleyn At High Noon.

<iframe title="Anne Boleyn At Vampire Noon" width="560" height="315" src="https://video.ploud.jp/videos/embed/b2696fce-199c-437a-a487-43e1fe48261f" frameborder="0" allowfullscreen="" sandbox="allow-same-origin allow-scripts allow-popups allow-forms"></iframe>

## Why I Cant Stand Framework Development For Those Whom Despise Innovation
Object-oriented-programming does not work for my specific use case. Technically the way that it’s suppose to work is that you have four Biome modules, and in each biome you have classes for each object relevant to your specific biome: plants, animals, and Rocks. Cats would do everything an animal cat, plus their own unique functions. Bananas everything a plant can. So the theory goes that you only use instance variables that pertain to each class, and local variables for specific functions.

The underlying problem with this that it creates for extremely bloated code, when having one file whose specialty is a specific functions works just fine for the vast majority of use cases. The only time you really need to do object-oriented programming is when you need to create a bunch of libraries used for a game design framework. But for the actual game you would generally do all this work, rather you would rely on existing libraries that have already created specific functions for your job.

The underlying problem is for my specific programming task, I’m having to essentially build an entire library for my specific task, because apparently nobody has made a comprehensible game library geared toward making roguelikes in Ruby. There is absolutely plenty of this in C++ and Python. 

Or rather, I was going to go the Roguelike route, except that’s the other issue. The cult of the roguelike is so profoundly stuck in their ways, that it really does not make it an absolute joy to program for these types of people, but they seem to have an extreme disdain for new innovations in computer games, for instance:

I’m wanting to create a map structure for Hexagonal map navigation, to be more in line with graphical Strategy games, which means having a map that looks slightly different from your standard Roguelike. This would essentially mean going against the grain. In other words, i would have to subject myself to object-oriented programming, just to appease a crowd that is notorious for not being pleased about anything.


This is why I’m going to be moving more in the direction of RPS-Like rather than Rogue-Likes, which would have its own genre-specifics for how it implements things. As at this point I’m mainly developing this framework for my own specific needs, which is rapidly diverging from the needs of Roguelike development.

I’ll do an article on the specific ways RPS-Likes differ from Roguelikes at a later point.

## Updates In Enemy AI Enhancements
These are formulas I've development for moving on from stupid enemy AI to slightly less stupid Enemy AI for games. Note this is only ever meant to be used for games, and not anything else.

### BASIC FORMULA
Basic formula for rock-paper-scissors.
~~~
Given a chart of 3x3, stalemate happens exactly 3 times.
From remembered player actions, find an ideal candidate.

Compare generated state based on rows and collumns.
  ( If result matches generated pathway
    declare that player's actions has been countered.
    make this the computer's choice

    ( if computer is correct        [ Player loses hp ]
    ( Else if computer is incorrect [ Enemy loses hp ]

  ( Els if result doesn't match pathway
    continue searching until generated result matches ideal candidate.
~~~

### LARGER DATASETS
Solutions for larger datasets.
~~~
Given a chart of 14x14, stalemate happens exactly 14 times.
From remembered player actions shuffled, find an ideal candidate. [ Shuffling remembered datasets reduces chance for error. ]

Compare generated state based on rows and collumns.
  ( If result matches generated pathway
    declare that player's actions has been countered.
    make this the computer's choice

    ( if computer is correct        [ Player loses hp ]
    ( Else if computer is incorrect [ Enemy loses hp ]

  ( Els if result doesn't match pathway
    continue searching until generated result matches ideal candidate.
~~~

## Toward A Different Programming Paradigm
This is something I've been wanting to development as a slightly different way of programming, which may evolve into a DSL.

### French Specific
~~~
fonc cette_pomme_et_jaune:
  cette "le pomme" == rouge, mais cette "le banane" == jaune:
    parle("That apple is: '); lisen(rouge).
    parle("That banana is: '); lisen(jaune).
  sinon:
    parle("All else is needs not be written.").
  fin
fin
~~~

Suppose this was a French dialect of that-but that-otherwise. The idea here is some things would be in Francais, and otherwise in Nihongo for things that have no equivalent in Francais. Talk me only in English please.

### Japanese Specific
Shouganai   - Cannot be helped / avoided.        Ex. cette "guillotine" == shouganai; parle("Je suis mort"); mort<br />
Wabi-Sabi   - Finding beauty in imperfection.    Ex. In Fruby, "wabisab", or avoid correcting a dataset when the only change is stylistic.<br />
Boketto     - Gazing vacantly into the distance. Ex. In Fruby, this would be used as a verb: to "a bokette", or "to look into" implying a sleep condition before reading.<br />
Fuubutsushi - Anticipate a shift in the dataset that evoke a particular feeling. Ex. Predict sensationalism.<br />

~~~
fubu(rouge). # records state of rogue.
fubu(jaune). # records state of yellow.

wabisab rogue et jaune:           # If change to code is stylistic, maintains to avoid breaking.
  bokette(rouge); bokette(jaune). # Read file with a sleep condition.
shouganai:                        # If breakage unavoidable, isolates it to a folder that isn't otherwise used..
  mod(rogue); mod(jaune).         # Modifies files to avoid conflicting with other datasets.
~~~

## Proposed But Not Considered
~~~
fonc calculer_somme:
  cette nombre = 0
  pour chaque element dans liste:
    si element > limite:
      mort  # Terminates loop early
    nombre += element
  fin
fin
~~~
