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
The same way we use AI to give personality to NPCs and make them interact towards the player and certain situations, we can program Enemies to behave as well so players can engage in what can resemble a real fight.

### 2.1. Types of AI found in enemies
The enemy AI controls their behaviour (moving, attacking, responding to certain acts, etc). Besides the individual enemy AI, in games where is expected to fight groups of enemies, developers create an AI for the enemy grouping.

#### 2.1.1. Enemies Attacking AI
Enemies have at least one attack and often a way to defend themselves, although this varies between games. They can have a number of attacks from a range of only one  to  enemies have multiple attacks with differing variables such as damage dealt. 

Depending it it fits the design of the enemy and the gameplay, developers can choose to add different features in the behaviour of enemies when they attack, such as the duration of the anticipation, hit frames, cooldown, optional added affects when the player is hit, whether if the enemy can interrupt the player's attacks and how the player can defend against it. 

In some games, enemies may attack with a combo, a sequence of rapid attacks, while in others their main attacks consist of one hit or have multiple attacks. Which combination the game uses is generally taught to the player from the start of the game. This is important to set a players expectations and to teach them how to fight against enemies or, in consequence, it can lead to frustation. Games that do not teach the player this progressively are significantly more difficult to learn, and this steep difficulty curve means that they generally appeal to a gaming audience that enjoys tough challenges, so developers should take in mind this point when creating the AI of the enemies to fit the target of the game.

In case the enemy has multiple attack, which the attack that is used can depend on a variety of factors. In most games where this happens this variety is regulated by a context driven decision tree to choose which attack to use, with some randomness included to use stronger attacks more sparingly.

#### 2.1.2. Enemies Grouping AI



### 2.2. Enemy Behaviour
The main objective for designers when creating enemies is engage the player to fight until a reward is given and feel like a real fight.

#### 2.2.1. Trigger
Appraching the enemy, being too close to them, attacking them without having entered into the combat... Triggers help player undertand that the fight has been iniciated and the enemy or enemies has noticed the player and they will soon attack or react to attacks.

#### 2.2.2. Tells
Signifies that the enemy is about to attack the player. This is a key feature for the readability of the combat system, as the tell allows players to recognize that they must dodge, prepare to defend or attack before the enemy attacks, and how the player responds depends on the game and which attack the enemy is using.

; in general, the player can either try to avoid the attack, block the attack, or counter attack in some way.

Tells have to be clear and distinctive, especially if enemies have more than one attack. Stronger attacks from enemies usually also have more obvious tells, thus making it easier for the player to respond. The harder it is for players to read these tells, the more difficult the combat becomes, but the feeling that the player is being given a strong warning of an impending attack means that the combat feels more fair. In essence, ‘fairness’ is the key reason for the existence of tells in combat design.

In general the tell is the start of the enemy’s attack animation, which is also used to set the player’s expectations for the attack. Often extra effects, possibly colour coded, are added to this to make it more obvious to the player. Some games also include sound effects, for example DmC, but this is not common, especially for standard-strength attacks when compared to the less-common powerful attacks.

#### 2.2.3. Idle


#### 2.2.4. Dodge


#### 2.2.5. Healthbar 
To help understand the player if they have damaged the enemy, we use another animation to show wheter if the enemy has only been damaged or if they have died. However, to understand how much health the enemy has remaning, developers add a healthbar to enemies once the enemy has been damaged for the first time. This helps players to plan their attacks, see how much damage they do or see if they should escape the fight as their health bar is much lower than the enemy's.

However, not all developers use this feature.

### 2.3. Types of Enemies
When we try to split enemies into different categories, we tend to think of strenght. Different levels of strenght allows to give the player various levels of challenge and enables them to see how much they progressed when they are putted against the fodder enemies later in the game. Usually in games, the groups are kept evenly spread, with higher groups being smaller because they required more work to create.

Taking in mind the strenght of the enemies is important when developing their AI, but so it is their purpose in the game. Each enemy can have a different role in the gameplay and that will depend when they are introduced, their mechanics, their behaviour, and most important, how the player should react to them. This splits enemies into four major reoccurring roles: Emphasizers, Enforcers, Smashers and Challengers. 

#### 2.3.1. Smashers
Can easily be defeated and allow the player to have fun smashing them up. They are usually the ones that are first introduced to the player when the game starts and can form a basic challenge, specially for new gamers who do not feel confident in their skills.

#### 2.3.2. Emphasizers
Emphasize a certain mechanic. They encourage players to use specific attacks or abilities against them to defeat them, yet at the same time it is still possible to take them out by regular means such as basic attacks. They are meant to test the player’s skill in specific mechanics and are introduced after new mechanics are introduced.

Emphasizers hold the danger of the player not knowing there is a better way to fight the enemy, and that can cause the fight to drag on for too long. To mitigate this risk, it is important to communicate to players what to expect from a different enemy and how to best fight them by using tutorials and taking in mind the learning curve.

#### 2.3.3. Enforcers
They force the player to use only some specific mechanic to defeat them, with the others having little or (more often) no effect. Like Emphasizers, they are meant to test the player’s skill in specific mechanics when new mechanics are introduced, but adding the important part of teaching the players that they can only be defeated with this new skills and that some special attacks do not affect them.

Enforcers must force players to learn how to fight them and also give a feeling of satisfaction when doing it right.

#### 2.3.4. Challengers
Tougher enemies which are meant to challenge the player and test their skills. 


## 3. What to take in mind
- OFFSCREEN: Enemies must attack on screen, almost never off screen. Take this in mind specially when developing 2D games to make enemies be aware of the camera limits or it will result in frustration for players as they will recieve damage without seeing who is attacking.
- PATTERNS: Players will engage in the fight if they understand the patterns of the enemies, so when developing think and playtest the patterns to seeif they are easy to understand and engalling, rather than too challenging or even boring.
- PLAYTESTING: Test the enemies, all the attacks, reactions and movements. 
- REGULATED ATTACKS: Enemies must not attack all together, and that should be regulated. For example, if the player is encountering a group of enemies, if they attack at the same time the player would recieve loads of damage that could hurt them of kill them and that would frustrate the player. In order to avoid this, attacks must be regulated so the player can have time to move or act between one attack and another.


## 4. Links to documentation
https://dataconomy.com/2022/04/artificial-intelligence-games/

https://www.gamedeveloper.com/design/level-design-for-melee-combat-systems

https://www.youtube.com/watch?v=KC-SVc84GfE&t=2946s&ab_channel=ToadintheHole


## 5. Games researched (in order)
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
