# Launch Command
A mod for Minecraft datapackers to launch entities with a command.

### Usage
Launch an entity in the direction they are facing:
/launchfacing [target] [strength] [overwrite]

Launch an entity towards a given coordinate:
/launchtopoint [target] [destination] [strength] [overwrite]

Launch an entity towards another entity:
/launchtoentity [target] [destination] [strength] [overwrite]

The target parameter is the entity being launched, destination is where it will be launched towards and strength is the magnitude of the force being applied.
If overwrite is set to true then the current velocity of the entity will be zeroed out before the new velocity is applied.

This mod is built for Fabric 1.21.1.