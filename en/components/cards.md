# Cards

## Title Cards

### Card Examples

<div style="display: flex; gap: 20px; margin: 20px 0;">
  <img src="/Dynasties/_media/户部尚书.png" alt="Minister of Treasury" style="max-width: 200px; border-radius: 8px;">
  <img src="/Dynasties/_media/中书令.png" alt="Secretary of State" style="max-width: 200px; border-radius: 8px;">
  <img src="/Dynasties/_media/太常卿.png" alt="Master of Ceremonies" style="max-width: 200px; border-radius: 8px;">
</div>

* Tang ×10 (Yellow), Song ×10 (Green), Yuan ×10 (Blue), Ming ×10 (Red)

### Title Reference Table

| Tang | Song | Yuan | Ming | Execute Policy | Issue Policy |
| --- | --- | --- | --- | --- | --- |
| Secretary of State | Prime Minister | Secretary of State | Chief Grand Counselor |  | Cede Territory / Train Troops / Reduce Subjects / Comfort People / Recruit Merchants / Expand Market |
| Minister of Personnel | Registrar | Prime Minister | Minister of Personnel | Rebellion: Appease / Coup: Concede / Invasion: Surrender |  |
| Minister of Treasury | Commissioner of Salt & Iron | Minister of Treasury | Minister of Treasury | Drought: Grant Grain / Earthquake: Aid / Flood: Dredge |  |
| Minister of Rites | Minister of Rites | Master of Ceremonies | Master of Rites | Drought: Prayer / Plague: Medicine / Invasion: Surrender |  |
| Minister of Public Works | Chancellor of National University | Chancellor of National University | Minister of Public Works | Earthquake: Rebuild / Flood: Dredge / Flood: Relocate |  |
| Minister of Justice | Chief Censor | Chief Censor | Minister of Justice | Plague: Quarantine / Corruption: Anti-Corruption / Coup: Purge |  |
| Minister of War | Director of Chancellery | Director of Chancellery | Supreme Military Commander | Rebellion: Suppress / Invasion: Fight / Plague: Quarantine |  |
| Regional Commander | Prefect | Provincial Prime Minister | Regional Governor | Invasion: Fight / Flood: Relocate / Rebellion: Suppress |  |
| Chief Censor | Remonstrator | Darugachi | Chief Censor | Corruption events do not trigger |  |
| Master of Ceremonies | Hanlin Academy Scholar | Chief of Department of State Religion | Chancellor of National University | Drought: Prayer | Blessing to Extend Life |


## Policy Cards

### Execute Policy

<div style="display: flex; gap: 20px; margin: 20px 0;">
  <div style="text-align: center;">
    <img src="/Dynasties/_media/政策卡牌背面.png" alt="Policy Card - Back" style="max-width: 200px; border-radius: 8px;">
    <p>Policy Card - Back</p>
  </div>
  <div style="text-align: center;">
    <img src="/Dynasties/_media/政策卡牌正面.png" alt="Policy Card - Front" style="max-width: 200px; border-radius: 8px;">
    <p>Policy Card - Front</p>
  </div>
</div>

* One set per faction ×4

* Drought ×3, Earthquake ×3, Flood ×3, Plague ×3
* Rebellion ×3, Invasion ×3, Coup ×3, Corruption ×2

#### Drought

* Grant Grain: Treasury -1500; Livelihood +1, Wealth -1
* Prayer: Treasury -500, roll die
  * 1~3 success, Livelihood +1
  * 4~6 failure, Wealth -1
* Neglect: Livelihood -1, Wealth -2

#### Earthquake

* Rebuild: Treasury -1500; Livelihood +2, Wealth -1
* Aid: Treasury -1000, roll die
  * 1~3 success, Livelihood +1, Wealth +1
  * 4~6 failure, Treasury -1000, Livelihood -1
* Neglect: Livelihood -1, Wealth -1

#### Flood

* Dredge: Treasury -1500, roll die
  * 1~3 success, Livelihood +1, Wealth +1
  * 4~6 failure, Treasury -1000, Livelihood -1
* Relocate: Treasury -800; Wealth -1
* Neglect: Livelihood -1, Wealth -1

#### Plague

* Medicine: Treasury -1500, roll die
  * 1~3 success, Livelihood +1
  * 4~6 failure, Livelihood -1, Wealth -1
* Quarantine: Treasury -800; Livelihood -1, Wealth -1
* Neglect: Livelihood -2, Wealth -1

#### Rebellion: Triggered when Livelihood ≤ 3

* Suppress: Livelihood -1, roll die
  * 1 ~ Military for success, Treasury +1000
  * Otherwise failure, Treasury -1500, Military -1
* Appease: Military -1; Treasury -800
* Neglect: Treasury -1500; Livelihood +1, Wealth -2

#### Invasion: Triggered when Military ≤ 3

* Fight: Livelihood -1, roll die
  * 1 ~ Military for success, Treasury +2000, Wealth +1
  * Otherwise failure, Treasury -2500, Military -1, Wealth -1
* Surrender: Military -1; Treasury -1500, Wealth -1
* Neglect: Lose 3 land tiles + citizen tokens on them; Livelihood +1, Wealth -1

#### Coup: Triggered when Military ≥ 4

* Purge: Treasury -1500, roll die
  * 1 ~ Military for success, Treasury +1000, Wealth +1
  * Otherwise failure, Treasury -2000, Livelihood -1, Wealth -1
* Concede: Forfeit next turn; Treasury -800, Military -1
* Neglect: Treasury -1000; Military -1, Livelihood -2

#### Corruption: Triggered when Wealth ≥ 4

* Anti-Corruption: Treasury -800
* Neglect: Livelihood -1; Treasury +500, Wealth -1

### Issue Policy

<div style="display: flex; gap: 20px; margin: 20px 0;">
  <div style="text-align: center;">
    <img src="/Dynasties/_media/颁布政策-背面.png" alt="Issue Policy - Back" style="max-width: 200px; border-radius: 8px;">
    <p>Issue Policy - Back</p>
  </div>
  <div style="text-align: center;">
    <img src="/Dynasties/_media/颁布政策-正面.png" alt="Issue Policy - Front" style="max-width: 200px; border-radius: 8px;">
    <p>Issue Policy - Front</p>
  </div>
</div>

* One set per faction ×4
* Cede Territory / Train Troops ×1, Reduce Subjects / Comfort People ×1, Recruit Merchants / Expand Market ×1, Blessing to Extend Life ×1

| Attribute | Policy Name | Condition to Gain |
| --- | --- | --- |
| Military +1 | Cede Territory / Train Troops | Lose 3 faction land tiles and citizen tokens on them |
| Livelihood +1 | Reduce Subjects / Comfort People | Remove 3 citizen tokens |
| Wealth +1 | Recruit Merchants / Expand Market | Treasury -1500 |
| Faith +1 | Blessing to Extend Life | Military -1, Livelihood -1, Wealth -1 |


### Special Policies

| Dynasty | Special Policy Card | Effect |
| --- | --- | --- |
| Tang | Inflation Card ×3 | Grain price increases to 300/unit for this round |
| Song | Dismissal of Generals Card ×3 | Other factions' battle strength -3 for this round |
| Yuan | Territorial Expansion Card ×3 | This faction rolls +1 die for this round |
| Ming | Reconstruction of Confucian Schools Card ×3 | This faction gains citizen tokens twice in the initial phase |


## Grain Cards

* 2.5cm × 2.5cm small cards

* 3-unit Grain Card ×10, 2-unit Grain Card ×18, 1-unit Grain Card ×24
