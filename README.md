# MG4
## Devlog

The FloatAnimation script has two serialized fields called `_moveSpeed` and `_switchSpeed`. It also has two private fields called `_up` and `_timer`. On `Start()`, the timer is initialized to `_switchSpeed`. In `Update()`, it first checks if `_up` is true or not, changing the `_moveSpeed` to negative to move the object down if `_up` is false. After that, timer is subtracted by delta and then checked if the timer has finished, flipping the value of `_up` and resetting the timer. 

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
