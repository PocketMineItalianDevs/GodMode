# GodMode

Download @ https://poggit.pmmp.io/ci/PocketMineItalianDevs/GodMode


**Commands and permissions:**

```
commands:
 god:    
  description: "Toggles God mode for you or the specified player"   
  usage: "/god [player]"    
  permission: godmode.toggle    
permissions:      
  godmode:  
    description: "Allows access to all GodMode features"
    default: false  
    children:
      godmode.toggle:
        description: "Allows the player to toggle God mode"
        default: false
        children:
          godmode.toggle.self:
            description: "Allows the player to toggle God mode for themselves"
            default: op
          godmode.toggle.others:
            description: "Allows the player to toggle God mode for others"
            default: op
```
