![Lake Crouch Orange Suit E1](https://github.com/augustsaintfreytag/stalker-cooker-overhaul/assets/7656669/2c18b6a9-c561-46e5-91c2-7cda1b098a57)

# STALKER Cooker Overhaul

A re-envisioning of cooker items for STALKER Anomaly (Open X-Ray). Overhauls all existing cooker items to give each a distinct tier, a common purpose in the field, and a spot in the player's equipment progression. The mod is built using DLTX and DXML to be compatible with other mods and popular packs.

> [!WARNING]
> This mod is in active development and not yet functional.
> Do not install this mod in your game in its current version.
> This warning will be removed once the mod is considered playable.

## Items

This mod creates the following line-up of cooker items. The gameplay principle is to provide items that are either multi-use with fuel requirements or single-use without fuel requirements. The ability to cook with a campfire is moved to a distinct item.

### Mess Kit

A widely used army mess kit, consisting of a mess tin and basic metal cutlery. Can be used as a pan or small pot over an existing heat source (like a campfire) for basic dishes. It is highly compact and features a recognisable convex-concave bottom profile, concave on one side, supplied with a wire handle-loop for hanging and carrying, and is reasonably easy to clean and reuse. Sufficient to cook low quality meats that don't require high temperatures. Due to its manufacturing quality, it has limited durability.

| Name        | Description                                          |
| ----------- | ---------------------------------------------------- |
| Progression | Early-game, mid-game when saving costs               |
| Usage       | Limited uses, no fuels, campfires only               |
| Crafting    | Basic recipe, cutlery, ball hammer, scrap            |
| Weight      | 0.8 kg                                               |
| Cost        | 6160 RU                                              |
| Tags        | Technological item, low-tier field cooking equipment |
| Item        | `army_bowler` (existing)                             |

### Disposable Gas Cooker

A crude stove cooker with a pre-mounted propane tank. Slightly heavier than usual because of a crude frying pot combo attachment to make the cooker ready for use as-is. Popular in the Zone as an entry-level stove with an adjustable burner to cook meats and dishes that require a high temperature. Besides its questionable manufacturing quality, its use is limited by the small gas tank. Cheaply imported into the Zone in bulk via Chinese resellers.

| Name        | Description                                                            |
| ----------- | ---------------------------------------------------------------------- |
| Progression | Early-game                                                             |
| Usage       | Single-use (charges), integrated                                       |
| Crafting    | Basic recipe, gas balloon, cutlery, fasteners, swiss army knife, scrap |
| Weight      | 1.32 kg                                                                |
| Cost        | 1490 RU                                                                |
| Tags        | Technological item, high-tier field cooking equipment                  |
| Item        | `cooking` (existing)                                                   |

### Portable Charcoal Cooker

A compact, foldable oven for cooking with charcoal or dry wood, made of stainless steel. The stove can produce temperatures sufficient to grill less contaminated meats and dishes. Includes a complementary high quality pan that perfectly fits on its frame. In the Zone, it is appreciated for its ability to use cheap imported charcoal over expensive liquid fuels. It is considered a decent upgrade to disposable cookers for everyday preparation of common game. Especially useful for deeper expeditions into the Zone where established campfires aren't available. Use of Zone-found wood highly discouraged due to the excessive release of contaminants when burning.

| Name        | Description                                                        |
| ----------- | ------------------------------------------------------------------ |
| Progression | Mid-game                                                           |
| Usage       | Multi-use, charcoal                                                |
| Crafting    | Advanced recipe, mess kit, cutlery, fasteners, hammer, scrap       |
| Weight      | 1.1 kg                                                             |
| Cost        | 8090 RU                                                            |
| Tags        | Technological item, high quality, low-tier field cooking equipment |
| Item        | `wood_stove` (re-enabled)                                          |

### Portable Multi-Fuel Stove

A powerful, robust, and reliable stove designed for universal off-the-grid cooking needs. Features an adjustable burner, very high maximum heat output and can be adapted to use virtually any kind of gas and liquid fuel. This model has surpassed other portable stoves previously used for its resilience against the harsh conditions of the Zone. Includes a complementary set of durable, high quality cookware for continued use. Touted by stalkers as a buy once, use forever.

| Name        | Description                                                                                         |
| ----------- | --------------------------------------------------------------------------------------------------- |
| Progression | Mid-game                                                                                            |
| Usage       | Multi-use, liquid and gas fuels                                                                     |
| Crafting    | Advanced recipe, disposable gas cooker, hammer, swiss army knife, fasteners, plastic, copper, scrap |
| Weight      | 1.8 kg                                                                                              |
| Cost        | 16290 RU                                                                                            |
| Tags        | Technological item, high quality, high-tier field cooking equipment                                 |
| Item        | `fieldcooker` (existing)                                                                            |

## Roadmap

-   Incorporate GAMMA cooking changes, update actor effects
-   Distribute items as loot, reenable the `wood_stove` item
-   Update PDA entries for all items

## License

This mod was created by Saint for free use by the STALKER modding community with basic attribution under the MIT license. This mod may be distributed with mod packs.
