# Hex-game (Noname)

A turn-based strategy game with a pixel art top view. The game will take place on hexagonal cells in different terrains. Each cell has its own buffs and debuffs. It will be possible to change the terrain by digging trenches, building fortifications or strategic buildings.


## Plains and forests
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

## Defense structures

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
