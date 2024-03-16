# Hex-game (Noname)

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913339882971168/Example.png?ex=66048559&is=65f21059&hm=63938e3d11ba63a33e96f6c210259d02412388fc6cb466d19bb8c863b0d0f50d&=&format=webp&quality=lossless&width=705&height=428">

A turn-based strategy game with a pixel art top view. The game will take place on hexagonal cells in different terrains. Each cell has its own buffs and debuffs. It will be possible to change the terrain by digging trenches, building fortifications or strategic buildings.


## Plains and forests 0.1
Standard location for combat operations on plains and forests

**Example of map:**

<img src="https://media.discordapp.net/attachments/856234593153056781/1171429927074148423/PlainsAndForet_Example.png?ex=6602c322&is=65f04e22&hm=b283c90452888f5c73eed985660528b1fe63092049f4bb4520dfdabab164665d&=&format=webp&quality=lossless&width=705&height=523" width="70%" height="70%">

**Cells buffs and debuffs:**

| Name        | Desscription           | Sprite     |
|--------------|----------------|--------------|
| Plain  | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434875820187748/Plain1.png?ex=6602c7be&is=65f052be&hm=ba276366f5af7a877c6211711cdbe200976031466a5d181611e452429c063e83&=&format=webp&quality=lossless" width="100" height="80"> |
| Plain 2 | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434879171436554/Plain2.png?ex=6602c7bf&is=65f052bf&hm=f7a69c0af5a9b33407a61b08fb6a81c9a6f248d8e5318440dcc0d523084b5cb0&=&format=webp&quality=lossless" width="100" height="80"> |
| Shrubs  | A cell with bushes where an army can hide and reduce its detection by 1 cell.         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434884338815016/Shrubs.png?ex=6602c7c0&is=65f052c0&hm=b23ec7cb76791f377aafa7786c7a757b22c028295d40762ee54ec33a005a4e00&=&format=webp&quality=lossless" width="100" height="80"> |
| Forest  | Forest. While in the forest, all troops reduce their detection distance by 2 cells         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434872775135232/Foret.png?ex=6602c7bd&is=65f052bd&hm=f455a72c8fb8d211fe62b132b50217f2475216ff1ddb54d4183a526926f27705&=&format=webp&quality=lossless" width="100" height="80">  |
| Lake  | We'll have to go around it, it hinders movement        | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434888667340800/Lake.png?ex=6602c7c1&is=65f052c1&hm=a9a84be3e1e8cd0f56e8b492453f76fae4e01ebb44b60d1c2c087dc5bee82066&=&format=webp&quality=lossless" width="100" height="80">  |

## Defense structures 0.2

Structures for the construction and fortification of combat positions, as well as obstacles for enemy troops.

**Sprites:**

<img src="https://media.discordapp.net/attachments/856234593153056781/1171477110230106173/Defense-structures.png?ex=6602ef14&is=65f07a14&hm=5f91aa1f598b7cdac70ab22251cc5d47d91427b932ad1c473637728f5aad66e7&=&format=webp&quality=lossless&width=705&height=448" width="70%" height="70%">

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

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913321755181056/Base.png?ex=66048555&is=65f21055&hm=50d298cc4ac4907ec568eb7a39354578601d968dbb25289e8869723043a51517&=&format=webp&quality=lossless" width="200" height="160">

**Barracks**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321046343740/Barracks_1lvl.png?ex=66048554&is=65f21054&hm=9372e87c9eff2b3a23515055eaa41b7fb6001be474be67bae9865243acfd97da&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321327374376/Barracks_2lvl.png?ex=66048554&is=65f21054&hm=5adc4fc99b021d3d1e494387f497d7296c07a1ec0a0d1f3739a76b486eb6c8fb&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321541287946/Barracks_3lvl.png?ex=66048554&is=65f21054&hm=4a31b6416734029b620f8d77d2e5d8ad1e8bae9f9e84f7044397056c718946ad&=&format=webp&quality=lossless" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**Factory**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322594054274/Factory_1lvl.png?ex=66048555&is=65f21055&hm=87612c40704d451be60319038d75d6e8973fef611a4109964fcf74f49f706c81&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322820550706/Factory_2lvl.png?ex=66048555&is=65f21055&hm=649b639ba1223386e140aa9c5089fc2aae8c9c518ac3b1d59a6269590a8b5f22&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913323005083658/Factory_3lvl.png?ex=66048555&is=65f21055&hm=6b4307d848c49699938fd9eb17c3810fec4b8d307b33ba947421148293a82128&=&format=webp&quality=lossless" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**City**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321973297323/City_1lvl.png?ex=66048555&is=65f21055&hm=5af56150918e60cfa7038da49e53de25a5de974de5394afc58737fca7b6b8c0e&=&format=webp&quality=lossless" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322178822254/City_2lvl.png?ex=66048555&is=65f21055&hm=278f4df60f1a29e86a2daaa6c5b56d7c9052b5d69ceb4df580f9f59c21d33ad9&=&format=webp&quality=lossless" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322401103912/City_3lvl.png?ex=66048555&is=65f21055&hm=353423f2cf9d7ebaf31c8e27c35b2b1e047126e8d5770b2233f734887ae308a8&=&format=webp&quality=lossless" width="200" height="160"> |
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

