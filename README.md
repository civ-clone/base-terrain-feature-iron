# base-terrain-feature-iron

The `Iron` terrain feature: a special resource a square can hold.

For example: Civ2's Iron, found on Mountains.

This package only declares the class: it has no `main` and registers nothing, so installing it changes no game.
A game's rules register it and give it its yields.

```ts
import Iron from '@civ-clone/base-terrain-feature-iron/Iron';
import { instance as availableTerrainFeatureRegistryInstance } from '@civ-clone/core-terrain-feature/AvailableTerrainFeatureRegistry';

availableTerrainFeatureRegistryInstance.register(Iron);
```

Part of the Civ2 work (civ-clone/web-renderer#1008).
