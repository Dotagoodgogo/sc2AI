<p align="center"><h1>SC2AI</h1></p> 


<p align="center">
  <img src="https://user-images.githubusercontent.com/87624521/212523904-45972460-5add-4a82-b407-03a40f383894.jpg" alt="StarcraftII">
</p>



## Project Introduction Video
<a href="https://youtu.be/LOzeq64PDas">Project Introduction Video</a>

## Demo_presentation

<a href="https://www.youtube.com/watch?v=AA731G7x-Ak">Starcraft II Bot Presesntation on Youtube</a>

----------------------------------------


1. [Initial intentions and goals](#Initial_intentions_and_goals)
2. [Current Phase](#Current_Phase)
3. [Bot in details](#Bot_in_deatils)
4. [Future goals](#Future_goals)
5. [Conclusion](#Conclusion)



## Initial_intentions_and_goals:
Because addiction for real-time strategy games. Starcraft 2 has always been a game that I love. Although the game has gradually fallen, but he is still the ceiling of real-time strategy games. 2019 Google speaks of research AI environment turned to StarCraft 2 this game, and research Alphastar and Deepmind with amazing ability to beat almost 90% of the players, become a great hit in the field of AI at that time. Meanwhile with the development of AI technology. These are the reasons why I wrote the code for StarCraft 2. Also the goal of writing this code is to take my passion for StarCraft 2 and make a Bot, while incorporating reinforcement learning to make my own intelligent Bot.

## Current_phase:
The code is not easy to write due to the overly complex nature of the game. The current Bot can beat Very Hard StarCraft 2's own computer. But Bot temporary strategy single, mainly has been the main development. If you encounter Rush tactics. My Bot is very easy to beat.

## Bot_in_deatils: 
**Strategy**:
* The general strategy for this bot is expansion and accumlating resources in early opening. Produing large amount of marines,tanks and medivsc and depending on resource advantages to crash enemies.
* Bot will auto attack if opponent is defeated in one battle.

**Construction**:
* SCV(workers) can construct buildings. If area was placed, they can find new spot to build.
<img src="https://user-images.githubusercontent.com/87624521/212524708-fecd8d68-6e60-4dc3-a702-f71ebc92924c.gif" alt="gif1_description" style="display: inline-block;">

* Barracks, factories and starports can grows when resource are aviailable enough.
* A bunker will be placed in front of the second in order to defend rush.
* Command center will be turned into orbital command.
* Orbital command can call mule when they get enough energy.

**Army**:
* The main configuration of the main army is marines,tanks and medivc/
* Army will attack when supply reachs 180.
* Units can detect enemy and defend.
<img src="https://user-images.githubusercontent.com/87624521/212524601-9fe26a46-289f-4700-acd3-51d8547e9c73.gif" alt="gif1_description" style="display: inline-block;">

* All army will be sent to a rally point(fixed).
* The first repear can scout enemies early stages and can retreat when threat is closed.
<img src="https://user-images.githubusercontent.com/87624521/212524439-35c4e436-61b5-4e87-87dc-147c3f6778e8.gif" alt="gif1_description" style="display: inline-block;">
<img src="https://user-images.githubusercontent.com/87624521/212524508-9bb20e84-e83c-4844-a032-25ae1134ab6f.gif" alt="gif2_description" style="display: inline-block;">


* Tanks will be sieged when threat is closing.
* Marines will use stimpacks when they get enough HP.
* Medivic will auto follow the front units and will retreat when they get attack. Healing is automatic.


## Future_goals:
### Some improvements
**Strategy**:
* In StarCraft 2, opponents may employ a variety of different opening strategies. Some common opening strategies include:

  * Rush: Attacking the opponent early on by producing units and building bases quickly in order to gain resource and control advantages.

  * Early Expansion: Securing an early expansion to gain resource advantages and more production capabilities.

  * Harassment: Launching small-scale attacks to disrupt the opponent's production and resource gathering.

  * Defense: Building fortifications and reinforcing defensive units to hold off opponent's attacks.

  **Suggestions**: The bot should develop more strategies to face opponents' opening starategies and should pick the optimal one to confront.

**Construction**:
* Bot should figure out the best place itself to construct buildings. (it is really useful when bot encounter zerg race.)
* Buildings should figure out when and how to use their abilites. some examples include:
  * Orbital command contains mule and radar. Mule is for minerals collection and radar is for scouting and anti-cloaked.
  * Barracks, Factories, Starports contains different tech lab and reactor labs. These buildings should exchange their add-ons in some cases.
  * Bunkers should decide when to collect marines or release them.
  * Each buildings should train correct units in different cases.
* Bot should figure out what is the best ratio between factories, barracks and starports.
* Buildings should lift up in some cases

**Army**:
* Army should contains more units in order to face different opponenets
* Each unit should figure their own combat modes and enhance combat abilities. For example:
  * My demo:


    <img src="https://user-images.githubusercontent.com/87624521/212525936-9db1b5fa-6fae-4258-ab8d-8e705f5b2711.gif" alt="gif1_description" style="display: inline-block;">
  * Nice example:


     <img src="https://user-images.githubusercontent.com/87624521/212525974-29f6151f-7467-481a-a70e-e94d34490d3c.gif" alt="gif1_description" style="display: inline-block;">
     
     
     
## Conclusion:

StarCraft II is a good game for training AI for several reasons:

* Complexity: StarCraft II is a highly complex game with a large number of units, abilities and strategies. This complexity makes it a challenging environment for AI to learn and adapt in.

* Real-time: StarCraft II is a real-time game, which means that actions happen in real-time, and the AI must be able to make decisions quickly and efficiently.

* Imperfect information: In StarCraft II, the player does not have complete information about the state of the game, such as the location of the opponent's units. This makes it difficult for AI to make decisions based on incomplete information, which is a problem that AI also faces in the real world.

* Micro-management: StarCraft II requires players to micromanage their units, which can include things like controlling the movement of individual units, managing resources, and building structures. This requires the AI to learn how to manage resources, multitask and make quick decisions

* Strategic and Tactical aspects: The game includes both strategic and tactical elements, which allows for the AI to learn to plan ahead and adapt to changing situations.



Applying reinforcement learning will be my next step to perfect my bot. This is also the most difficulty I am facing to. Hoepfully, I can handle and continue develop my bot through my future learning.
