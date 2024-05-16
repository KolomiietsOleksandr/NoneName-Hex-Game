# Hex-game (Noname)

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913339882971168/Example.png?ex=66471919&is=6645c799&hm=a480507da78b3a20123912c34056871b4a91934824fdccdbd713ae1b2c54eff6&=&format=webp&quality=lossless&width=705&height=428">

A turn-based strategy game with a pixel art top view. The game will take place on hexagonal cells in different terrains. Each cell has its own buffs and debuffs. It will be possible to change the terrain by digging trenches, building fortifications or strategic buildings.


## Plains and forests 0.1
Standard location for combat operations on plains and forests

**Example of map:**

<img src="https://media.discordapp.net/attachments/856234593153056781/1171429927074148423/PlainsAndForet_Example.png?ex=66475122&is=6645ffa2&hm=8eb103b149f24de6e7abd956c56aa1afecbcc82c228005dbcaa16bf0d05a8ab5&=&format=webp&quality=lossless&width=472&height=350" width="70%" height="70%">

**Cells buffs and debuffs:**

| Name        | Desscription           | Sprite     |
|--------------|----------------|--------------|
| Plain  | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434875820187748/Plain1.png?ex=664755be&is=6646043e&hm=e0cb9ed558ab4c858da50b5f6860efa1152af0242e960cf5a42425dc567a37f2&=&format=webp&quality=lossless" width="100" height="80"> |
| Plain 2 | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434879171436554/Plain2.png?ex=664755bf&is=6646043f&hm=ecebcebfc146504cbc3e7f631a9ea7472f28980935ce1af1d6ba9ec7b32164a4&=&format=webp&quality=lossless" width="100" height="80"> |
| Shrubs  | A cell with bushes where an army can hide and reduce its detection by 1 cell.         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434884338815016/Shrubs.png?ex=664755c0&is=66460440&hm=936f5834be8854a37051e6d1febce1ea5a1988931d25e9bad5306b73da3da07d&=&format=webp&quality=lossless" width="100" height="80"> |
| Forest  | Forest. While in the forest, all troops reduce their detection distance by 2 cells         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434872775135232/Foret.png?ex=664755bd&is=6646043d&hm=128522e936a90b9f97896de2010c5c81a000e16917cf6e392a17ffe784e64306&=&format=webp&quality=lossless" width="100" height="80">  |
| Lake  | We'll have to go around it, it hinders movement        | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434888667340800/Lake.png?ex=664755c1&is=66460441&hm=d11749c415208d6080573fcdcb8b2133e582dc9d2fe209d2ea41c4d721edea89&=&format=webp&quality=lossless" width="100" height="80">  |

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

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913321755181056/Base.png?ex=66471915&is=6645c795&hm=1c429403623dd50f7f341ca8e4036301422da52400efee34694d63bb6842b3d6&=&format=webp&quality=lossless" width="200" height="160">

**Barracks**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321046343740/Barracks_1lvl.png?ex=66374714&is=6635f594&hm=768cab40435067fc137ec7747f086d962aa105a74df45f8ea6dca8014b395516&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321327374376/Barracks_2lvl.png?ex=66471914&is=6645c794&hm=aa91224baeec3f803df931a2b2501f4fe3c33c70de38aff5e9fd957ef72f24ec&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321541287946/Barracks_3lvl.png?ex=66471914&is=6645c794&hm=b2c4819a3fc5607fc71123dbdb5878907c634e8220c5397987b72519b303a2ac&=&format=webp&quality=lossless" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**Factory**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322594054274/Factory_1lvl.png?ex=66471915&is=6645c795&hm=64d380792e2d89be7d47fd7bdd6ff3e139d659cb0e575fb026ef6a62777ac85f&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322820550706/Factory_2lvl.png?ex=66471915&is=6645c795&hm=2dcdd2cfe8149983d1594f196c46d9556a637d4515dadb98488fe39d314cc5e2&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913323005083658/Factory_3lvl.png?ex=66471915&is=6645c795&hm=004b608419a915ea313f4abb3fa6712d3215bb19a04ce04b877fc367a8866b17&=&format=webp&quality=lossless" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**City**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321973297323/City_1lvl.png?ex=66374715&is=6635f595&hm=823cb8873ab8656755712651a7029cff5c1ad329da5aaa313841f5b2774fa291&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322178822254/City_2lvl.png?ex=66471915&is=6645c795&hm=d128f650e0a5aa6b5267367c8824dfd6a6b39c659c763a61590e23d3b4f95521&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322401103912/City_3lvl.png?ex=66471915&is=6645c795&hm=695f7d81421c9d68d2594cf9675a22fe06dc9799ff1d2a5b2a53dbcbb3d3542b&=&format=webp&quality=lossless" width="200" height="160"> |
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

