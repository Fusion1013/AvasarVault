# Calendar Overview
## Overview
The year is split into 653 days, or 16 months. All months have 41 days, except for [[Zermid]] which has 38 days.
## Days of the Week
The names for the days of the week are based on the names for the major celestial bodies, in order from Taiya. There are 5 weeks/month.
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
(day_order + 1) + ": [[" + file.name + "]]" AS "Day Name",
astral_body AS "Astral Body"
FROM #week_day 
SORT day_order ASC
```
%%

| Day Name       | Astral Body                                           |
| -------------- | ----------------------------------------------------- |
| 1: [[Taidar]]  | [[Cosmology/Cosmology Overview.md#Taiya\|Taiya]]      |
| 2: [[Auridar]] | [[Cosmology/Cosmology Overview.md#Aurius\|Aurius]]    |
| 3: [[Saidar]]  | [[Cosmology/Cosmology Overview.md#Sahti Dark\|Sahti]] |
| 4: [[Gadar]]   | [[Cosmology/Cosmology Overview.md#Gaia\|Gaia]]        |
| 5: [[Avadar]]  | [[Cosmology/Cosmology Overview.md#Avasar\|Avasar]]    |
| 6: [[Epidar]]  | [[Cosmology/Cosmology Overview.md#Epistos\|Epistos]]  |
| 7: [[Yondar]]  | [[Cosmology/Cosmology Overview.md#Yomi\|Yomi]]        |
| 8: [[Delidar]] | [[Cosmology/Cosmology Overview.md#Delir\|Delir]]      |

%% DATAVIEW_PUBLISHER: end %%
### Months
The names for the months have their roots from the names of the gods, with influences from [[Proto-Naiwa]].
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
(order + 1) + ": [[" + file.name + "]]" AS "Month Name",
god AS "God"
FROM #month 
SORT order ASC
```
%%

| Month Name      | God                                                                                                         |
| --------------- | ----------------------------------------------------------------------------------------------------------- |
| 1: [[Cirsyl]]   | [[Pantheon/Major Gods/Lu'Syl - the Twilight Twins.md\|Lu'Syl, Light Twin]]                                  |
| 2: [[Sahr]]     | [[Pantheon/Minor Gods/Saheir - the Enchantress.md\|Saheir - the Enchantress]]                               |
| 3: [[Inora]]    | [[Pantheon/Minor Gods/Isoroa - the Shadowed Mask.md\|Isoroa - the Shadowed Mask]]                           |
| 4: [[Scarnoc]]  | [[Pantheon/Minor Gods/Ogrun - the Scarlet Champion.md\|Ogrun - the Scarlet Champion]]                       |
| 5: [[Orzen]]    | [[Pantheon/Minor Gods/Vuzen - the Law Baron.md\|Vuzen - the Law Baron]]                                     |
| 6: [[Verra]]    | [[Pantheon/Major Gods/Anvarra - the Soulless Mistress.md\|Anvarra - the Soulless Mistress]]                 |
| 7: [[Nerduva]]  | [[Pantheon/Minor Gods/Verdus - the Earthweaver.md\|Verdus - the Earthweaver]]                               |
| 8: [[Sensari]]  | [[Pantheon/Major Gods/Mau'Sari - the Divine Essence.md\|Mau'Sari - the Divine Essence]]                     |
| 9: [[Zermid]]   | [[Pantheon/Minor Gods/Midar - the Unshackled.md\|Midar - the Unshackled]]                                   |
| 10: [[Loutrix]] | [[Pantheon/Minor Gods/Intrix - the Prime Sculptor.md\|Intrix - the Prime Sculptor]]                         |
| 11: [[Hurise]]  | [[Pantheon/Minor Gods/Verise - the Unmasked Goddess.md\|Verise - the Unmasked Goddess]]                     |
| 12: [[Duvria]]  | [[Pantheon/Minor Gods/Irellia - Mistress of the Tranquil Lake.md\|Irellia - Mistress of the Tranquil Lake]] |
| 13: [[Merthim]] | [[Pantheon/Minor Gods/Merstur - the Unbroken Tide.md\|Merstur - the Unbroken Tide]]                         |
| 14: [[Vedzer]]  | [[Pantheon/Major Gods/Veda - the Elder Scribe.md\|Veda - the Elder Scribe]]                                 |
| 15: [[Aznoc]]   | [[Pantheon/Major Gods/Aztaris - the Shepherd of Souls.md\|Aztaris - the Shepherd of Souls]]                 |
| 16: [[Nocsyl]]  | [[Pantheon/Major Gods/Lu'Syl - the Twilight Twins.md\|Lu'Syl, Dark Twin]]                                   |

%% DATAVIEW_PUBLISHER: end %%