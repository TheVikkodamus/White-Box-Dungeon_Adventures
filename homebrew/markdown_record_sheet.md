
# Character Record Sheet

<!-- Hello and welcome to your character sheet! Don't worry, this text won't show on your finalized sheet unless you are editing it. 

Here is how to fill out your sheet:
- You don't need to enter numbers while editing code. Once you exit edit mode, simply click a number field to enter your value. 
- Note: This is not an automated/smart sheet. If you change an Ability Score, consult your GM/Referee or the OSE SRD to enter the matching modifier manually.
- On the tables, everything is set up for you. You only need to edit regular text fields. 
- DO NOT edit anything that looks like number(name=...) or rollable(dice=...). Leave those exact formulas as they are!

If you need to add equipment or abilities later, open the editor and make your changes. If you have any questions, hit me up via Discord!  This markdown is friendly for Goblin Notebook-->


|  |  |  |  |
| :--- | :--- | :--- | :--- |
| **Name** |  | **Player** |  |
| **Class** | | | |
| **Level** | number(name=level_score,label=Add Current Level,value=1) | **Alignment** | |
| **XP** | number(name=current_exp,label=Add your earned xp,value=0) | **Next** | number(name=next_level_up,label=Add your next level up,value=1000) |
| **Game Master** | | **Game Location** | |


---

## Ability Scores

| Attribute | Score | Modifier | Notes / Effects |
| :---: | :---: | :---: | :--- |
| **STR** | number(name=strength_score,label=Add/Change your Strength Score,value=10)|number(name=strength_mod,label=Add/Change your STR modifier,value=0)| |
| **INT** | number(name=intelligence_score,label=Add/Change your Intelligence Score,value=10)| number(name=intelligence_mod,label=Add/Change your INT modifier,value=0)| |
| **WIS** | number(name=wisdom_score,label=Add/Change your Wisdom Score,value=10)| number(name=wisdom_mod,label=Add/Change your WIS modifier,value=0)| |
| **DEX** | number(name=dexterity_score,label=Add/Change your Dexterity Score,value=10)| number(name=dexterity_mod,label=Add/Change your DEX modifier,value=0)| |
| **CON** | number(name=constitution_score,label=Add/Change your Constitution Score,value=10)| number(name=constitution_mod,label=Add/Change your CON modifier,value=0)| |
| **CHA** | number(name=charisma_score,label=Add/Change your Charisma Score,value=10)| number(name=charisma_mod,label=Add/Change your CHA modifier,value=0)| |
| **Saving Throws** | number(name=saving_throws,label=Add/Change your Saving Throw Score, value=10 | | |

---

## Combat Stats

| Stat | Value ||
| :--- | :---: |:---:|
| **Hit Points** |  number(name=hp,label=Hit Points,value=5) | number(name=curr_hp,label=Current Hit Points,value=7)|
| **Armor Class** | umber(label=Armor Class,name=ac,value=14) | number(label=Thaco,name=tc,value=5)|
| **Movement** | number(name=normal_speed,label=Exploring Speed,value=120) ft| number(name=battle_speed,label=Battle Speed,value=40) ft|



### Weapons
* **Melee Weapon:** rollable(1d20+field[strength_mod]) | **Damage:** rollable(1d8)| *Melee* 
* **Range Weapon:** rollable(1d20+field[dexterity_mod]) | **Damage:** rollable(1d8) | *Missile, range, two-handed*


---

### Class/Background Abilities

*Description/Flavor text here.*

* **Ability Name**: Description
* **Ability Name**: Description
* **Ability Name**: Description

**Languages:** 

---

## Gear and Equipment

| Equipment | Quantity | Weight |
| :--- | :---: | :---: |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| **Current Weight** | | **Max Carry:** |
