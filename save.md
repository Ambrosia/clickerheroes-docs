# Save format

## abaddonMultiplier
`Float`

## account
`null`

## accountId
`null`

## achievements
`Object`

The key is the achievement ID, the value is a `Boolean`
(true if achieved, false otherwise).

## actionBar
`Object`

## activityCount
`Integer`

## activityRoller
`null`

## adCampaign
`null`

## adRetargetId
`null`

## adRetargetTime
`Integer`

## allDpsMultiplier
`Float`

## ancientEntrySizes
`Object`

## ancientSouls
`Integer`

The amount of unspent ancient souls the player currently has.

## ancientSoulsTotal
`Integer`

The amount of ancient souls, spent or unspent, the player has.

The highest zone the player has been to across all transcensions.

## ancients
`Object`

### _currentUids
`null`

### ancients
`Object`

The key is the ancient ID, the value is an `Object` in the following form:

#### id
`Integer`

#### level
`Scientific`

#### locked
`Boolean`

#### purchaseTime
`Integer`

#### spentHeroSouls
`Scientific`

#### uid
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

### numRerolls
`Integer`

### rerollSoulsSpent
`Integer`

## appliedDLC
`Object`

## autoclickerSkins
`Object`

The key is the skin ID, the value is whether or not the player has the skin.
If the player does not have the skin, it won't show in this object anyway.

## autoclickers
`Integer`

## baseClickDamage
`Integer`

## baseCriticalClickChance
`Integer`

Critical click chance when lucky strikes isn't active.

## buyExactQuantity
`Boolean`

## clickDpsPercent
`Float`

## clickMultiplier
`Integer`

## collectedAchievements
`Object`

Deprecated?

## collectedRaidRewardDates
`Object`

This object contains the dates of the last two times a raid was completed
and whether the reward has been collected by the player or not.
The key is a `Date` (`yyyy-mm-dd`) and the value is a `Boolean`.

## creationTimestamp
`Integer`

## criticalMultiplier
`Integer`

## currentActivityOrderNumber
`null`

## currentAutoclickerSkin
`Integer`

Value is skin ID.

## currentZoneHeight
`Integer`

The zone the player is currently on.

## damageFloatersDisabled
`Boolean`

Whether the click damage text is shown after the player clicks.
For some reason, it looks like there is no option for this in the game.

## darkRitualClicks
`Integer`

## debug
`Boolean`

## devGifts
`Object`

## didClickOnAncientsTab
`Boolean`

Resets every transcension.

## didClickOnMercenaryTab
`Boolean`

Resets every transcension.

## didClickOnShopTab
`Boolean`

Deprecated?

## didClickOnTranscendenceTab
`Boolean`

Resets every transcension.

## dlcAutoclickers
`Integer`

## dpsSacrificedInWorldResets
`null`

## email
`String`

## epicHeroReceivedUpTo
`Integer`

The highest zone the player has received a gild from.

## epicHeroSeed
`Integer`

## epicRoller
`Object`

### numUses
`Integer`

### seed
`Integer`

## extraGildsAwarded
`Integer`

Number of purchased gilds that the player has been given this transcension.

## finishedPrimals
`Object`

The key is the zone number, the value is whether the primal has been defeated
or not.

## freeRespecs
`Integer`

## gold
`Scientific`

## goldFloatersDisabled
`Boolean`

## goldMultiplier
`Float`

## goldQuestsCompleted
`Integer`

## goldSacrificedInWorldResets
`null`

## hasJoinedGuild
`Boolean`

Not sure if this works properly.

## hasSeenNewShopItems
`Boolean`

## hasSeenZone100Tip
`null`

## heroCollection
`Object`

### _currentUids
`Object`

#### heroes
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

### maxSize
`Integer`

## heroEntrySizes
`Object`

## heroSoulQuestsCompleted
`Integer`

## heroSouls
`Scientific`

The amount of hero souls the player currently has
(not the amount of hero souls the player receives after ascension).

## heroSoulsSacrificed
`Scientific`

## hideRelicPopups
`Boolean`

## highestFinishedZone
`Integer`

The highest zone the player has been to this ascension.

## highestFinishedZonePersist
`Integer`

The highest zone the player has been to this transcension.

## highestGold
`Scientific`

The highest amount of gold held by the player this transcension.

## highestHistoricAncients
`Integer`

## highestMercenaryLevelEver
`Integer`

## historicRubies
`Integer`

## isBanned
`Boolean`

## isCheater
`Boolean`

## isTestUser
`Boolean`

## items
`Objects`

AKA relics.

### _currentUids
`Object`

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

### equipmentSlots
`Integer`

