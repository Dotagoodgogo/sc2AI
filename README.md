<p align="center"><h1>SC2AI</h1></p> 


<p align="center">
  <img src="https://user-images.githubusercontent.com/87624521/212523904-45972460-5add-4a82-b407-03a40f383894.jpg" alt="StarcraftII">
</p>


## Demo_presentation

<a href="https://www.youtube.com/watch?v=AA731G7x-Ak">Starcraft II Bot Presesntation on Youtube</a>

----------------------------------------


1. [Initial intentions and goals](#Initial_intentions_and_goals)
2. [Current Phase](#Current_Phase)
3. [Bot in details](#Bot_in_deatils)
4. [Future goals](#Future_goals)



## Initial_intentions_and_goals:
Because addiction for real-time strategy games. Starcraft 2 has always been a game that I love. Although the game has gradually fallen, but he is still the ceiling of real-time strategy games. 2019 Google speaks of research AI environment turned to StarCraft 2 this game, and research Alphastar and Deepmind with amazing ability to beat almost 90% of the players, become a great hit in the field of AI at that time. Meanwhile with the development of AI technology. These are the reasons why I wrote the code for StarCraft 2. Also the goal of writing this code is to take my passion for StarCraft 2 and make a Bot, while incorporating reinforcement learning to make my own intelligent Bot.

## Current_phase:
The code is not easy to write due to the overly complex nature of the game. The current Bot can beat Very Hard StarCraft 2's own computer. But Bot temporary strategy single, mainly has been the main development. If you encounter Rush tactics. My Bot is very easy to beat.
For the time being, I have not used reinforcement learning to let Bot judge various response strategies in complex situations by itself.

## Bot_in_deatils: 
**Strategy**:
* The general strategy for this bot is expansion and accumlate resouce in early. Produing large amount of marines,tanks and medivc and depending on resouce advantage to crash enemy.
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
  ![第一次](https://user-images.githubusercontent.com/87624521/212525936-9db1b5fa-6fae-4258-ab8d-8e705f5b2711.gif)
  * Nice example:
  ![a16e6e6fjw1f8ro1500n8g20b406ye83](https://user-images.githubusercontent.com/87624521/212525974-29f6151f-7467-481a-a70e-e94d34490d3c.gif)

 



----------

## 初衷和目标：
出于对即时战略类的游戏的热爱。星际争霸2一直是我热爱的一款游戏。虽然游戏已经逐渐没落，但是他还是即时战略类游戏的天花板。2019年谷歌讲研究AI环境转向星际争霸2这款游戏，并且研究出了Alphastar 和 Deepmind 以惊人的能力几乎可以击败九成玩家，成为当时AI领域很大的热门。同时随着AI科技的发展。这些是我写星际2代码的原因。同时写这代码的目标是希望把我对星际争霸2的热情制作成一个Bot,同时融入强化学习来制作出我自己的智能Bot.

## 现在的阶段：
由于游戏过度复杂的情况，代码是不容易写出来的。目前的Bot可以击败Very Hard 星际争霸2自己的电脑。但是Bot暂时策略单一，主要已发展为主。如果遇到Rush战术。我的Bot是很容易被击败的
暂时还没有运用强化学习来让Bot在复杂的情况自己判断各种应对策略。

## 未来目标:
我会继续发展Bot的战略，同时强化学习会将引入。希望可以做出我自己的AI
