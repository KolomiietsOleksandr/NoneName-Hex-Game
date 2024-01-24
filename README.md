# Hex-game (Noname)

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913339882971168/Example.png?ex=655e6859&is=654bf359&hm=685aa043660c6596a1285de9a09473c0406bab15c10e05adcf9c9c1c19d86e07&=&width=1115&height=676">

A turn-based strategy game with a pixel art top view. The game will take place on hexagonal cells in different terrains. Each cell has its own buffs and debuffs. It will be possible to change the terrain by digging trenches, building fortifications or strategic buildings.


## Plains and forests 0.1
Standard location for combat operations on plains and forests

**Example of map:**

<img src="https://cdn.discordapp.com/attachments/856234593153056781/1171429927074148423/PlainsAndForet_Example.png?ex=655ca622&is=654a3122&hm=918e94dbd3987198438898f36f6d5384245679b6ee4beb27f2cc5e598629e808&" width="70%" height="70%">

**Cells buffs and debuffs:**

| Name        | Desscription           | Sprite     |
|--------------|----------------|--------------|
| Plain  | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434875820187748/Plain1.png" width="100" height="80"> |
| Plain 2 | Simple cells without additional features         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434879171436554/Plain2.png?ex=655caabf&is=654a35bf&hm=fe6430c70c6ca864d34736d82d94a1958b36c16073d776304f969554d50e30d2&=" width="100" height="80"> |
| Shrubs  | A cell with bushes where an army can hide and reduce its detection by 1 cell.         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434884338815016/Shrubs.png?ex=655caac0&is=654a35c0&hm=af28a9202d45f8604d280fa219cfebb8f836f6a8817c9ccb121273989ab55d36&=" width="100" height="80"> |
| Forest  | Forest. While in the forest, all troops reduce their detection distance by 2 cells         | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434872775135232/Foret.png?ex=655caabd&is=654a35bd&hm=7c99da92e8773446796ee916717913565d67bea69295418eb17c6c7984035ddf&=" width="100" height="80">  |
| Lake  | We'll have to go around it, it hinders movement        | <img src="https://media.discordapp.net/attachments/856234593153056781/1171434888667340800/Lake.png?ex=655caac1&is=654a35c1&hm=d8506d51fb0236b5759423f59a513d98b057a9d999642bdf5849fac0f0ac7c2a&=" width="100" height="80">  |

## Defense structures 0.2

Structures for the construction and fortification of combat positions, as well as obstacles for enemy troops.

**Sprites:**

<img src="https://media.discordapp.net/attachments/856234593153056781/1171477110230106173/Defense-structures.png?ex=655cd214&is=654a5d14&hm=239a5c78d9b1642e820427b8bd074e5720772d4df0f6e21331a7dea65beb3969&=&width=1063&height=676" width="70%" height="70%">

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

<img src="https://media.discordapp.net/attachments/856234593153056781/1171913321755181056/Base.png?ex=655e6855&is=654bf355&hm=a8784e00c6509c2b4a059c23291ed94fe371322d4ffcebda4045b94d4253e660&=" width="200" height="160">

**Barracks**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321046343740/Barracks_1lvl.png?ex=655e6854&is=654bf354&hm=7752e971059fa84d0d5a7250fac4fe8a76a20e1ad74a4196e0d9c9a34d7b5b54&=" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321327374376/Barracks_2lvl.png?ex=655e6854&is=654bf354&hm=c58d7dea7311e92168fd9d8b6ee1538e2dd2cbbc1e90d17abbad4b8e2fd23254&=" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321541287946/Barracks_3lvl.png?ex=655e6854&is=654bf354&hm=c93583a2092798f5bd0a3e3f3c6104b74a51ac5c5b6c7bcffad5368f5e0fb62f&=" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**Factory**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322594054274/Factory_1lvl.png?ex=655e6855&is=654bf355&hm=5337778527c9f20d63850d0df375b1a3e9a61860d611ad2b63c3e62ee6ce288e&=" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322820550706/Factory_2lvl.png?ex=655e6855&is=654bf355&hm=a91941af4096d2ed0fff972392520bc43664a4244a48b2187a156560ca1549e6&=" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913323005083658/Factory_3lvl.png?ex=655e6855&is=654bf355&hm=eeb1b3de7dc23035480ba9aa818b0447061aa716900d75b62faff2296c6c32dd&=" width="200" height="160"> |
| <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> | <div>Price: coming soon<br>Produce: soon<br>HP: soon</div> |

**City**
| Level 1      | Level 2      | Level 3      |
|------------------|------------------|------------------|
| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913321973297323/City_1lvl.png?ex=655e6855&is=654bf355&hm=f127502767e49a96485e10019a600e0bb94936f3cc0869f928b1fc63587e8e7e&=" width="200" height="160">| <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322178822254/City_2lvl.png?ex=655e6855&is=654bf355&hm=19b62d4cb92e4c3b18ca62cd62a2b430d64f337fe354cc5c131f8aa894691962&=" width="200" height="160"> | <img src="https://media.discordapp.net/attachments/856234593153056781/1171913322401103912/City_3lvl.png?ex=655e6855&is=654bf355&hm=e6788e9e4793f3ff744be7b0f25d3ba3dc60e3ceb7f9dba16988050110e98ecf&=" width="200" height="160"> |
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

##Infantry
**Barracks**
| Level 1      |  Level 2       |  Level 2       |  Level 3       |  Level 3       |
|------------------|------------------|------------------|------------------|------------------|
|  **Recruit** | **Shotgun-man** | **Rifle-man** | **Bazooka-man** | **Sniper** |
|  <img src="Infantry/Barracks/Recruit.png" width="75%">    |   <img src="Infantry/Barracks/Shotgun-man.png" width="75%">    |   <img src="Infantry/Barracks/Rifle-man.png" width="75%">    |   <img src="Infantry/Barracks/Bazooka-man.png" width="75%">    |   <img src="Infantry/Barracks/Sniper.png" width="75%">    |
| Coming soon | Coming soon | Coming soon | Coming soon | Coming soon |
|  **Scouting car** | **Mortar-man** | **APC** | **Anti-tank cannon** | **Tank** |
|  <img src="Infantry/Factory/Scouting-car.png" width="75%">    |   <img src="Infantry/Factory/Mortar-man.png" width="75%">    |   <img src="Infantry/Factory/ACP.png" width="75%">    |   <img src="Infantry/Factory/Anti-tank-cannon.png" width="75%">    |   <img src="Infantry/Factory/Tank.png" width="75%">    |
| Coming soon | Coming soon | Coming soon | Coming soon | Coming soon |
