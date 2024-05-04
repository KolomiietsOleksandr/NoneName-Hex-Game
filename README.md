# Hex-game (Noname)

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913339882971168/Example.png?ex=66374719&is=6635f599&hm=2218de97dedc97a4276f3ab5b807502e4487b58f6f7b21a5bf7189ae78918473&=&format=webp&quality=lossless&width=705&height=428">

A turn-based strategy game with a pixel art top view. The game will take place on hexagonal cells in different terrains. Each cell has its own buffs and debuffs. It will be possible to change the terrain by digging trenches, building fortifications or strategic buildings.


## Plains and forests 0.1
Standard location for combat operations on plains and forests

**Example of map:**

<img src="https://media.discordapp.net/attachments/856234593153056781/1171429927074148423/PlainsAndForet_Example.png?ex=6636d662&is=663584e2&hm=763c652db039f851c03b1b7019455703593379d78d5bfdf9ec80d74d3a306ad8&=&format=webp&quality=lossless&width=705&height=523" width="70%" height="70%">

**Cells buffs and debuffs:**

| Name        | Desscription           | Sprite     |
|--------------|----------------|--------------|
| Plain  | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434875820187748/Plain1.png?ex=6636dafe&is=6635897e&hm=b274889738b8bcb29cc18433c8773df45c79f4022db9c1a5a2fe8fabaf0dbd15&=&format=webp&quality=lossless" width="100" height="80"> |
| Plain 2 | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434879171436554/Plain2.png?ex=6636daff&is=6635897f&hm=532b6726884985ce2152a99ebf73afff5411de2c0fc22eecdb1ec08c8d60c10b&=&format=webp&quality=lossless" width="100" height="80"> |
| Shrubs  | A cell with bushes where an army can hide and reduce its detection by 1 cell.         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434884338815016/Shrubs.png?ex=6636db00&is=66358980&hm=e699521ea378b73b7c767bdac4abe4050070ee5e1081d35aa9fbea3025f0cdfc&=&format=webp&quality=lossless" width="100" height="80"> |
| Forest  | Forest. While in the forest, all troops reduce their detection distance by 2 cells         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434872775135232/Foret.png?ex=6636dafd&is=6635897d&hm=b4123a69f2fc23c6a34f77d2f8bb3fac71f4e8ecde33bb1a72c7c5aa1a03c563&=&format=webp&quality=lossless" width="100" height="80">  |
| Lake  | We'll have to go around it, it hinders movement        | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434888667340800/Lake.png?ex=6636db01&is=66358981&hm=4c5ab6a315d112ed7ecf9710ce6b54ec3ad042d7a1b55e6c02bee44e59a393d4&=&format=webp&quality=lossless" width="100" height="80">  |

## Defense structures 0.2

Structures for the construction and fortification of combat positions, as well as obstacles for enemy troops.

**Sprites:**

<img src="https://media.discordapp.net/attachments/856234593153056781/1171477110230106173/Defense-structures.png?ex=66370254&is=6635b0d4&hm=d78a453b90d7b9ef6b8e5597dd9b23013474b91e6f730975badd89d9e933e390&=&format=webp&quality=lossless&width=1063&height=676" width="70%" height="70%">

1. Trench - a reliable shelter for infantry, where they can wait out the shelling or conduct defensive actions.
   - Level 1: -50% damage from infantry at a distance of more than 2 square, -15% damage from shelling, maximum capacity of 3 soldiers
   - Level 2: Infantry cannot be hit at a distance of more than 2 square, -25% damage from shelling, maximum capacity of 5 soldiers
   - Level 3: Infantry cannot be hit at a distance of more than 1 square, -40% damage from shelling, maximum capacity of 8 soldiers
  
2. Machine gun crew - very effective on the battlefield, can fire suppressive. Have an extended range of destruction.
   - Level 1: -15% damage from infantry, +1 cell attack distanse, +30% damage from shelling 
   - Level 2: -25% damage from infantry, +1 cell attack distanse, +20% damage from shelling
   - Level 3: -50% damage from infantry, +2 cell attack distanse, +10% damage from shelling

3. Reconnaissance tower -  facilitates surveillance of the territory, allows snipers to make longer shots and increases their accuracy.
   - Level 1: 4 cells visabilliity, +15% accurancy 
   - Level 2: 5 cells visabilliity, +20% accurancy 
   - Level 3: 6 cells visabilliity, +25% accurancy
  
4. Barbed wire - delays infantry for one turn and deals 20% damage, can be run over by vehicles.
5. Anti-tank hedgehogs - do not allow vehicles to pass, but infantry can cross them. Can be broken by infantry sabotage.
6. Minefield - visible only to the owner, blows up 1-5 infantry units or 1-2 vehicles.

