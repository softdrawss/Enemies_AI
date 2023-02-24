Hello, my name is Júlia Serra Trujillo and I am a student of the Bachelor’s Degree in Video Games at Centre de la Imatge i la Tecnologia Multimèdia (CITM), at Universitat Politècnica de Catalunya (UPC). 

This page contents information about RPG Enemies AI, their patterns and information about different enemies in games, and has been created for the subject Project II.

# RPG Enemies AI
## 1. Types of AI that can be found in RPGs
For developers, and AI is another tool to use for the development of a videogame. Here we have some uses for it and examples of games that used them:
### 1.1. Image enhancement
Video game graphics may be improved in the second application of image improvement. The basic concept behind the algorithms is to convert a low-resolution picture into something that appears identical but has far more pixels. This method is known as “AI upscaling.”

The AI specialists at the forefront of picture improvement attempt to use a deep learning method. It transforms 3D modeled pictures into realistic photos.  The most sophisticated image improvement AI techniques can convert high-quality synthetic 3D pictures into realistic representations. Grand Theft Auto 5 was subjected to such a technology by creating a network that can great detail recreate the LA and southern Californian environments.

![gta5](https://user-images.githubusercontent.com/99959289/220201604-ac06f9db-85f2-49ba-8a0b-4e912d007cfe.jpg)

### 1.2. Game level generation
Creating a game level is also known as Procedural Content Generation (PCG). These are the names for a collection of techniques that employ sophisticated AI algorithms to generate huge open-world environments, new game levels, and other gaming assets without having to create it manually using human-generated assets and algorithms. This artificial intelligence application reduces lots of time to design and develop and introduces the idea of randomness in your path and improve new scenery in response to the game’s progress. It is mainly used in open world or open map games where they let the player explore huge environments.

No Man’s Sky is an AI-based game with dynamically generated new levels while you play.

![nomansky](https://user-images.githubusercontent.com/99959289/220765068-aef20d8b-a0aa-4bca-98a1-96c1ae618303.jpg)

### 1.3. Scenarios and stories
AI can be employed to generate stories and situations too. This apllication is most often used in interactive narrative games, where users may create or influence a dramatic tale through their actions or what they say. Text analysis is utilized by the AI algorithms, which then produce scenarios based on past narrative experiences.

One of the most well-known examples of this is Dungeon 2. The game uses an OpenAI-developed, open-source text generation technology trained on Choose Your Own Adventure novels.

![dungeons](https://user-images.githubusercontent.com/99959289/220915717-d2eaf597-7339-444b-be40-fa39fd55999b.jpg)

### 1.4. Balancing in-game complexity
Gamers are continuously striving to make their games more immersive and lifelike. However, modeling reality is difficult. A game’s AI algorithms can forecast the consequences of gamer decisions and things like weather and emotions to account for in-game complexity. 

The ultimate team mode in the games series FIFA is a great example of this technology in action. The players’ personalities in a football club are used to calculate a team chemistry score. The team’s mood can vary from bad to wonderful based on game outcomes (losing the ball, making a well-timed pass, etc), and teams with better players can lose against weaker sides because of their morale.

![fifa](https://user-images.githubusercontent.com/99959289/220749760-2213911e-454f-4238-8193-a192d6e44ace.jpg)

### 1.5. Adding intelligence to non-playing characters (NPCs)
The AI of most current games is pre-programmed NPCs. In other games, as the game advances, NPCs become more intelligent and respond to the game environment in innovative and distinctive ways. This makes them more unpredictable and more fun to interact with it.

Many gaming companies are already employing this type of AI in their games, and The Last of Us is one of them. Every character has distinct characteristics, and their reactions will differ depending on your (player’s) decisions. When under attack, non-playable characters may seek assistance from you or ambush your blind spots. It will feel like a real battle, with even your teammates out of ammunition. Characters will exhibit self-awareness and independent thinking, much as in real life.

![thelastofus](https://user-images.githubusercontent.com/99959289/220749937-b82770dc-a5c6-40d5-aabd-bea8a2faeb3d.jpg)


## 2. Enemies and Bosses AI Patterns
The same way we use AI to give personality to NPCs and make them interact towards the player and certain situations, we can program enemies to behave as well so players can engage in what can resemble a real fight.

### 2.1. Enemy Behavior
The main objective for designers when creating enemies is engage the player to fight and feel like (or resemble) a real fight. To do this, they follow certain behaviors known by players that can be easily understood and that are featured in almost every game (with some differences) to help players see what is doing the enemy, and by this create and program their enemies' AI.

#### 2.1.1. Trigger
Appraching the enemy, being too close to them, attacking them without having entered into the combat... Triggers help player undertand that the fight has been iniciated and the enemy or enemies has noticed the player and they will soon attack or react to attacks. It also helps set the player’s expectations for the attack.

Many games feature question marks to show the player is near but the enemy has not noticed yet, and exclamation points when the enemy notices.

#### 2.1.2. Tells
Signifies that the enemy is about to attack the player. This is a key feature for the readability of the combat system, as the tell allows players to recognize that they can either try to avoid the attack, block it, or counter it in some way, and how the player responds will depends on the game and which attack the enemy is using.

Tells have to be clear and distinctive, especially if enemies have more than one attack. Stronger attacks from enemies usually also have more obvious tells, making it easier for the player to respond. The harder it is for players to read these tells, the more difficult the combat becomes. Given a strong warning of an impending attack means that the combat feels more fair. In essence, ‘fairness’ is the key reason for the existence of tells in combat design.

Sometimes the tell is the start of the enemy’s attack animation, which can be the same animation used when we trigger the enemy. Often developers add extra effects, or  colour coded it to make the tells more obvious to the player. Some games also include sound effects.

#### 2.1.3. Idle
When enemies are not attacking, they often move around the player, playing some animation to cheer on the other enemies, or taunting the player. This animation is what we call the idle. This is very important to make it appear as if they are still participating in the fight instead of simply waiting for their turn to attack the player, or they would look static or even glitchy. 

Enemies also try to move around to be on screen (in view of the camera), or switch to the near group before attacking the player.

#### 2.1.4. Defence
In some games, enemies also have the ability to respond to the player’s attacks with a block, dodge, or counter attack. Blocking and dodging can help teach the player which attacks do work and those that do not against specifics enemies without punishing the player for using that attack while explaining the player what has happened. In games where elements are important, usually players can read on the screen phrases such as "No effect", "It's not very effective..." and so on.

Enemies counter-attacking is a more clear, yet unforgiving, way to teach players the same thing. This also strongly increases the difficulty of the game and but is rarely seen or is only presented on higher difficulty settings.

#### 2.1.5. Healthbar 
To help understand the player if they have damaged the enemy, we use another animation to show wheter if the enemy has only been damaged or if they have died. However, to understand how much health the enemy has remaning, developers add a healthbar to enemies once the enemy has been damaged for the first time. This helps players to plan their attacks, see how much damage they do or see if they should escape the fight as their health bar is much lower than the enemy's.

However, not all developers use this feature. Not seeing how much health points the enemy is remaining can create a sense of emergency to kill your enemies before they kill you, and that can be challenging for some users as they are not able to see if killing the enemy is going to take a long time or not. 

In any case, it is good to use a healthbar when we are fighting Bosses who are very challenging and have a big amount of health point in comparison to other enemies who have less strenght, as the absence of it could stress the players and feel that the fight is pointless or not as important as it should be.

#### 2.1.6. Chasing 
Enemies usually try to follow the player when the player tries to leave the fight or when they are in range and have been noticed so the combat can start, or to attack. This keeps players engaged with the fight and strongly encourages them to defeat the enemies. In linear games, enemies follow the player until they reach an obstacle they cannot overcome. In open world games, however, enemies often follow a certain distance from their set patrol area or until the player gets far enough away from them.

To create this effect of chasing, we use algorithms such as A* so the AI can pathfind the player if it is in range or has been noticed, depending on how developers have stablished the enemy's AI and the gameplay.


### 2.2. Types of Enemies
When we try to split enemies into different categories, we tend to think of strenght. Different levels of strenght allows to give the player various levels of challenge and enables them to see how much they progressed when they are putted against the fodder enemies later in the game. Usually in games, the groups are kept evenly spread, with higher groups being smaller because they required more work to create.

Taking in mind the strenght of the enemies is important when developing their AI, but so it is their purpose in the game. Each enemy can have a different role in the gameplay and that will depend when they are introduced, their mechanics, their behaviour, and most important, how the player should react to them. This splits enemies into four major reoccurring roles: Emphasizers, Enforcers, Smashers and Challengers. 

#### 2.2.1. Smashers
Can easily be defeated and allow the player to have fun smashing them up. They are usually the ones that are first introduced to the player when the game starts and can form a basic challenge, specially for new gamers who do not feel confident in their skills.

#### 2.2.2. Emphasizers
Emphasize a certain mechanic. They encourage players to use specific attacks or abilities against them to defeat them, yet at the same time it is still possible to take them out by regular means such as basic attacks. They are meant to test the player’s skill in specific mechanics and are introduced after new mechanics are introduced.

Emphasizers hold the danger of the player not knowing there is a better way to fight the enemy, and that can cause the fight to drag on for too long. To mitigate this risk, it is important to communicate to players what to expect from a different enemy and how to best fight them by using tutorials and taking in mind the learning curve.

#### 2.2.3. Enforcers
They force the player to use only some specific mechanic to defeat them, with the others having little or (more often) no effect. Like Emphasizers, they are meant to test the player’s skill in specific mechanics when new mechanics are introduced, but adding the important part of teaching the players that they can only be defeated with this new skills and that some special attacks do not affect them.

Enforcers must force players to learn how to fight them and also give a feeling of satisfaction when doing it right.

#### 2.2.4. Challengers
Tougher enemies which are meant to challenge the player and test their skills. 


### 2.3. Types of Enemy AI
The enemy AI controls their behaviour (moving, attacking, responding to certain acts, etc). Besides the individual enemy AI, in games where is expected to fight groups of enemies, developers create an AI for the enemy grouping.

#### 2.3.1. Attacking AI
Enemies have at least one attack and often a way to defend themselves, although this varies between games. They can have a number of attacks from a range of only one  to  enemies have multiple attacks with differing variables such as damage dealt. 

Depending it it fits the design of the enemy and the gameplay, developers can choose to add different features in the behaviour of enemies when they attack, such as the duration of the anticipation, hit frames, cooldown, optional added affects when the player is hit, whether if the enemy can interrupt the player's attacks and how the player can defend against it. 

In some games, enemies may attack with a combo, a sequence of rapid attacks, while in others their main attacks consist of one hit or have multiple attacks. Which combination the game uses is generally taught to the player from the start of the game. This is important to set a players expectations and to teach them how to fight against enemies or, in consequence, it can lead to frustation. Games that do not teach the player this progressively are significantly more difficult to learn, and this steep difficulty curve means that they generally appeal to a gaming audience that enjoys tough challenges, so developers should take in mind this point when creating the AI of the enemies to fit the target of the game.

In case the enemy has multiple attack, which the attack that is used can depend on a variety of factors. In most games where this happens this variety is regulated by a context driven decision tree to choose which attack to use, with some randomness included to use stronger attacks more sparingly.

#### 2.3.2. Grouping AI
In several games enemies were split into two groups around the player; one near group and one far group.

- The near group are enemies which are close to the player and form an immediate threat, and it only consists of a few enemies. 
- The far group are enemies which are further away from the player and contains all other enemies.

The separation allows the player to fight the enemies without all of them attacking and it helps both incentivise player movement and to make a small amount of AI enemies fill a space more effectively (which is better visually). Developers use it to control who attacks the player, as only enemies from the near group will attack the player, with enemies from the far group may sparingly use ranged attacks if they are capable of them. The tells of these later attacks are generally more obvious, because the player is usually focussing on the closer group.

These algorithms show that there are other possible ways to prevent enemies from overwhelming the player other than only carefully mixing the Emphasizer, Enforcer, Smasher, and Challenger functions, yet these decisions also need to be integrated with the rest of the combat system and overall intended experience.

#### 2.3.2. Bosses AI
AI for bosses is different from AI for regular enemies and even mini-bosses which appear in different locations, as it is designed specifically for the boss arena bosses tend to have much different attacks to make them distinguishable. The AI can rely on the specific size and shape of the arena as well as on the position in which they appear. 

Regular enemies will be fighting the player in arenas of various sizes and shapes, spawning on various positions. For this reason, the AI for regular enemies cannot rely on these things and has to be more general.


## 3. What to take in mind
**1.** Before design your enemies, have in mind which type of game you are developing. Are talking about games that player and enemies attack in tourns? Will enemies attack in groups or each enemy will be different an attack individually? Designers must think of this before designing the opponents of the player as the behaviours will change accordingly to the game.

**2.** Do your research. How enemies tend to work in games similar to the game you want to develop? How other developers had created the AI of similar enemies of yours?

**3.** Illustrate as possible your idea. Write down the mechanics, create graphs, even draw them if necesary. This will help artists and programmers to create your idea and everyone will have a clear idea of how the enemy works, and it would be helpful when you create the Wiki of the enemies of the gameand get feedback from your teammates. 

**4.** Develop your idea. Think which type of enemy will be (Smasher, Challenger, Emphasizer, Enforcer) and their strenght, and see if the ideas you had for the mechanics and behaviours could fit with their type and strenght.

If you as a designer develop the enemies with the concept art, try to write down all the ideas inspired by the artists' work and see if the type of enemy and strenght fits the art.

Other things to take in mind:

- **OFFSCREEN**: Enemies must attack on screen, almost never off screen. Take this in mind specially when developing 2D games to make enemies be aware of the camera limits or it will result in frustration for players as they will recieve damage without seeing who is attacking.
- **PATTERNS**: Players will engage in the fight if they understand the patterns of the enemies, so when developing think and playtest the patterns to see if they are easy to understand and engaging, rather than too challenging or even boring.
- **PLAYTESTING**: Test the enemies, all the attacks, reactions and movements, specially if one of your game pillars is the fighting. Even if the game is great and features great things such as new mechanics, great visuals and a magnificient soundtrack, if the enemies do not work correctly players will not feel engaged and will avoid fighting as much as possible, or even stop playing the game. 


## 4. Resources
Link of the website: https://softdrawss.github.io/Enemies_AI/

Link of the presentation: https://docs.google.com/presentation/d/1sCu6MVlQada29AXVAuJk4qQ_W8qx_aQjP3KUFh4FCm4/edit?usp=sharing

Chart to create enemies with examples: 

(PDF) https://github.com/softdrawss/Enemies_AI/blob/main/docs/Enemy%20Chart.pdf

(.docx) https://github.com/softdrawss/Enemies_AI/blob/main/docs/Enemy%20Chart.docx

## 5. Links to documentation
https://dataconomy.com/2022/04/artificial-intelligence-games/

https://www.gamedeveloper.com/design/level-design-for-melee-combat-systems

https://www.youtube.com/watch?v=KC-SVc84GfE&t=2946s&ab_channel=ToadintheHole

https://www.gamedeveloper.com/design/level-design-for-melee-combat-systems

https://www.youtube.com/watch?v=KOj87_Bte7g&t=1768s&ab_channel=LazyBlue

https://genshin-impact.fandom.com/wiki/Ruin_Guard

https://www.ign.com/wikis/genshin-impact/Tartaglia_(Childe)_Boss_Fight

https://villains.fandom.com/wiki/Abyss_Mages

https://genshin-impact.fandom.com/wiki/Hilichurl

## 6. Games researched (in alphabetical order)
- Chrono Trigger (1995)
- Cult of the Lamb (2022)
- Deltarune (2018)
- Dungeons 2 (2015)
- FIFA
- Genshin Impact (2020)
- Grand Theft Auto V (2013)
- Guilty Gear Strive (2021)
- The Last of Us (2013)
- No Man's Sky (2016)
- Pokemon Scarlet and Violet (2022)
- Rain World (2017)
- Super Mario Land (1989)
- Super Mario Odyssey (2017)
- The Binding of Isaac (2011)
- The Legend of Zelda: Breath of the Wild (2017)
