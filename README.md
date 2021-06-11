# chivalry-2-data
manual parsed data for Chivalry 2

## data format
This will be a CSV export of Dumpster's damage sheet.  
Anyone can then pull this CSV to make their own sheets.

## damage types

### cut (swords)
Cut deals normal damage to all classes

### chop (axes)
Chop deals 1.175x damage to Footmen  
Chop deals 1.25x damage to Knights  

### blunt (maces)
Blunt deals 1.35x damage to Footmen  
Blunt deals 1.5x damage to Knights  

### bots
Bots have less health than players  
Bots take extra damage from chop and blunt, but not as much as players to. Probably because they have less health overall  
Chop deals 1.1x damage to Bots  
Blunt deal 1.2x damage to Bots  

## hitboxes
Hitting the body deals normal damage

### melee
Hitting the legs deals 0.85x damage  
Hitting the head deals 1.0x damage (aka no damage buff)

### thrown
??? Not sure if these follow the same rules as projectiles  

### projectile
Shooting the legs deals 0.75x damage  
Shooting the head deals 1.5x damage
