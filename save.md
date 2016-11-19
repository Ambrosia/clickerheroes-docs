# Save format

## skillWildGold
`Integer`

## skillGoldBonus
`Integer`

## debug
`Boolean`

## goldQuestsCompleted
`Integer`

## rubyQuestsCompleted
`Integer`

## lastPageLoadTime
`null`?

## skillDouble
`Boolean`

Whether energise is currently active or not.

## relicQuestsCompleted
`Integer`

## skillClickMultiplierEnd
`Integer`

## usedSkills
`Object`

The key is the skill ID, the value is always `true`.
The skills currently on cooldown. When not on cooldown, the skills will not
be shown in the object.


## skillClickMultiplier
`Float`

## gold
`Scientific`

## lastSkillUsed
`Integer`

The skill that has its cooldown reduced by an hour when reload is used.

## rubies
`Integer`

## skillQuestsCompleted
`Integer`

## transcendent
`Boolean`

Whether the player has transcended or not.

## secondToLastSkillUsed
`Integer`

The skill that has its cooldown reduced by an hour when energised reload is
used.

## historicRubies
`Integer`

## collectedAchievements
`Object`

Deprecated?

## totalMoneySpent
`Float`

Amount of money player has spent on the game.

## baseCriticalClickChance
`Integer`

Critical click chance when lucky strikes isn't active.

## lastLoadTime
`null`

## numPageLoads
`null`

## totalCreditsPurchased
`null`

## persistentVars

### pwbWon
`Integer`

### christmasSaleBuys
`Integer`

### previousPermaAdsTimestamp
`Integer`

### pwbPlayed
`Integer`

### allVisualEffects
`Boolean`

### previousEventAdsTimestamp
`Integer`

### pwbClosest
`Integer`

### preloadAds
`Boolean`

### previousMainScreenAdsTimestamp
`Integer`

### bloopCoins
`Integer`

### karma
`Integer`

### fullscreen
`Boolean`

### bloopCoinRequestDonationTimestamp
`Integer`

### showBossDefeatHelp
`Boolean`

### pwbHelp
`Boolean`

### showLevel100Help
`Boolean`

### didPurchaseSkill
`Boolean`

### showPrimalBossHelp
`Booolean`

### didUseSkill
`Boolean`

### goldNotificationsEnabled
`Boolean`

### showGildedHeroHelp
`Boolean`

### didOpenShop
`Boolean`

### cooldownNotificationsEnabled
`Boolean`

### showItemHelp
`Boolean`

### didOpenAncientScreen
`Boolean`

### mercenaryNotificationsEnabled
`Boolean`

### didOpenOnlineSave
`Boolean`

### nextRatePromptTime
`Integer`

### bossDefeatHelpTimestamp
`Integer`

### didShowTranscendenceNews
`Boolean`

### halloweenSaleBuys
`Integer`

## ancients
`Object`

### rerollSoulsSpent
`Integer`

### ancients
`Object`

The key is the ancient ID, the value is an `Object` in the following form:

#### locked
`Boolean`

#### id
`Integer`

#### purchaseTime
`Integer`

#### level
`Scientific`

#### spentHeroSouls
`Scientific`

#### uid
`Integer`

### _currentUids
`null`

### numRerolls
`Integer`

### ancientsRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

### artificiallyRaisedAncients
`Object`

### numPurchased
`Integer`

## primateAdminMessages
`Object`

## heroSoulQuestsCompleted
`Integer`

## hasSeenZone100Top
`null`

## adCampaign
`null`

## worldGoldBonus
`null`

## achievements
`Object`

The key is the achievement ID, the value is a `Boolean`
(true if achieved, false otherwise).

## total5MinuteQuests
`Integer`

## criticalMultiplier
`Integer`

## heroCollection
`Object`

### maxSize
`Integer`

### heroes
`Object`

The key is the hero ID, the value is an `Object` in the following form:

#### locked
`Boolean`

