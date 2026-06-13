# X4 Distress Extended

A small extension for X4: Foundations that expands the fleet "Respond to Station Distress Calls" behavior for the `Position defense` order.

When enabled on a fleet in `Position defense` mode, fleets will respond to attacks on ships and stations belonging to their faction in the assigned sector — not just faction-owned stations in the commander's sector.

## Features

- Extends the built-in distress-response behavior so fleets react to attacks on ships and stations belonging to their faction in the assigned sector.
- Keeps the original scope of the vanilla `Position defense` order and distress-response toggle.
- Leaves other defense orders and behaviors unchanged.

## Installation

1. Copy the folder into the game's `extensions` directory.
2. Start (or restart) X4. The extension is loaded automatically.

## Usage

1. Assign a fleet to the `Position defense` order.
2. Enable the `Respond to Distress Calls` option for that fleet.
3. With this extension active, the fleet will now respond when ships or stations belonging to the same faction in the assigned sector are attacked.

## Preview

Before / After (extension active):

![Before](preview/Before.png)
![After](preview/Afterpng.png)

## Compatibility

- Targeted at the X4: Foundations `9.00` release.
- Scope remains limited to the vanilla `Position defense` order.
- Backward compatibility with `8.x` has not been re-verified as part of this update.

## 9.0 Update Notes

- Refreshed extension metadata for the 9.0 update.
- Kept the existing AI patch scope focused on `order.fight.protect.position`.
- Updated UI text to describe the actual ship-and-station distress behavior more accurately.

## Validation

- Verified the XML files in this repository remain well-formed.
- Re-checked the vanilla 8.x integration points used by the mod (`respondtodistresscalls`, `station_under_attack`, related tooltip IDs, and `AttackInRange` order usage).
- In-game validation on X4 9.0 is still recommended after game hotfixes, especially for distress event routing and handler ordering.

## License

This project is licensed under the terms in the `LICENSE` file in this repository.

## Contact

For questions or support, open an issue on this repository.