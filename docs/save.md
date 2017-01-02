# Save format

Last updated version: 1.0e8 (Clickmas)

The Clicker Heroes save is a JSON object. Examples of this can be found [here](../saves).

The `Scientific` type is a number Clicker Heroes uses to save huge numbers without losing precision. It's serialised as a `String` in the same form as you see in the game when numbers get bigger than 10,000* or when scientific notation is turned on. Note that 0 is serialised as "0" (without the exponent).

### abaddonMultiplier
`Float`

---

### account
`null`

---

### accountId
`null`

---

### achievements
`Object`

The key is the achievement ID, the value is a `Boolean`
(true if achieved, false otherwise).

---

### actionBar
`Object`

---

### activityCount
`Integer`

---

### activityRoller
`null`

---

### adCampaign
`null`

---

### adRetargetId
`null`

---

### adRetargetTime
`Integer`

---

### allDpsMultiplier
`Float`

---

### ancientEntrySizes
`Object`

---

### ancientSouls
`Integer`

The amount of unspent ancient souls the player currently has.

---

### ancientSoulsTotal
`Integer`

The amount of ancient souls, spent or unspent, the player has.

The highest zone the player has been to across all transcensions.

---

### ancients
`Object`

[Details...](save/ancients.md)

---

### appliedDLC
`Object`

---

### autoclickerSkins
`Object`

The key is the skin ID, the value is whether or not the player has the skin.
If the player does not have the skin, it won't show in this object anyway.

---

### autoclickers
`Integer`

---

### baseClickDamage
`Integer`

---

### baseCriticalClickChance
`Integer`

Critical click chance when lucky strikes isn't active.

---

### buyExactQuantity
`Boolean`

---

### candyCanes
`Integer`

Number of candy canes the player currently has.

---

### candyCanesEarned
`Integer`

Number of candy canes the player has earned in total.

---

### clickDpsPercent
`Float`

---

### clickMultiplier
`Integer`

---

### clickmasRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

---

### clickmasRubiesEarned
`Integer`

Number of rubies earned by opening presents.

---

### collectedAchievements
`Object`

Deprecated?

---

### collectedRaidRewardDates
`Object`

This object contains the dates of the last two times a raid was completed
and whether the reward has been collected by the player or not.
The key is a `Date` (`yyyy-mm-dd`) and the value is a `Boolean`.

---

### creationTimestamp
`Integer`

---

### criticalMultiplier
`Integer`

---

### currentActivityOrderNumber
`null`

---

### currentAutoclickerSkin
`Integer`

Value is skin ID.

---

### currentZoneHeight
`Integer`

The zone the player is currently on.

---

### damageFloatersDisabled
`Boolean`

Whether the click damage text is shown after the player clicks.
For some reason, it looks like there is no option for this in the game.

---

### darkRitualClicks
`Integer`

---

### debug
`Boolean`

---

### devGifts
`Object`

---

### didClickOnAncientsTab
`Boolean`

Resets every transcension.

---

### didClickOnMercenaryTab
`Boolean`

Resets every transcension.

---

### didClickOnShopTab
`Boolean`

Deprecated?

---

### didClickOnTranscendenceTab
`Boolean`

Resets every transcension.

---

### dlcAutoclickers
`Integer`

---

### dpsSacrificedInWorldResets
`null`

---

### email
`String`

---

### epicHeroReceivedUpTo
`Integer`

The highest zone the player has received a gild from.

---

### epicHeroSeed
`Integer`

---

### epicRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

---

### extraGildsAwarded
`Integer`

Number of purchased gilds that the player has been given this transcension.

---

### finishedPrimals
`Object`

The key is the zone number, the value is whether the primal has been defeated this ascension or not.

---

### forgeCoals
`Integer`

---

### freeRespecs
`Integer`

---

### gold
`Scientific`

---

### goldFloatersDisabled
`Boolean`

---

### goldMultiplier
`Float`

---

### goldQuestsCompleted
`Integer`

---

