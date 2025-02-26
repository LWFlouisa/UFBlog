---
title: "Uploaded Fairy Page 8, Emelie's Train, Healing As A Complex State Machine, Yoda Nots Conditionals"
author: "S.R. Weaver / NumeroHex"
tags: uploadedfairy emeliestrain healingstatemachine yodanots
---
## Uploaded Fairy Page 8
![page8](https://raw.githubusercontent.com/LWFlouisa/UFBlog/refs/heads/main/images/Pages/page8.jpg)

## Emelie's Train
Riding in a train was an experience that Emelie had not had before. She always assumed that it would be louder, with constant talking at the rhythm of a cigarette butt. But there was only silence. Her sister Alain was reading her eReader device, pay not much attention to either Emelie staring out of the window. Or the waiter placing snack peanuts on their table. It was her favorite book, two little platypuses. “So are you looking forward to being at out new home?” said Emelie. But her little sister had no answer, only the answer of a swipe with her finger across the moving screen.

The girls stepped out of the train. Sound of their wooden heels tapping the pavement, they walked out in resistance to the moving wind. “Everything is going to be fine,” said Emelie. Both of the girls were greeting by their father. A man in    formal office get up, and a berret. Scratched up glasses. “Surely nothing bad will happen, its only been around for the last one hundred years.” She said this in order to relief her sister, who was biting her nails as if she had not had breakfast. Emelie turned around to her father. He looked at her as if she were a bother.

“If I hear one more word about the house.” said the father. But his eldest daughter was quick to hop up, and kiss him on the cheek.

“I wasn’t, just trying to calm Alain.” said Emelie.

“She can handle herself.” said the father.

Emelie arrived at her home away from the station, a few blocks down the road. Where children were playing with their jump ropes, and the clatter of wooden heels being loud enough to irritate her ears. They arrived at a small apartment flat. It was cracked and torn. “This place is going to need a fixer upper,” said the father, who gently rubbed his index finger along the wall. “now go on inside I’m getting cold.” They went inside of the flat, and was greeted by a spiral stair case. The kitchen was in the entrance along the right wall. A smell of unvanished wooden floor filled Emelie’s nose.

The next day of school, Emelie met Andie in class. While the other boys wore a brown uniform, he always wore a black uniform. It was a wonder he didn’t complete the get up, with a red rose squirting acid. Like some sort of strange twisted demented clown. He was still writing definitions in his textbook, and Emelie couldn’t resist trying to talk to him. But he would not listen, nobody listened to Emelie. Instead she began to drift off, and that was her first introduction to the board of education. Even if the teacher got fired for it, it was something that would go into her permanent grade down on a school review site on her eReader. Simple enough to use a proxy, to evade the schools website blocker.

But it was the next night that would put her eReader in jeopardy. Emelie decided to call up the night before about asking Andi about possibly taking a walk with her into the woods the next night. He was at first hesitant, it was at first homework, then it was school club. “Just say you don’t want to travel with me, or are you a little chicken about the unknown.” And of course Andi wouldn’t take that, so thats how that got to be here right then. Walking through the woods, they paused to look at an old storage house. Possibly left over from the last war. “They say the spirits of the soldiers still haunt this groun.” said Emelie.

“Are you kidding? Those are just stories.” said Andi.

As much of a story as, a mural on the tree. But the murals on trees, were appearing on the trees. Like some invisible entity had decided to place a curse on the woods. Emelie wanted to leave, using her GPS. But Andi wanted to stay behind, and touch the murals to see what would happen. She tried to get him to not touch the strange figures. But it was to much, he had already poked them with his index finger. Andi could feel himself growing ill, like something had poisoned him. Emelie took the blame, and went without her eReader for about a week. Well she would, if she didn’t get it while her father was away at work.

Andi couldn’t come with her as he was to sick to go. Something about some sort of strange illness he developed from the event. So she went alone. Emelie could hear the sounds of chants, but she wasn’t sure where they were coming from. And then strange figures, little girls with skull-masks and strange types of guns eased out of the odd murals. To her mind she compared it to cyberspace, but there was no evidence of any sort of connection, and besides no monitor. “Who are you, what do you want?” said Emelie, but she was answered with an electrical pulse gun.

At eternity later, easing vision. Emelie was in a strange room, surrounded by the odd skull-faires. “We never captured a live one before, I wonder if keeping her alive long enough with effect her taste.” said one of the little skull-faires.

“Doesn’t matter, she’s one of us now.”

And then Emelie woke up beside the tree.

Emelie went to go visit Andi in the hospital the next week end, and he was slowly beginner to recover. He mentioned how after he touched the strange mural, he had visions. Saw strange girls that were about both of their ages, about thirteen. “Do you remember what they look like?” said Emelie. But Andi was already to unconcious to make any speech that made sense to her. She got home, and was still pissed at her father for breaking her eReader. He promised to get her another, after she was no longer grounded. Emelie was half way tempted to go without her GPS system. And continue to investigate the matter further on her own.

Then Emelie went missing for a week.

When Andi was beginner to recover, her called up her father to see how Emelie was doing. He had not seen or heard from Emelie over the past week, and his neighborhood was caught up in trying to file a missings person report. He wanted to investigate the matter himself, but wasn’t sure how to get past the yellow tape around the forest green. Andi simply play eReader games until he figured out what to do.

Emelie was still around of course, locked in time and space. She was drifiting along the sands of grey, walking eternally during the month of May. And became one of the stars during the night, and would soon meet Andi again for other reasons. To drag take him with her, after dying from alcoholic poisoing. He had never managed to get a date, and by fate they held their hands together. After he walked through the purgatory gate. Into the eternal twilight, of the sands of grey.

The land of skull-fairy manifest.

## Healing Mechanics As Intrasitive State Machine
In continuation my working theory about primary and secondary gameplay features, my style of Rock-Paper-Scissors includes an HP system, incremented by healing and decremented by healing. There is no formal way of leveling up, rather you level up your monster pet, that can enhance their HP, ATK, and healing abilities.

But I'm in the process of fleshing out healing mechanics into its own Intransitive State Machine, between Spider, Pig, and Farmer. The pig eats the spider, the farmer eats the pig, the spider bites the farmer. Depending on whether you land on spider, pig, or farmer determines whether you're able to heal or whether your spider pet is able to heal. Landing on the same state as the enemy, means while you lost the opprotunity to heal, you also take no further damage.

If the enemy scores a hit, that branches into a seperate state machine determining whether they successfully heal themselves. If you score a hit ( by landing on a farm stronger than the other ) you have an opprotunity to heal. This makes it so that healing isn't just a free-for-all, and there are limitations to how much you can heal in any one battle.

This is primarily relevant for exploration, rather than when staying at inns or graveyards, where you will still be able to completely heal if you manage to rest.

## Yoda Nots
Yoda Nots are not conditionals in Ruby that follow a Yoda-like conditional syntax, as a form of constraints within a random number generator. Later as I shift gears for developing my own Text Parser, this will be the syntax I will use for conditionals:

~~~ruby
three = 3

if not 3 == three
  puts "This is not the number three."
else
  puts "This is the number three."
end
~~~

The use case here is that sometimes you want to explicitely tell ruby what not to generate rather than exclusively what to allow, such as placing limits for an RNG for procedural dungeon generation. Not that the map generated using this method still needs to be edited. But I'm also in the process of finding a more sustaining alternative to procedural dungeon generation:

~~~ruby
# learn player map preferences
# from learned preferences:
#   choose a random behaviour based on constraints.
#

previous_explored_maps  = File.readlines("lib/data/world/explored_areas.txt")
shuffled_explored_areas = previous_explored_maps.shuffle
starting_map_vector     = File.read("lib/data/world/starting_map.txt").strip.to_i

size_limit = previous_explored_maps.size.to_i

size_limit.times do
  def level_1
    # Send player to easy map.
  end

  def level_2
    # Send player to less easy map.
  end

  def level_3
    # Send player to slightly harder map.
  end

  def level_4
    # Send player to challenging map.
  end

  def level_5
    # Send player to trechorous map.
  end

  current_map = shuffled_explored_areas[starting_map_vector]

  if    not "level_1" == current_map
  elsif not "level_2" == current_map
  elsif not "level_3" == current_map
  elsif not "level_4" == current_map
  elsif not "level_5" == current_map
  else
    settlement
  end
end
~~~

This might seems like a small difference, but what it means in practice is rather than a map being chosen at random, the game will track what type of map the player prefers to play it, and dynamically adjusts the difficulty setting based on what their own personal play preferences are. This differs from procedural content generation in that rather than choosing something at random, the game tracks what the player prefers over time.
