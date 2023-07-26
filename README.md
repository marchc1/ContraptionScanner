# Contraption Scanner
A starfall-based contraption scanner capable of scanning most major ACF entities & some wire components, with easibility of adding further entities in mind. Helps with verifying the legitimacy of a contraptions legality.

Get the latest release using the Releases tab.

## Key
![Markers](https://github.com/horizon-technologies/ContraptionScanner/assets/106459595/e8c21e13-7698-4cbe-ab96-a7d1c9a031ab)

## Showcase
![image](https://github.com/horizon-technologies/ContraptionScanner/assets/106459595/a18db93f-f897-4b1f-8a0e-363d61183f0b)
*All entities currently scanned (except players). The left side are always shown, the right side are shown in extended mode.*

![image](https://github.com/horizon-technologies/ContraptionScanner/assets/106459595/e9e5306a-f6d1-49ae-b179-4ea02ef8c27d)

*Shows players outside of seats as \[PL\] markers.*

![image](https://github.com/horizon-technologies/ContraptionScanner/assets/106459595/70543e91-ffd4-43dd-9577-d290b7581a8d)
*When the scanned player is in a vehicle, the baseplate of the contraption is highlighted (with its bounding box shown). The player marker is placed  behind the vehicle marker, to show which vehicle is in use.*

![image](https://github.com/horizon-technologies/ContraptionScanner/assets/106459595/dc1eef3d-3e65-4e66-be25-9e105835a5b2)

## Chat Functions
### !scan (part of player name OR SteamID):
Starts scanning all entities owned by the player. If a player is already being scanned, that player is discarded.

### !stopscan
Stops scanning.

### !extendscan
Adds additional, less important entities to the scanner.

### Always-Shown Entities
- ACF Guns
- ACF Racks
- ACF Ammo
- ACF Radars
- Vehicles
- Players
- Baseplates

### Extended Entities
- ACF Gearboxes
- ACF Engines
- ACF Piledrivers
- ACF Armor
- Expression 2 Chips
- Starfall Chips

