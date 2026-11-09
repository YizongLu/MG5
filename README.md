# MG5
## Devlog
1. In games like Diablo or LOL with top-down perspective, if there are pillars or walls on the way, it is hard to recognize the exact location of the main character, so character can move avoid walking into obstacles by using NavMesh. Therefore, NavMesh is better. In games like Darksouls, players have to move precisely by press the button on keyboard. Players have to dodge or attack at very precise time, so scripting a character’s movement with physics is better than NavMesh.
2. The call to Vector3.Distance is used to get the distance between the bird in the array and Pudu. If the distance between them is lower or equal to the predefined threshold, the bird will run away from Pudu. All birds in the array that are within the threshold distance of Pudu will run away.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)