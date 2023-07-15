# RVolumetric
RVolumetric is a module meant to display volumetric lighting for Roblox. It is easy to set up:
```lua
RVolumetric:Set()
```

# Configuring
Refer to figure 1.1 to configure settings
```lua
RVolumetric.Settings = {
  maxRenderDistance = 150, -- self explanatory
  useAccurateLength = true, -- when active, volumetric effects will be as long as the light's range; otherwise, it will be a constant, preset range.
  updatePerChanges = true -- whether or not light effects should update based on the environment and properties of the light (e.g: obstacles in the way, range and angle of the light, etc.)
}
```
# Credits
It should be noted that this is built off of filiprodak's open-source module, "BetterGraphics." However, it does improve upon it with several features and much more garbage collecting.
