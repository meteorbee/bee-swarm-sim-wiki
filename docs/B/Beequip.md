# Beequip

[[File:Bear bee with pinecone.png|thumb|A Bear Bee with a Pinecone Beequip.]]
A '''Beequip''' is a type of [[:Category:Inventory|inventory item]] that can be worn by [[bees]]. When equipped to a bee, they alter its stats and can also give bonuses to the hive. Beequips can only be given to bees that are at or above the level of the Beequip. Some Beequips can only be given to certain bees or types of bees, for example, the {{Cost|Bubble Light|4=0}} requires a bee with an energy [[mutation]].

==Beequip Cases and Storage==
[[File:Beequip Case.png|thumb|100px|The Beequip Case.|alt=]]
When a Beequip is obtained, they are initially stored in a Beequip Case. The Beequip Case is obtained when the player first talks to [[Dapper Bear]] at his [[Dapper Bear's Shop|shop]]. The player starts off with five slots but can obtain additional slots from [[Dapper Bear]]'s quests and [[Bee Bear]]'s quests during Beesmas 2020, with the total amount of slots being 15 Beequips. Beequips in a case can be given to bees.
{| class="sortable article-table"
|+Extra storage slots (does not affect how many Beequips can be equipped)
!{{Cost|Ticket}}
!Total storage
|-
|100
|15
|-
|250
|20
|-
|450
|25
|-
|800
|30
|-
|1,250
|35
|-
|1,850
|40
|-
|2,550
|45
|-
|3,400
|50
|-
|4,400
|55
|-
|5,550
|60
|-
|6,800
|65
|-
|8,250
|70
|-
|9,800
|75
|-
|11,550
|80
|-
|13,400
|85
|-
|15,450
|90
|-
|17,650
|95
|-
|20,000
|100
|-
! colspan="2" ; |Total: {{Cost|Ticket|123500}}
|}

[[File:Beequip Storage.png|thumb|100x100px|The Beequip Storage.|alt=]]
[[File:BeequipStorageIcon.png|thumb|The quest reward icon for the Beequip Storage.]]
If all the slots of the Beequip case are filled, Beequips are moved to the Beequip Storage, located near the [[Dandelion Field]], or the [[Public Sticker Board]] in the Hive Hub. Beequips in the storage ''cannot'' be given to bees. By default, the storage has 10 slots. However, the player can purchase 90 additional slots, for a max total of 100, with a total of 123,500 tickets. Additional slots could have been obtained by completing some of Bee Bear's quests during Beesmas 2020. If both the storage and case are full, the Beequips are stored in the inbox. The inbox can store the player's 25 most recent Beequips, but they have a 48-hour time limit before being discarded automatically. If the player doesn't want a certain Beequip in the inbox to be deleted, they can empty a slot in the case, and then they can keep the Beequip.

There are special Beequips that are permanent and can be stored in the ‘permanents’ section of the Beequip Storage without taking up any space. However, those special Beequips will still require a case slot in order to be equipped to a bee. Currently, there are no permanent Beequips, since the ones that used to be (the [[Reindeer Antlers]] and [[Festive Wreath]]) were made normal Beequips, with Onett saying that he might get rid of the permanent Beequip feature. 

Beequips can be moved around the Beequip case, storage, and inbox by dragging them to the location they would like to be put at.

==Potential==
Beequips have a potential that can range from 0-5 stars. In-game, this value is stored as a float between 0 and 1; however, for simplicity, the wiki will represent this value as a number between 0 and 10 half-stars.

The potential of a Beequip '''cannot''' change.

When displayed, the potential will round to the nearest star (nearest half-circle in Dapper Bear’s shop).

The higher the potential a Beequip has, the higher chance the Beequip having better base stats, better upgrades and better chance of certain stats to increase when using [[Waxes]]. 

==Base Stats==
<!--someone please swoop in and rewrite this section i'm tired-->
When a Beequip is first generated, or when a {{Cost|Swirled Wax|4=0}} is applied to it, it is given a new set of base stats.

Each possible stat on the Beequip has a chance of being in this new set of base stats, with a value between 2 pre-determined limits. The chance and limits are dependant on the stat and the Beequip.

Note that the base stats are not dependant on {{Cost|Caustic Wax}}, i.e. you can have an otherwise Caustic-only stat on a Beequip as its base stats.

==Waxes==
Each type of wax has its own "Upgrades Value", which is essentially its amount of upgrade rolls. Each upgrade roll is an upgrade to one stat.<ref name=":0">This data was taken from the [https://docs.google.com/spreadsheets/d/1DFvWFNN7euft6ELtkif0BgORQIppZ3PnrLWwk0dfAEQ/edit?gid=690777983#gid=690777983 Beequip Spreadsheet].</ref>
{| class="article-table"
!Wax
!Upgrades Value
|-
|{{Cost|Soft Wax|||0}}
|1
|-
|{{Cost|Hard Wax|||0}} 
|2
|-
|{{Cost|Caustic Wax|||0}}
| 4
|-
|{{Cost|Debug Wax|4=0}}
| 4
|-
|{{Cost|Swirled Wax|||0}}
|0
|}
* If the wax is successful, it applies a number of upgrade rolls to the Beequip, equal to the value given in the table above. Each upgrade roll improves a single stat once.
* Each individual Beequip stat can only be improved a set number of times using the upgrade rolls. This number is dependant on the stat and the Beequip. 
**When a stat reaches its maximum number of upgrade rolls, later upgrade rolls will ignore the stat.
**This means every Beequip stat has a maximum value it can reach.
**Some stats may only be improved by an upgrade roll given by a {{Cost|Caustic Wax|||0}}.
*Up to 5 waxes can be applied on a Beequip. 
**As a result, it may be better to risk using waxes with a chance to fail in order to achieve better stats and/or have a better chance at getting the stat you need.
* Each stat has a weight, which dictates the chance at which the stat is chosen by an upgrade roll.
**The chance at which a stat is chosen by an upgrade roll uses the formula:<math> \frac{weight\_of\_stat}{sum\_of\_weights} \times 100\%</math> 
***Example: If a Beequip has two stats with a weight of 1, one stat with a weight of 0.1 and two stats with a weight of 0.02, the chance of an upgrade roll choosing the stat with the weight of 0.1 is <math>\frac{0.1}{1+1+0.1+0.02+0.02} \times 100\% \simeq 4.67\%</math>.
***Note that in the linked spreadsheet<ref name=":0" /> and on the wiki, a percentage is given instead of a number. The same formula can be applied.
**This weight may be increased based on the Beequip's potential.
**If a stat is ignored, its weight is not included in the sum.
***This can happen due to the stat having reached its maximum number of upgrade rolls, or due to the upgrade roll not being given by a {{Cost|Caustic Wax|||0}}.
* When a stat is chosen, it is improved by an amount equal to one of multiple different values. The amount is dependant on the stat and the Beequip.
** In some cases where there are more than 1 value present, a '''bias''' may be applied to make some values have better or worse chances of being chosen than others.
***This bias is based on the stat and the Beequip, especially its potential.
***The base bias is 2, though some stats multiply this by a separate value.
***For stats with exactly 2 values present, the chance for each value to be chosen can be calculated using formulas <math>\frac{bias - potential \times \frac{bias - 1}{10}}{bias + 1} \times 100\%</math> and <math>\frac{1 + potential \times \frac{bias - 1}{10}}{bias + 1} \times 100\%</math> respectively.
****Example: If a stat has a potential of 2 stars (i.e. 4 potential), and a bias of 4, the chance for the first value is <math>\frac{4 - 4 \times \frac{4-1}{10}}{4 + 1} \times 100\% = 56\%</math> and the chance for the second value is <math>\frac{1 + 4 \times \frac{4-1}{10}}{4 + 1} \times 100\% = 44\%</math>.
***For stats with more than 2 values present, the formula is not known.

==Gallery ==
<gallery>
BeequipSample.png|A Beequip in the Beequip Storage or Case.
BeequipLevelCropped.png|Clicking the level for a Beequip.
BeequipColorCropped.png|Clicking the color for a Beequip.
BeequipLimitCropped.png|Clicking the limit for a Beequip.
BeequipPotentialCropped.png|Clicking the potential for a Beequip.
BeequipBeesmasCropped.png|Clicking the Beesmas icon for a Beesmas Beequip.
BeequipToken1.png|A Beequip token's old design, with an orange color.
BeequipToken2.png|A Beequip token's current design, with a green color.
</gallery>

==Beequips==
[[Category:Pages that uses original tabber]]
<tabber>
|-|Non-Event=
Non-Event Beequips were added on April 1, 2022, and can be obtained from planters (the Dandelion Field has a much higher chance of dropping Beequips than other fields).

<tabview>
Thimble|Thimble
Sweatband|Sweatband
Bandage|Bandage
Thumbtack|Thumbtack
Camo Bandana|Camo Bandana
Bottle Cap|Bottle Cap
Kazoo|Kazoo
Smiley Sticker|Smiley Sticker
Whistle|Whistle
Charm Bracelet|Charm Bracelet
Paperclip|Paperclip
Beret|Beret
Bang Snap|Bang Snap
Bead Lizard|Bead Lizard
Pink Shades|Pink Shades
Lei|Lei
Demon Talisman|Demon Talisman
Camphor Lip Balm|Camphor Lip Balm
Autumn Sunhat|Autumn Sunhat
Rose Headband|Rose Headband
Pink Eraser|Pink Eraser
Candy Ring|Candy Ring
</tabview>

|-|Beesmas=

[[Beesmas]] Beequips were added during Beesmas 2020 and are only obtainable during Beesmas events, but can still be used year-round.

<tabview>
Elf Cap|Elf Cap
Single Mitten|Single Mitten
Warm Scarf|Warm Scarf
Peppermint Antennas|Peppermint Antennas
Beesmas Top|Beesmas Top
Pinecone|Pinecone
Icicles|Icicles
Beesmas Tree Hat|Beesmas Tree Hat
Bubble Light|Bubble Light
Snow Tiara|Snow Tiara
Snowglobe|Snowglobe
Reindeer Antlers|Reindeer Antlers
Toy Horn|Toy Horn
Paper Angel|Paper Angel
Toy Drum|Toy Drum
Lump Of Coal|Lump Of Coal
Poinsettia|Poinsettia
Electric Candle|Electric Candle
Festive Wreath|Festive Wreath
</tabview>
</tabber>

[[Category:Items]]
[[Category:Beequips]]
[[Category:Inventory]]
[[Category:Mechanics]]

<references />