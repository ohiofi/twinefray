Implementing a simple [Twine](http://twinery.org/2) battle system in Glitch. This battle system, Twine Fray, has several features:<br>
- random probability of an enemy appearing
- progressively healthier enemies (enemy health is determined by player score)
- random probability of enemy being more vulnerable to punch or kick
- allows the player to select an attack
- market in which player can purchase health and more powerful weapons
- HTML5 audio embedded in the title screen

![alt text](https://cdn.glitch.com/fbd4217e-2ea0-47d6-a562-212f7f478094%2Ftwine200px.png?1503856203172 "Twine logo")


# How To Use Glitch To Edit Twine

_Create new passages like this:_<br>
**\<tw-passagedata name=\"My New Passage\"\>** Passage text **\</tw-passagedata\>**

_Add links:_<br>
Add links **\[\[like this\]\]** just like a normal Twine game

_Note:_<br>
Your starting passage must have pid=\"1\" or else Twine doesn't know where to start the story. For example, \<tw-passagedata name=\"My Start Passage\" **pid=\"1\"** \> Passage text \</tw-passagedata\>