Number of slots the player has, filled or not.

### gotAscensionItem
`Boolean`

Whether the player got their free relic this ascension or not.

### guildItemsRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

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

### slots
`Object`

The key is the slot number, the value is the item (relic) ID.

#### items
`Integer`

### salvagePoints
`Integer`

Forge cores.

## kongId
`String`

## language
`null`

## lastAdBonusTimestamp
`Integer`

## lastGuildRankUpdatedTime
`Integer`

## lastLoadTime
`null`

## lastPageLoadTime
`null`?

## lastPrimalLevelChecked
`Integer`

## lastPrimalLevelResult
`Boolean`

## lastRaidTimestamp
`Integer`

## lastSkillUsed
`Integer`

The skill that has its cooldown reduced by an hour when reload is used.

## latestBuildLoaded
`Integer`

## leeroyJenkinsBuried
`Integer`

## lifetimeDarkRitualClicks
`Integer`

## loginValidated
`Boolean`

## maxDps
`Scientific`

## mercenaries
`Object`

### _currentUids
`null`

### hasGivenOneFreeRecruit
`Boolean`

### mercRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

### mercenaries
`Object`

The key is the index and the value is an `Object` in the following form:

#### assetId
`Integer`

The appearance of the mercenary.

#### bonusLives
`Integer`

Amount of bonus lives this mercenary currently has.

#### createTime
`Integer`

#### creationEquipped
`Boolean`

#### experience
`Float`

#### hasUpdate
`Boolean`

#### lastQuestDuration
`Integer`

Number of seconds the last quest lasted for.

#### lastQuestGoldRewardQty
`Integer`

#### lastQuestRewardQty
`Float`

#### lastQuestRewardType
`Integer`

#### lastQuestStartTime
`Integer`

Timestamp of when the last quest was started.

#### lastQuestSuccessChance
`Float`

#### level
`Integer`

#### name
`String`

#### phrase1
`String`

Death phrase.

#### phrase2
`String`

Death phrase.

#### questResult
`Integer`

#### rarity
`Integer`

#### roller
`Object`

numUses: `Integer`

seed: `Integer`

#### slotId
`Integer`

The order this mercenary appears in inside the mercenaries tab. Zero-indexed.

#### statId
`Integer`

#### timeToDie
`Integer`

Number of seconds on quest before this mercenary dies.

#### updateChecked
`Boolean`

### questOptions
`Object`

### questRoller
`Object`

#### numUses
`Integer`

#### seed
`Integer`

### startRecruitTime
`Boolean`

## mercenaryCount
`Integer`

## mostClicksPerSecond
`Integer`

## mostCritsPerSecond
`Integer`

## musicEnabled
`Boolean`

## numAscensionsThisTranscension
`Integer`

## numPageLoads
`null`

## numRaidsToday
`Integer`

## numWorldResets
`Integer`

Number of ascensions.

## numberDisplayMode
`Boolean`

True if "Always use scientific notation." is checked. False otherwise.

## numberOfTranscensions
`Integer`

## outsiderEntrySizes
`Object`

## outsiders
`Object`

### _currentUids
`null`

### outsiders

The key is the outsider ID, the value is an `Object` in the following form:

#### id
`Integer`

#### level
`Integer`

#### spentAncientSouls
`Integer`

#### uid
`Integer`

## paidForRubyMultiplier
`Boolean`

Whether the player has the 2x damage bonus from the shop.

## passwordHash
`String`

## persistentVars

### allVisualEffects
`Boolean`

### bloopCoinRequestDonationTimestamp
`Integer`

### bloopCoins
`Integer`

### bossDefeatHelpTimestamp
`Integer`

### christmasSaleBuys
`Integer`

### cooldownNotificationsEnabled
`Boolean`

### didOpenAncientScreen
`Boolean`

### didOpenOnlineSave
`Boolean`

### didOpenShop
`Boolean`

### didPurchaseSkill
`Boolean`

### didShowTranscendenceNews
`Boolean`

### didUseSkill
`Boolean`

### fullscreen
`Boolean`

### goldNotificationsEnabled
`Boolean`

### halloweenSaleBuys
`Integer`

### karma
`Integer`

### mercenaryNotificationsEnabled
`Boolean`

### nextRatePromptTime
`Integer`

### preloadAds
`Boolean`

### previousEventAdsTimestamp
`Integer`

### previousMainScreenAdsTimestamp
`Integer`

### previousPermaAdsTimestamp
`Integer`

### pwbClosest
`Integer`

### pwbHelp
`Boolean`

### pwbPlayed
`Integer`

### pwbWon
`Integer`

### showBossDefeatHelp
`Boolean`

