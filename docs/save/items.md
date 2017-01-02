# items

AKA relics.

### _currentUids
`Object`

---

### ascensionItemsRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

---

### bonusZoneRoller
`Object`

This is to decide which zone the player gets their free ascension relic.

#### numUses
`Integer`

#### seed
`Integer`

---

### equipmentSlots
`Integer`

Number of slots the player has, filled or not.

---

### gotAscensionItem
`Boolean`

Whether the player got their free relic this ascension or not.

---

### guildItemsRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

---

### items
`Object`

The key is the item ID, the value is an `Object` in the following form:

#### bonus1Distribution
`Integer`

#### bonus2Distribution
`Integer`

#### bonus3Distribution
`Integer`

#### bonus4Distribution
`Integer`

#### bonus1Level
`Float`

The number of levels the first bonus gives.

#### bonus2Level
`Float`

The number of levels the second bonus gives.

#### bonus3Level
`Float`

The number of levels the third bonus gives.

#### bonus4Level
`Integer`

The number of levels the fourth bonus gives.

#### bonusType1
`Integer`

The ID of the first bonus. 0 or null if there isn't a bonus.

#### bonusType2
`Integer`

The ID of the second bonus. 0 or null if there isn't a bonus.

#### bonusType3
`Integer`

The ID of the third bonus. 0 or null if there isn't a bonus.

#### bonusType4
`Integer`

The ID of the fourth bonus. 0 or null if there isn't a bonus.

#### imageId
`Integer`

#### isNew
`Boolean`

Whether the player has seen the relic's stats or not.

#### level
`Integer`

#### name
`String`

#### rarity
`Integer`

#### type
`String`

#### uid
`Integer`

#### upgradeCount
`Integer`

---

### salvagePoints
`Integer`

Forge cores.

---

### slots
`Object`

The key is the slot number, the value is the item (relic) ID. Additionally, the object also has the following values:

#### items
`Integer`