Whether the hero is locked (see Gilded window).

#### id
`Integer`

#### level
`Integer`

#### damageMultiplier
`Float`

#### uid
`Integer`

#### epicLevel
`Integer`

Number of guilds this hero currently has.

### _currentUids
`Object`

#### heroes
`Integer`

## treasureChestsKilled
`Integer`

## remoteQueue
`null`

## leeroyJenkinsBuried
`Integer`

## rarestMercenaryEver
`Integer`

## adRetargetTime
`Integer`

## heroSouls
`Scientific`

The amount of hero souls the player currently has
(not the amount of hero souls the player receives after ascension).

## totalRelicsReceived
`Integer`

## highestMercenaryLevelEver
`Integer`

## adRetargetId
`null`

## upgrades
`Object`

The key is the upgrade ID, the value is maybe whether the player has purchased
it or not (I have no idea).

## ancientSouls
`Integer`

The amount of unspent ancient souls the player currently has.

## highestFinishZonePersist
`Integer`

The highest zone the player has been to this transcension.

## activityRoller
`null`

## highestFinishedZone
`Integer`

The highest zone the player has been to this ascension.

## ancientsSoulsTotal
`Integer`

The amount of ancient souls, spent or unspent, the player has.

## pretranscendentHighestFinishedZone
`Integer`

## mercenaryCount
`Integer`

## paidForRubyMultiplier
`Boolean`

Whether the player has the 2x damage bonus from the shop.

## relicsReceivedThisTranscension
`Integer`

## revision
`null`

## transcendentHighestFinishZone
`Integer`

The highest zone the player has been to across all transcensions.

## numberOfTranscensions
`Integer`

## titanDamage
`Scientific`

## heroSoulsSacrificed
`Scientific`

## actionBar
`Object`

## totalHeroSouls
`Scientific`

## ticketsUsed
`Object`

## tutorialArrow
`Integer`

## totalClicks
`Integer`

## currentZoneHeight
`Integer`

The zone the player is currently on.

## activityCount
`Integer`

## totalGold
`Scientific`

The total amount of gold the player has ever earned.

## lastRaidTimestamp
`Integer`

## goldFloatersDisabled
`Boolean`

## highestGold
`Scientific`

The highest amount of gold held by the player this transcension.

## lastGuildRankUpdatedTime
`Integer`

## numRaidsToday
`Integer`

## transparentAutoclickerMode
`Boolean`

## totalGoldThisGame
`Scientific`

The amount of gold earned by the player this ascension.

## collectedRaidRewardDates
`Object`

This object contains the dates of the last two times a raid was completed
and whether the reward has been collected by the player or not.
The key is a `Date` (`yyyy-mm-dd`) and the value is a `Boolean`.

## damageFloatersDisabled
`Boolean`

Whether the click damage text is shown after the player clicks.
For some reason, it looks like there is no option for this in the game.

## totalKills
`Float`

## titanTypesDefeated
`Object`

## tinyMonsters
`Boolean`

## totalBossKills
`Integer`

## purchaseHashes
`Object`

## email
`String`

## totalUpgrades
`Integer`

## rubyClickablesThisAscension
`Integer`

## syncedGameServices
`Boolean`

## buyExactQuantity
`Boolean`

## totalHeroLevels
`Integer`

## hideRelicPopups
`Boolean`

## lastAdBonusTimestamp
`Integer`

## primeNumberGenerator
`Object`

### numUses
`Integer`

### seed
`Integer`

## account
`null`

## heroEntrySizes
`Object`

## baseClickDamage
`Integer`

## outsiderEntrySizes
`Object`

## totalCrits
`Integer`

## devGifts
`Object`

## mostClicksPerSecond
`Integer`

## epicRoller
`Object`

### numUses
`Integer`

### seed
`Integer`

## totalPrimalsKilled
`Integer`

## finishedPrimals
`Object`

The key is the zone number, the value is whether the primal has been defeated
or not.

