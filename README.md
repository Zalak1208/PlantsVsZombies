# PlantsVsZombies
PlantsVsZombie is a classic game in which player prtotects their home from the coming horde of zombies, by strategically planting various types of plants with unique abilities.These plants, ranging from pea shooters to sunflowers, are used to fend off the zombies and prevent them from reaching the house.The game is designed to encourage strategic thinking and adaptability, offering a deeper and more rewarding experience as players advance.

# Resources
* Bullets: This consists of different types of bullets named as:
   * BulletMushRoom<br>
   ![BulletMushRoom](resources/graphics/Bullets/BulletMushRoom/BulletMushRoom_0.png)
   * SnowPea<br>
   ![SnowPea](resources/graphics/Bullets/PeaIce/PeaIce_0.png)
   * PeaNormal <br>
    ![PeaNormal](resources/graphics/Bullets/PeaNormal/PeaNormal_0.png)
 

  
* implement plants: sunflower, peashooter, wallnut, snowpeashooter, cherrybomb, threepeashooter, chomper, puffshroom, potatomine, spikeweed, scaredyshroom, squash, scaredyshroom, jalapeno, sunShroom, iceShroom, hypnoShroom.
* implement zombies: zombie, flagzombie, coneheadzombie, bucketheadzombie, newspaperzombie.
* use json file to store level data (e.g.position and time of zombies, background info)
* support to select plant cards at the beginning of the level
* support day level, night level, moving card select level and wallnut bowling level

# Requirement
* Python 3.7 
* Notice: python version 3.7 is advisable, but not required. For LINUX: if your Linux system has a preinstalled python 3+, it's ok to run this game. Updating to python 3.7 directly may break LINUX Mint.
* Python-Pygame 1.9

# How To Start Game
$ python main.py

# How to Play
* use mouse to collect sun, select the plant cards and seed the plant 
* you can set the start level by changing START_LEVEL_NUM value in source/constants.py
  * level 1 and 2：day level
  * level 3: night level
  * level 4: moving card select level
  * level 5: wallnut bowling level

# Demo
![demo1](https://raw.githubusercontent.com/marblexu/PythonPlantsVsZombies/master/demo/demo1.jpg)
![demo2](https://raw.githubusercontent.com/marblexu/PythonPlantsVsZombies/master/demo/demo2.jpg)

