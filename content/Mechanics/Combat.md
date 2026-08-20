---
tags:
---
# Ballistics System
- The ballistics system will not be "fully simulated" to ensure simplicity
	- This will make it easier to balance and control while remaining realistic
- ## [Enemy](Enemies.md) Armor
	- Effective thickness based on angle of the impact
		- Damage to the part is independent of the effective thickness, effective thickness only influences penetration power
	- All parts with colliders are modeled with hp and armor and are destructible (but not visually)
	- No post pen shrapnel, only the main bullet with penetration falloff
	- Hitting a shot will always damage something, even non-pens will do a small amount of damage to simulate armor degradation
	- Penetration mostly determines if a shot continues through the current part to the next or not
		- especially includes internal modules
	- If a shot did not clearly penetrate, shots will become partial penetrations
	- There is no damage falloff
	- Explosive effect rounds done using a sphere collider instead of many shrapnel raycasts
- ## [Player](Classes.md) and [Player Ally](Drones.md) Armor
	- Player armor isn't physically modeled and covers an entire limb (uses the player colliders)
		- This is to prevent deaths and frustration caused by raycasts going through a tiny gap in the armor
	- Armor thickness, effective thickness, non pens, etc are all still modeled
	- Otherwise shares the same penetration system as enemies (see above)
# Shields
- (see [Story](Story.md) for lore explanation)
- Shields will apply a flat penetration (and damage) decrease for incoming shots, the amount depending on the [grade](Items) of the shield.
- While they will melt smaller projectiles, larger caliber shots may pass through relatively unaffected
- Shields do not protect against explosion shockwaves