### goldSacrificedInWorldResets
`null`

---

### hasJoinedGuild
`Boolean`

Not sure if this works properly.

---

### hasSeenNewShopItems
`Boolean`

---

### hasSeenZone100Tip
`null`

---

### heroCollection
`Object`

[Details...](save/hero_collection.md)

---

### heroEntrySizes
`Object`

---

### heroSoulQuestsCompleted
`Integer`

---

### heroSouls
`Scientific`

The amount of hero souls the player currently has
(not the amount of hero souls the player receives after ascension).

---

### heroSoulsSacrificed
`Scientific`

---

### hideRelicPopups
`Boolean`

---

### highestFinishedZone
`Integer`

The highest zone the player has been to this ascension.

---

### highestFinishedZonePersist
`Integer`

The highest zone the player has been to this transcension.

---

### highestGold
`Scientific`

The highest amount of gold held by the player this transcension.

---

### highestHistoricAncients
`Integer`

---

### highestMercenaryLevelEver
`Integer`

---

### historicRubies
`Integer`

---

### isBanned
`Boolean`

---

### isCheater
`Boolean`

---

### isTestUser
`Boolean`

---

### items
`Objects`

[Details...](save/items.md)

---

### kongId
`String`

---

### language
`null`

---

### lastAdBonusTimestamp
`Integer`

---

### lastGuildRankUpdatedTime
`Integer`

---

### lastLoadTime
`null`

---

### lastPageLoadTime
`null`?

---

### lastPrimalLevelChecked
`Integer`

---

### lastPrimalLevelResult
`Boolean`

---

### lastRaidTimestamp
`Integer`

---

### lastSkillUsed
`Integer`

The skill that has its cooldown reduced by an hour when reload is used.

---

### latestBuildLoaded
`Integer`

---

### leeroyJenkinsBuried
`Integer`

---

### lifetimeDarkRitualClicks
`Integer`

---

### loginValidated
`Boolean`

---

### maxDps
`Scientific`

---

### mercenaries
`Object`

[Details...](save/mercenaries.md)

---

### mercenaryCount
`Integer`

---

### mostClicksPerSecond
`Integer`

---

### mostCritsPerSecond
`Integer`

---

### musicEnabled
`Boolean`

---

### numAscensionsThisTranscension
`Integer`

---

### numPageLoads
`null`

---

### numRaidsToday
`Integer`

---

### numWorldResets
`Integer`

Number of ascensions.

---

### numberDisplayMode
`Boolean`

True if "Always use scientific notation." is checked. False otherwise.

---

### numberOfTranscensions
`Integer`

---

### openedClickmasPresents
`Integer`

---

### outsiderEntrySizes
`Object`

---

### outsiders
`Object`

[Details...](save/outsiders.md)

---

### paidForRubyMultiplier
`Boolean`

Whether the player has the 2x damage bonus from the shop.

---

### passwordHash
`String`

---

### persistentVars

[Details...](save/persistent_vars.md)

---

### personalSales
`Object`

#### _largestPurchaseBundleId
`Integer`

#### _numHistoricSales
`Integer`

#### _saleEndTimestamp
`Integer`

#### flashSalesEnabled
`Boolean`

#### seasonalSalesEnabled
`Boolean`

---

### pretranscendentHighestFinishedZone
`Integer`

---

### prevLoginTimestamp
`Integer`

---

### primalNumberGenerator
`Object`

#### numUses
`Integer`

#### seed
`Integer`

---

### primalSouls
`Scientific`

---

### privateAdminMessages
`Object`

---

### purchaseHashes
`Object`

---

### purchaseRecord
`Object`

---

### purchasedGilds
`Integer`

---

### purchasedTitanFightExpTime
`Integer`

---

### rarestMercenaryEver
`Integer`

---

### readPatchNumber
`String`

The latest version of the changelog the player has seen. This is an empty string if the player has not seen the changelog yet.

---

### relicQuestsCompleted
`Integer`

---

