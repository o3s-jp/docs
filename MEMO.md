# Draft

The Chintama (令和・ちんたま大戦)

* MMO 2D platformer game.
* Players choose their team (Chiba or Saitama) before starting.
* Using weapons (e.g. guns) which are randomly placed in the world, players fight against opponent team players.
* Being hit by weapons, players lose their lives and they die if their lives reache to 0.
* The main goal of the teams is to acquire `landmarks`, which are special objects located randomly in the world.
* Players can acquire landmarks by attacking them and making their lives 0.
* Landmarks can also attack. By default, landmarks attack both teams but once a landmark is acquired, it attacks its opponent team.
* A team that acquires more landmarks than the other is considered dominant.
* The ultimate weapon of Saitama:

![](http://kaomojich.com/wp-content/uploads/saitama/saitama_01.gif)

## Player

* Chiba player color is blue.
* Saitama player color is red.
* Control:
    * Move right
    * Move left
    * Jump
    * Take an item
    * Use an item
    * Drop an item

## Item

* Players cannot attack the same team players.
* Let's implement `gun` first.

## Landmark

* Landmarks are white objects by default.
* They turn blue if acquired by Chiba.
* They turn red if acquired by Saitama.
* They are fixed to the ground. (No velocity)
* They use `gun` to attack.
