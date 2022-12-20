### [Secrets of Game Feel and Juice](https://www.youtube.com/watch?v=216_5nu4aVQ) 🧨
Add visually appealing effects, indicators (dust particles when player hits ground, recoil, bassy sound effects, big bullets)
![](assets/GMTK%20notes/images/effects%20from%20game.png)  
Screen shake is important (firing, hitting enemy)
pause few frames when hitting enemy.
make the player feel that he is damaging the enemy. (animation, blood, paint white, sound)
make the player feel the previous chaos he did.

### [How to make a good platforming character (Developing 6)](https://www.youtube.com/watch?v=ep_9RtAbwog) 🧨
*talks about good pre made player controllers*
![](assets/GMTK%20notes/images/acceleration%20graph.png)  

snappy jump
![](assets/GMTK%20notes/images/jump%20graph.png)  

implement jump buffer so player can jump when he is near the floor.
![](assets/GMTK%20notes/images/jump%20buffer.png)  

implement coyote time so player can jump at the edge
![](assets/GMTK%20notes/images/coyote%20time%20celeste.png)  

implement short hop for single jump key and long jump for holding key

animate the character like bending while running (player and object personality is important)

Decide when to add accessibility option

### [The Genius of Prey's Gloo Cannon](https://www.youtube.com/watch?v=aJ9x3AtGADM&ab_channel=GameMaker%27sToolkit) 🧨
Signature weapon of the game. Can freeze the enemy with gloo.
Can create stair with gloo
![](assets/GMTK%20notes/images/gloo%20stair%20game.png)  

Concept can be used in 2D game too.
![](assets/GMTK%20notes/images/2d%20gloo%20game.png)

Restricted the player to create wall and sticking gloo on top of gloo to reduce memory use.


### [Shovel Knight's Signature Moves](https://www.youtube.com/watch?v=8fjCKMIE1Pg&ab_channel=GameMaker%27sToolkit) 🧨

#### Shovel knight
Shovel can be used to jump around and kill enemies.

#### Plague knight
Runs around using bomb.

#### Specter knight
Slash and run

#### King knight
needs object to hold on and jump and can perform dash on air.

### [Why Does Celeste Feel So Good to Play?](https://www.youtube.com/watch?v=yorTG9at90g&list=PLc38fcMFcV_t66OnpNFFXKIqsQRPVHq6U&index=7) 🧨

speed graph intro
![](assets/GMTK%20notes/images/intro_movement.png)  

celeste is snappy
![](assets/GMTK%20notes/images/celeste_movemtn.png)  

good top speed
![](assets/GMTK%20notes/images/speed.png)  

shovel knight jump height
![](assets/GMTK%20notes/images/shovel_knight.png)  

super meat boy jump height
![](assets/GMTK%20notes/images/super_meat_boy.png) 

Celeste jump height
![](assets/GMTK%20notes/images/celeste_jump.png)  

Jump curve of celeste
![](assets/GMTK%20notes/images/celeste_jump_height.png)  

### [What Makes Celeste's Assist Mode Special](https://www.youtube.com/watch?v=NInNVEHj_G4&ab_channel=GameMaker%27sToolkit) 🧨
Celeste's assit mode:
![](assets/GMTK%20notes/images/celeste_assist_mode_show.png)  

Player should not be able to change game feel / story.
If easy levels are required then it needs to be made sure that the player is not ruining the story or the player needs to be notified.
![](assets/GMTK%20notes/images/darkest_dungeon_notify_player.png)  
![](assets/GMTK%20notes/images/heat_signature_permadeath_mode.png)  
![](assets/GMTK%20notes/images/players_decision_to_change_game_design.png)  

make follow up instead implementing assist mode / easy mode at the launch. (SOMA did this) or release side by side to emphasize disconnection.

### [Breaking Down the Best World in Rayman Legends](https://www.youtube.com/watch?v=Ea6XJRqHUU4&ab_channel=GameMaker%27sToolkit) 🧨
Splinter cell and James Bond mixup.
![](assets/GMTK%20notes/images/rayman_game_type.png)  

Main mechanics: Sentry
![](assets/GMTK%20notes/images/rayman_game_sentry_20221113194248.png)  

Elevetar fight with Sentry enabled
![](assets/GMTK%20notes/images/elevator_fight20221113194454.png)  

Laser in a level
![](assets/GMTK%20notes/images/rayman_laser20221113194548.png)  

Last fast paced level was doable, because all the enemies are introduced in previous levels.

### [How Cuphead's Bosses (Try to) Kill You](https://www.youtube.com/watch?v=F8T6Ul4aHTI&ab_channel=GameMaker%27sToolkit) 🧨

Variation of projectile path, size.
Player needs to learn about the boss and predict attack.

Bosses / Enemies inform in some sort to the player. (knowing as Telegraphing)

Build up the difficulties.
Bosses should be balanced to:
![](assets/GMTK%20notes/images/Cuphead_boss20221113200221.png)  

### [Shovel Knight and Nailing Nostalgia](https://www.youtube.com/watch?v=rHhX5GtWNr8&ab_channel=GameMaker%27sToolkit) 🧨
Player loses gold when dies.
Breaking checkpoints yields loots but player won't respawned to the checkpoint.

Shovel knight's game design:
- Take from multiple sources
- emulate what works
- modernise what doesn't
- give it a rose-tinted look

### [The 4 "P"s of DOOM's Amazing Combat](https://www.youtube.com/watch?v=I9ZsFT_eqXY&ab_channel=GameMaker%27sToolkit) 🧨
Enemies are introduced in phases.
![](assets/GMTK%20notes/images/doom_phase1_20221113202006.png)  
![](assets/GMTK%20notes/images/doom_phase2%2020221113202053.png) 
![](assets/GMTK%20notes/images/doom_phase2_again20221113202142.png)  
![](assets/GMTK%20notes/images/doom_phase320221113202226.png)  
![](assets/GMTK%20notes/images/doom_phase_3_20221113202249.png)  
![](assets/GMTK%20notes/images/doom_phase4_20221113202326.png)  
![](assets/GMTK%20notes/images/doom_phase4_again20221113202400.png)  
Begs the question:
- which enemy to kill first (priority)
- which weapon to use (preference)
- recover resources (Doom zombies are mainly for resource purpose. they die quickly and spawn loots) (preservation)
- next player movement (position)

### [What Makes a Good Combat System?](https://www.youtube.com/watch?v=8X4fx-YncqA&ab_channel=GameMaker%27sToolkit) 🧨
Attacking: all players has base attack
- heavy attack would take time
  
Attacking frames category:
- Anticipation (dictates speed)
- Contact
- Recovery
![](assets/GMTK%20notes/images/light_attack_heavy_attack20221113204009.png)  

Dark souls don't have animation cancelling. Cannot interrupt with one move with another.
Attack range depends on design. (like Batman Arkham asylum has snapping, so attack range doesn't matter)

Defending:
- block
- dodge (two of these must be distinct)
In dark souls stamina gets reduced when performing defending

Parry/ counter:
- Don't make a wait-parry-counter game
- Don't make a alltime-slash-game

Enemy design:
make the player learn about enemies by making them distinct.
give heads up before enemy strike

Reward player in scoring system for successful combos and punish player for taking damage

Make intelligent enemy that learns player's move

Making an impact:
![](assets/GMTK%20notes/images/resident_evil_signature20221113205751.png)  
![](assets/GMTK%20notes/images/resident_evil20221113205817.png)  
- huge anticipation
- pause upon impact
- hefty recovery
- visual effects / blowing the screen / fireworks / enemy flashing red