### relicsReceivedThisTranscension
`Integer`

---

### remoteQueue
`null`

---

### respondedToEmailSequelPrompt
`Boolean`

---

### respondedToSurvey
`Boolean`

This is about the Clicker Heroes 2 survey I think.

---

### revision
`null`

---

### rubies
`Integer`

---

### rubyClickablesThisAscension
`Integer`

---

### rubyQuestsCompleted
`Integer`

---

### secondToLastSkillUsed
`Integer`

The skill that has its cooldown reduced by an hour when energised reload is used.

---

### settings
`null`

---

### shouldAutoSetHeroDpsDisplay
`Boolean`

---

### shouldShowHeroDps
`Boolean`

This corresponds to "Show individual hero DPS." in the settings.

---

### skillClickMultiplier
`Float`

---

### skillClickMultiplierEnd
`Integer`

---

### skillCooldowns
`Object`

The key is the skill ID, the value is the timestamp the skill comes off cooldown (or 0 if it already is off cooldown).

---

### skillCriticalClickChance
`Float`

Critical click chance granted from skills (currently only lucky strikes).

---

### skillCriticalClickChanceEnd
`Integer`

---

### skillDouble
`Boolean`

Whether energise is currently active or not.

---

### skillDpsMultiplier
`Float`

---

### skillDpsMultiplierEnd
`Integer`

Timestamp of when the DPS bonus from skills ends.

---

### skillFreeClicks
`Integer`

---

### skillFreeClicksEnd
`Integer`

---

### skillGoldBonus
`Integer`

---

### skillGoldBonusEnd
`Integer`

Timestamp of when the gold bonus from skills ends.

---

### skillQuestsCompleted
`Integer`

---

### skillWildGold
`Integer`

---

### skillWildGoldEnd
`Integer`

---

### soulsSpent
`Integer`

---

### soundsEnabled
`Boolean`

---

### stageQuality
`Boolean`

Flash quality setting.

---

### startTimestamp
`Integer`

---

### syncedGameServices
`Boolean`

---

### ticketsUsed
`Object`

---

### timelapses
`Integer`

---

### tinyMonsters
`Boolean`

---

### titanDamage
`Scientific`

---

### titanTypesDefeated
`Object`

---

### total5MinuteQuests
`Integer`

---

### totalBossKills
`Integer`

---

### totalClicks
`Integer`

---

### totalCreditsPurchased
`null`

---

### totalCrits
`Integer`

---

### totalGold
`Scientific`

The total amount of gold the player has ever earned.

---

### totalGoldThisGame
`Scientific`

The amount of gold earned by the player this ascension.

---

### totalHeroLevels
`Integer`

---

### totalHeroSouls
`Scientific`

---

### totalHeroSoulsFromAscensions
`Scientific`

---

### totalKills
`Float`

---

### totalMercenariesBuried
`Integer`

---

### totalMercenariesRevived
`Integer`

---

### totalMoneySpent
`Float`

Amount of money player has spent on the game.

---

### totalPrimalsKilled
`Integer`

Time of the most recent transcension.

---

### totalRelicsReceived
`Integer`

---

### totalUpgrades
`Integer`

---

### transcendent
`Boolean`

Whether the player has transcended or not.

---

### transcendentHighestFinishedZone
`Integer`

---

### transcensionTimestamp
`Integer`

---

### transparentAutoclickerMode
`Boolean`

---

### treasureChestsKilled
`Integer`

---

### tutorialArrow
`Integer`

---

### uid
`null`

---

### uniqueId
`String`

---

### unixTimestamp
`Integer`

---

### unopenedClickmasPresents
`Integer`

---

### upgrades
`Object`

The key is the upgrade ID, the value is maybe whether the player has purchased it or not (I have no idea).

---

### usedSkills
`Object`

The key is the skill ID, the value is always `true`. The skills currently on cooldown. When not on cooldown, the skills will not be shown in the object.

---

### version
`Integer`

---

### worldGoldBonus
`null`