## Buildings 0.3

In addition to defensive structures, you can also build strategic buildings, as: Barracks, Factories, and Cities. Within a 3-cell radius of factories and barracks, empty cells belonging to the player provide 1 point for army construction. Some structures have additional points (Cities, forests, lakes). Build a strong economy for victory!

**Base**
The base is the main goal, and when it is destroyed or captured, the game ends. Protect it until the last fighter is left.

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913321755181056/Base.png?ex=66374715&is=6635f595&hm=0ed565ef3db9706bf969596128d18f6256b1f8dda4fbe410e3b7157f4ab29a4b&=&format=webp&quality=lossless" width="200" height="160">

**Barracks**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321046343740/Barracks_1lvl.png?ex=66374714&is=6635f594&hm=768cab40435067fc137ec7747f086d962aa105a74df45f8ea6dca8014b395516&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321327374376/Barracks_2lvl.png?ex=66374714&is=6635f594&hm=57b2815d085e4d96ffc11d9128b8c3836df5cbe5360e1ee92964cfd883c0fbc0&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321541287946/Barracks_3lvl.png?ex=66374714&is=6635f594&hm=ed79a5e5cdaae19da328d2f1efc829f156410b5199192d6c2cbdcd951e624a44&=&format=webp&quality=lossless" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**Factory**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322594054274/Factory_1lvl.png?ex=66374715&is=6635f595&hm=073d4494eb9970809caa0f02391aa2d61557936422943cbd30f1d11eedab9041&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322820550706/Factory_2lvl.png?ex=66374715&is=6635f595&hm=30f215644bb4cf43ceace5046e76e1650786c6be279748a53ad1c0b5251c5038&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913323005083658/Factory_3lvl.png?ex=66374715&is=6635f595&hm=3ec0d6b4c882ce153e109f0d23a4f76b3b83289658c8d2f9867ebfe5506594fd&=&format=webp&quality=lossless" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**City**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321973297323/City_1lvl.png?ex=66374715&is=6635f595&hm=823cb8873ab8656755712651a7029cff5c1ad329da5aaa313841f5b2774fa291&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322178822254/City_2lvl.png?ex=66374715&is=6635f595&hm=13ae3d0ef640b7ad3dda77b45ec046518c0f9cc0703b2dde1dcef08bcaa166ee&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322401103912/City_3lvl.png?ex=66374715&is=6635f595&hm=18c7ad7a052d0f38211d0977b09e8d69a13efb97b64ea1ce5a001b92ce91717e&=&format=webp&quality=lossless" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

## Select and Upgrade 0.3
<table style="border-collapse: collapse;">
  <tr>
    <td style="border: none;">The ability to select cells and further interact with them has been added. When you click on a cell, a menu appears with a choice of what you want to build.<br><br>  Menu: <br>ㅤ▹ㅤLogistic structures <br>ㅤ▹ㅤDefense structures<br>ㅤ▹ㅤObstacles and trapsb<br><br> 
Buid menu: <br>
Contains information about the structure, its capabilities, and price. <br><br>  
Interaction menu:<br> Contains buttons for interacting with structures, as well as information about the next improvement of the structure. <br>
ㅤ▹ㅤDestroy structure <br> ㅤ▹ㅤReplace (trench) / produce <br>
ㅤ▹ㅤUpgrade structure
</td>
    <td style="border: none;">
    <img src="SelectionExample.gif" width="450" height="450">
    </td>
  </tr>
</table>

## Infantry 0.4

<h3 align="center"> <b>Barracks</b> </h3>

|  <img src="Infantry/Barracks/Recruit.png" width="75%">    |   <img src="Infantry/Barracks/Shotgun-man.png" width="75%">    |   <img src="Infantry/Barracks/Rifle-man.png" width="75%">    |   <img src="Infantry/Barracks/Bazooka-man.png" width="75%">    |   <img src="Infantry/Barracks/Sniper.png" width="75%">    |
|------------------|------------------|------------------|------------------|------------------|
|  **Recruit** | **Shotgun-man** | **Rifle-man** | **Bazooka-man** | **Sniper** |

<h3 align="center"> <b>Factory</b> </h3>

|  <img src="Infantry/Factory/Scouting-car.png" width="75%">    |   <img src="Infantry/Factory/Mortar-man.png" width="75%">    |   <img src="Infantry/Factory/ACP.png" width="75%">    |   <img src="Infantry/Factory/Anti-tank-cannon.png" width="75%">    |   <img src="Infantry/Factory/Tank.png" width="75%">    |
|------------------|------------------|------------------|------------------|------------------|
|  **Scouting car** | **Mortar-man** | **APC** | **Anti-tank cannon** | **Tank** |