### showGildedHeroHelp
`Boolean`

### showItemHelp
`Boolean`

### showLevel100Help
`Boolean`

### showPrimalBossHelp
`Booolean`

## personalSales
`Object`

### _largestPurchaseBundleId
`Integer`

### _numHistoricSales
`Integer`

### _saleEndTimestamp
`Integer`

### flashSalesEnabled
`Boolean`

### seasonalSalesEnabled
`Boolean`

## pretranscendentHighestFinishedZone
`Integer`

## prevLoginTimestamp
`Integer`

## primalNumberGenerator
`Object`

### numUses
`Integer`

### seed
`Integer`

## primalSouls
`Scientific`

## privateAdminMessages
`Object`

## purchaseHashes
`Object`

## purchaseRecord
`Object`

## purchasedGilds
`Integer`

## purchasedTitanFightExpTime
`Integer`

## rarestMercenaryEver
`Integer`

## readPatchNumber
`String`

The latest version of the changelog the player has seen.

## relicQuestsCompleted
`Integer`

## relicsReceivedThisTranscension
`Integer`

## remoteQueue
`null`

## respondedToEmailSequelPrompt
`Boolean`

## respondedToSurvey
`Boolean`

This is about the Clicker Heroes 2 survey I think.

## revision
`null`

## rubies
`Integer`

## rubyClickablesThisAscension
`Integer`

## rubyQuestsCompleted
`Integer`

## secondToLastSkillUsed
`Integer`

The skill that has its cooldown reduced by an hour when energised reload is
used.

## settings
`null`

## shouldAutoSetHeroDpsDisplay
`Boolean`

## shouldShowHeroDps
`Boolean`

This corresponds to "Show individual hero DPS." in the settings.

## skillClickMultiplier
`Float`

## skillClickMultiplierEnd
`Integer`

## skillCooldowns
`Object`

The key is the skill ID, the value is the timestamp the skill comes off
cooldown (or 0 if it already is off cooldown).

## skillCriticalClickChance
`Float`

Critical click chance granted from skills (currently only lucky strikes).

## skillCriticalClickChanceEnd
`Integer`

## skillDouble
`Boolean`

Whether energise is currently active or not.

## skillDpsMultiplier
`Float`

## skillDpsMultiplierEnd
`Integer`

Timestamp of when the DPS bonus from skills ends.

## skillFreeClicks
`Integer`

## skillFreeClicksEnd
`Integer`

## skillGoldBonus
`Integer`

## skillGoldBonusEnd
`Integer`

Timestamp of when the gold bonus from skills ends.

## skillQuestsCompleted
`Integer`

## skillWildGold
`Integer`

## skillWildGoldEnd
`Integer`

## soulsSpent
`Integer`

## soundsEnabled
`Boolean`

## stageQuality
`Boolean`

Flash quality setting.

## startTimestamp
`Integer`

## syncedGameServices
`Boolean`

## ticketsUsed
`Object`

## timelapses
`Integer`

## tinyMonsters
`Boolean`

## titanDamage
`Scientific`

## titanTypesDefeated
`Object`

## total5MinuteQuests
`Integer`

## totalBossKills
`Integer`

## totalClicks
`Integer`

## totalCreditsPurchased
`null`

## totalCrits
`Integer`

## totalGold
`Scientific`

The total amount of gold the player has ever earned.

## totalGoldThisGame
`Scientific`

The amount of gold earned by the player this ascension.

## totalHeroLevels
`Integer`

## totalHeroSouls
`Scientific`

## totalHeroSoulsFromAscensions
`Scientific`

## totalKills
`Float`

## totalMercenariesBuried
`Integer`

## totalMercenariesRevived
`Integer`

## totalMoneySpent
`Float`

Amount of money player has spent on the game.

## totalPrimalsKilled
`Integer`

Time of the most recent transcension.

## totalRelicsReceived
`Integer`

## totalUpgrades
`Integer`

## transcendent
`Boolean`

## transcendentHighestFinishedZone
`Integer`

## transcensionTimestamp
`Integer`

## transparentAutoclickerMode
`Boolean`

## treasureChestsKilled
`Integer`

## tutorialArrow
`Integer`

## uid
`null`

## uniqueId
`String`

## unixTimestamp
`Integer`

## upgrades
`Object`

The key is the upgrade ID, the value is maybe whether the player has purchased
it or not (I have no idea).

## usedSkills
`Object`

The key is the skill ID, the value is always `true`.
The skills currently on cooldown. When not on cooldown, the skills will not
be shown in the object.

Whether the player has transcended or not.

## version
`Integer`

## worldGoldBonus
`null`