## mostCritsPerSecond
`Integer`

## ancientEntrySizes
`Object`

## purchasedTitanFightExpTime
`Integer`

## uniqueId
`String`

## maxDps
`Scientific`

## totalHeroSoulsFromAscensions
`Scientific`

## passwordHash
`String`

## soundsEnabled
`Boolean`

## mercenaries
`Object`

### hasGivenOneFreeRecruit
`Boolean`

### startRecruitTime
`Boolean`

### mercRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

### questRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

### questOptions
`Object`

### _currentUids
`null`

### mercenaries
`Object`

The key is the index and the value is an `Object` in the following form:

#### lastQuestRewardType
`Integer`

#### level
`Integer`

#### statId
`Integer`

#### createTime
`Integer`

#### roller
`Object`

numUses: `Integer`

seed: `Integer`

#### assetId
`Integer`

The appearance of the mercenary.

#### rarity
`Integer`

#### phrase1
`String`

#### lastQuestGoldRewardQty
`Integer`

#### bonusLives
`Integer`

Amount of bonus lives this mercenary currently has.

#### phrase2
`String`

Death phrase.

#### lastQuestRewardQty
`Float`

#### lastQuestSuccessChance
`Float`

#### name
`String`

#### slotId
`Integer`

The order this mercenary appears in inside the mercenaries tab. Zero-indexed.

#### questResult
`Integer`

#### lastQuestStartTime
`Integer`

Timestamp of when the last quest was started.

#### updateChecked
`Boolean`

#### experience
`Float`

#### lastQuestDuration
`Integer`

Number of sections the last quest lasted for.

#### hasUpdate
`Boolean`

#### timeToDie
`Integer`

Number of seconds on q eust before this mercenary dies.

#### creationEquipped
`Boolean`

## hasJoinedGuild
`Boolean`

Not sure if this works properly.

## prevLoginTimestamp
`Integer`

## stageQuality
`Boolean`

Flash quality setting.

## personalSales
`Object`

### flashSalesEnabled
`Boolean`

### _largestPurchaseBundleId
`Integer`

### _numHistoricSales
`Integer`

### seasonalSalesEnabled
`Boolean`

### _saleEndTimestamp
`Integer`

## timelapses
`Integer`

## clickMultiplier
`Integer`

## items
`Objects`

AKA relics.

### items
`Object`

The key is the item ID, the value is an `Object` in the following form:

#### bonusType4
`Integer`

The ID of the fourth bonus. 0 or null if there isn't a bonus.

#### bonusType1
`Integer`

The ID of the first bonus. 0 or null if there isn't a bonus.

#### bonus3Distribution
`Integer`

#### bonus1Level
`Float`

The number of levels the first bonus gives.

#### isNew
`Boolean`

Whether the player has seen the relic's stats or not.

#### rarity
`Integer`

#### bonus4Distribution
`Integer`

#### bonus2Level
`Float`

The number of levels the second bonus gives.

#### uid
`Integer`

#### upgradeCount
`Integer`

#### bonus3Level
`Float`

The number of levels the third bonus gives.

#### name
`String`

#### type
`String`

#### bonusType2
`Integer`

The ID of the second bonus. 0 or null if there isn't a bonus.

#### bonus1Distribution
`Integer`

#### level
`Integer`

#### bonusType3
`Integer`

The ID of the third bonus. 0 or null if there isn't a bonus.

#### bonus4Level
`Integer`

The number of levels the fourth bonus gives.

#### imageId
`Integer`

#### bonus2Distribution
`Integer`

### slots
`Object`

The key is the slot number, the value is the item (relic) ID.

### equipmentSlots
`Integer`

Number of slots the player has, filled or not.

### _currentUids
`Object`

#### items
`Integer`

### gotAscensionItem
`Boolean`

Whether the player got their free relic this ascension or not.

### ascensionItemsRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

### bonusZoneRoller
`Object`

