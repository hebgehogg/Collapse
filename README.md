# Collapse!
First-person shooter / Unreal Engine 4



## Team : Naughty Gods. 
* Alina Ovchinnikova БПИ185
* Vadim Maksimov БПИ185
* Roman Piskunov БПИ185 

# Design doc

### History 
For 300 years, the inhabitants of the planet Earth from different parts of the world have been sending technologies into space in the hope that extraterrestrial technologies will improve what is already there. Several decades after the first clear response from extraterrestrial civilizations, the United States, Russia and China joined forces to create a mobile space station. As a result, something happened and the Moon split into several pieces, which caused a rain of moon debris to fall on the Earth. Only 3 % of people survived. After 150 years, a girl warrior decided to go out into the world. What she saw was that the world his parents had told him about was even more beautiful than he had thought. All thanks to the fact that nature has restored its beauty. However, as Artemis (the heroine) settled into the new world, so did the rest of the survivors, who did nothing but fight for life in the bunkers that had been their home for more than 100 years. Naturally, many did not change and decided to take everything for themselves. The rest just went into the woods, but it was not so simple - the main figure of the criminal world of bunkers - Bongo decided to take the nearest territories to his hands and captured Leonardo's relatives. And so begins the story of Artemis – explore the world. The main goal is to destroy enemies and complete destruction missions, participate in 1 vs gang fights and the like. Meanwhile, it is discovered that there are already inhabitants on earth who have arrived from other universes.  

Civil war on earth in 2846, for the extraction of resources on other planets, the inhabitants were divided into 4 factions, where the first is the rebels, the second are monarchists, the third is a humanoid "settled" race, the fourth is mercenaries, the world is in ruin, there is not enough money for food, there is no electricity in many areas, people can no longer walk safely on the streets, and everyone is struggling to survive. 

The player is offered a list of heroes, each has its own story, at the beginning of the creation of the game one character will be added - the renounced imperial daughter, according to history, her father killed her mother because she refused to support the idea of ​​war, our heroine subsequently decided to leave home and became the leader the rebel army. Now she is saving for her people.   

The list of heroes will expand as the game develops.  


## Concept: 
Platforms: Windows  
Technologies: Unreal Engine 4  
Languages:  Russian, English   
Genre: First-person shooter  
Emotions:  relieving stress after work / school day  
Rating:  12+  
User Number:  Single-player  
Gameplay time:  About 20 minutes  
Maine mechanic:  Shooting  
Setting:  Several locations to choose from  
Goal: 10 won round  


## Mood
See information about mood by this link:  
https://miro.com/app/board/o9J_kkCb3cI=/?moveToWidget=3074457350601321897&cot=12  

### Targeted audience  
* Age: The average age of players is between 12 and 25, because the game involves the development of cybersport disciplines.
* Gender: 50/50.
* Social Class: mainly players are people of middle social class, because the game requires some «power» of the game computer.
* Taste: mainly this game for people who after work/study want to vent «pairs» and relax, they like to be «ahead of the opponent», so the competitive aspect is very appropriate. Usually, these people don’t have enough action in their lives, that’s why they come to play.


## Game Character 
Game mechanics and operating  
Actor moving player can control the character using keys «WASD», the game is played from a first-person perspective, there’s a possibility of running on the Shift button. A single jump is performed with 1 press space, and a double jump with a double press. When you press the Ctrl button, the character squats, and if you press Ctrl when you move, the character slips through. LBM – shoot. Additional abilities are placed on the "FEQRT" keys, depending on the hero.

In the beginning it is planned to add only one character with 1 ability and shooting ability, and in the development of the game the number of characters and abilities will increase.


## Interface
Three-dimensional space. It is planned to add sound elements and voice-over characters.
The interface prototype (developed by us) is presented below:  

In the main menu, the player can select the game mode and customize the game. There is the game also starts.

Also user can use tab-weapon for purchase weapon and armor.
Gameplay map
> Карта игрового процесса не полная:  

https://miro.com/welcomeonboard/jSHGMntPnbDQDv1Ira0hcPupsQvQ6PWOADDAqECzgSdOb2rdt3dznseNHjWowqst


## Level Design
* Number of rounds: from 10 to 19.  
*  Level structures in the game: the player and the enemy are loaded onto the map, the map is limited, guards take place on it, an example of a similar setting of the level is maps in cs go.
* Restrictions: the game time is not limited, the number of enemies is limited (1 on 1), the resonage can move all over the map, it cannot walk through objects.
* Goal level: when a player enters the game, he does not have a rating, having played 10 games, the system determines the level of being able to play and gives a starting rating figure, with each victory +25 is added to the rating, with each loss -25. This allows you to match players by rating, you need to balance.


> This game will be three-dimensional and will have a certain set of locations.  
The game plans to introduce the ability to select a map for the gaming and add different modes:
1. Dynamic game – the player plays on a random map
2. Fast game – 2 times less rounds


## Balance

> Player

| Name | Value | Comment |
| ------------- |:------------------:|:------------------:|
| Quantity of cartridges | ∞ | none |
| Running speed | 6 m/s | none |
| Movement speed| 3 m/s | none |
| Hero's life size № 1 | 600 hp | none |
| The size of damage from a knife | 100 hp | none |
| The amount of damage from the gun (in the torso) | 150 hp | From 1 bullet |
| The amount of damage from hitting the head with any type of weapon | 600 hp | none |
| The amount of damage from the machine | 60 hp | From 1 bullet |
| The amount of damage in the case of hand-to-hand combat | 60 hp | From a single hit |

> NPC №1 - similar to character №1

## Artificial Intelligence
NPCs appear when there are not enough players in the session, and if the player wants to play on the "polygon", then the polygon is developed first, and then multiplayer. It is planned to develop a unique algorithm for the behavior of the hero, which will create a feeling of fighting with a real player, the complexity can be configured - 3 levels of difficulty. Each of the levels implies an increase in the damage dealt and the characteristics of how the NPC moves. 