This is to decide which zone the player gets their free ascension relic.

#### numUses
`Integer`

#### seed
`Integer`

### salvagePoints
`Integer`

Forge cores.

### guildItemsRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

## kongId
`String`

## allDpsMultiplier
`Float`

## purchasedGilds
`Integer`

## soulsSpent
`Integer`

## goldMultiplier
`Float`

## loginValidated
`Boolean`

## extraGildsAwarded
`Integer`

Number of purchased gilds that the player has been given this transcension.

## primalSouls
`Scientific`

## clickDpsPercent
`Float`

## isTestUser
`Boolean`

## respondedToSurvey
`Boolean`

This is about the Clicker Heroes 2 survey I think.

## creationTimestamp
`Integer`

## abaddonMultiplier
`Float`

## latestBuildLoaded
`Integer`

## respondedToEmailSequelPrompt
`Boolean`

## epicHeroReceivedUpTo
`Integer`

The highest zone the player has received a gild from.

## startTimestamp
`Integer`

## language
`null`

## musicEnabled
`Boolean`

## transcensionTimestamp
`Integer`

Time of the most recent transcension.

## lastPrimalLevelResult
`Boolean`

## hasSeenNewShopItems
`Boolean`

## unixTimestamp
`Integer`

## numWorldResets
`Integer`

Number of ascensions.

## lastPrimalLevelChecked
`Integer`

## epicHeroSeed
`Integer`

## dlcAutoclickers
`Integer`

## shouldShowHeroDps
`Boolean`

This corresponds to "Show individual hero DPS." in the settings.

## numAscensionsThisTranscension
`Integer`

## shouldAutoSetHeroDpsDisplay
`Boolean`

## autoclickers
`Integer`

## purchaseRecord
`Object`

## goldSacrificedInWorldResets
`null`

## highestHistoricAncients
`Integer`

## dpsSacrificedInWorldResets
`null`

## didClickOnAncientsTab
`Boolean`

Reset every transcension.

## skillCooldowns
`Object`

The key is the skill ID, the value is the timestamp the skill comes off
cooldown (or 0 if it already is off cooldown).

## didClickOnTranscendenceTab
`Boolean`

Resets every transcension.

## settings
`null`

## didClickOnMercenaryTab
`Boolean`

Resets every transcension.

## skillFreeClicksEnd
`Integer`

## skillFreeClicks
`Integer`

## didClickOnShopTab
`Boolean`

Deprecated?

## skillDpsMultiplier
`Float`

## freeRespecs
`Integer`

## skillDpsMultiplierEnd
`Integer`

## autoclickerSkins
`Object`

The key is the skin ID, the value is whether or not the player has the skin.
If the player does not have the skin, it won't show in this object anyway.

## numberDisplayMode
`Boolean`

True if "Always use scientific notation." is checked. False otherwise.

## skillCriticalClickChance
`Float`

Critical click chance granted from skills (currently only lucky strikes).

## currentAutoclickerSkin
`Integer`

Value is skin ID.

## accountId
`null`

## skillCriticalClickChanceEnd
`Integer`

Timestamp of when the crit bonus from skills ends.

## appliedDLC
`Object`

## isBanned
`Boolean`

## outsiders
`Object`

### _currentUids
`null`

### outsiders

The key is the outsider ID, the value is an `Object` in the following form:

#### level
`Integer`

#### id
`Integer`

#### uid
`Integer`

#### spentAncientSouls
`Integer`

## uid
`null`

## currentActivityOrderNumber
`null`

## skillGoldBonusEnd
`Integer`

Timestamp of when the gold bonus from skills ends.

## readPatchNumber
`String`

The latest version of the changelog the player has seen.

## version
`Integer`

## darkRitualClicks
`Integer`

## totalMercenariesRevived
`Integer`

## isCheater
`Boolean`

## lifetimeDarkRitualClicks
`Integer`

## totalMercenariesBuried
`Integer`
