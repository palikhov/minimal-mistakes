---
title: "Руководство игрока по использованию листа персонажа 5e OGL by Roll20"
permalink: /roll20-guide/players-guide-ogl/
excerpt: "How the theme is organized and what all of the files are for."
last_modified_at: 2018-03-20T15:19:22-04:00
---

## Кратко о нюансах Roll20

### Общий вид 

![Общий вид Roll20](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-general-view-player02.png)

1 - 

2 - Включенная панель макросов с кнопками вызовов макросов

3 -  Основное меню (пункты меню слева направо Чат / Токены / Журнал / Компендиум / Звуковой плеер / Макросы / Настройки)

### Включение панели макросов и просмотр доступных макросов

Для того чтобы включить панель макросов - в правом меню переходим в вкладку "Макросы" и отмечаем пункт меню **Show macro quick bar?**

![macrobar](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-player-view-macros.png)

### Компендиум

![compendium](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-player-view-compendium.png)

### Чат, как его вынести в отдельное окно

Двойной клик левой кнопкой мыши на иконке чата в правом меню

### Действия токена (token actions)

Кнопки действий, привязанные к токену - действия токена (token actions), видны только при выборе токена. Видны могут быть действия двух видов: глобальные, привязанные к настройкам доступных макросов, у которых отмечено **Показывать как действия токенов** и локальные, привязанные к конкретному листу персонажа (если токен связан с конкретным листом персонажа)

![tokenactions](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-token-action01.png)

### "Бары" у токена, настройки и "статус маркеры"

![token-bars](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-token-selected-player01.png)

По умолчанию приняты следующие привязки:

Крайний левый - красный - Hit Points

Средний - зеленый - Armor Class

Крайний правый - синий - Speed

HP и AC необходимы мастеру, но бар с Speed можно перенастраивать на любые другие атрибуты листа персонажа. К сожалению, сделать это может только мастер, поэтому при необходимости следует к нему обратиться.

![status-markers](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-status-markers.png)

Статус маркеры используются для отслеживания состояния и эффектов на персонаже. Более детально - смотри описание макроса [Conditions]()

![tokenbarsedit](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-edit-token-gmview01.png)

Меню редактирования свойств токена, в т.ч. ауры выглядит следующим образом (с т.з. ГМа)

### Заметки

Заметки являются важной частью Roll20 и их тоже можно выносить в отдельное окно. Для этого надо нажать кнопку в левом верхнем углу заметки.

![handoutview](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-handout-view-01.png)

### Вынесенные в отдельные окна окна чата и заметки

Если вынести и чат, и заметки в отдельные окна, то можно работать как удобно - переносить на отдельные экраны (второго монитора), на виртуальные столы, быстро переключаться между различными заметками.

![popouts](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img-roll20-chathandout-popouts.png)


### Экспорт и импорт персонажей между кампаниями

Персонажи могут быть импортированы из любой игры. Экспорт же персонажей в игру основан на уровне доступа к Хранилищу игры.

#### Ограниченный доступ к Хранилищу - Limited Vault Access.

Позволяет только игрокам с подпиской уровня Про или Плюс экспортировать их персонажей в эту игру. Такой доступ установлен для каждой игры по умолчанию.

#### Полный доступ к Хранилищу персонажей - All Access Vault.

Позволяет любому игроку или ГМу, включая игроков без подписки, экспортировать персонажей в эту игру. Игры созданные игроками с подпиской Про или Плюс или игры основанные на модулях из  магазина имеют по умолчанию данный уровень доступа к хранилищу.

#### Хранилище персонажей 

Доступ находится на главной странице в подменю Tools

![Хранилище персонажей](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img/img-roll20-import-export-character-vault-01.png)

После открытия Хранилища вы увидите список своих импортированных персонажей ...
![Список персонажей](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img/img-roll20-import-export-character-vault-02.png)

... и можете или импортировать еще одного.
![Импорт персонажа](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img/img-roll20-import-export-character-vault-03.png)

... или экспортировать уже имеющегося в другую игру.
![Экспорт персонажа](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img/img-roll20-import-export-character-vault-04.png)

***

## Лист персонажа для D&D5e - 5e OGL Roll20 



## 5e OGL ROLL20 Templates

[Roll20 wiki](https://wiki.roll20.net/D%26D_5e_OGL_Roll_Templates)

### Описание

```
 &{template:desc} {{desc=desc}}
```
![](https://wiki.roll20.net/images/9/90/D%26D_5E_OGL_Description_Template.jpg)

###  Simple

```
&{template:simple} {{rname=rname}} {{mod=mod}} {{r1=r1}} {{always=1}} {{r2=r2}} {{charname=charname}} 
```
![](https://wiki.roll20.net/images/4/48/D%26D_5E_OGL_Simple_Template.jpg)

### Attack

```
&{template:atk} {{mod=mod}} {{rname=rname}} {{rnamec=rnamec}} {{r1=r1}} {{always=1}} {{r2=r2}} {{range=range}} {{desc=desc}} {{spelllevel=spelllevel}} ammo=ammo {{charname=charname}} 
```

![](https://wiki.roll20.net/images/d/d7/D%26D_5E_OGL_Atk_Template.jpg)

### Damage

```
&{template:dmg} {{rname=rname}} {{range=range}} {{damage=1}} {{dmg1flag=1}} {{dmg1=dmg1}} {{dmg1type=dmg1type}} {{dmg2flag=1}} {{dmg2=dmg2}} {{dmg2type=dmg2type}} {{crit=1}} {{crit1=crit1}} {{crit2=crit2}} {{save=1}} {{saveattr=saveattr}} {{savedesc=savedesc}} {{savedc=savedc}} {{desc=desc}} {{hldmg=hldmg}} {{spelllevel=spelllevel}} ammo=ammo {{charname=charname}} 
```

![](https://wiki.roll20.net/images/e/ea/D%26D_5E_OGL_Dmg_Template.jpg)


###  Attack & Damage 

```
&{template:atkdmg} {{mod=mod}} {{rname=rname}} {{r1=r1}} {{always=1}} {{r2=r2}} {{attack=1}} {{range=range}} {{damage=1}} {{dmg1flag=1}} {{dmg1=dmg1}} {{dmg1type=dmg1type}} {{dmg2flag=1}} {{dmg2=dmg2}} {{dmg2type=dmg2type}} {{crit1=crit1}} {{crit2=crit2}} {{save=1}} {{saveattr=saveattr}} {{savedesc=savedesc}} {{savedc=savedc}} {{desc=desc}} {{hldmg=hldmg}} {{spelllevel=spelllevel}} ammo=ammo {{charname=charname}} 
```
![](https://wiki.roll20.net/images/6/64/D%26D_5E_OGL_AtkDmg_Template.jpg)

### Spell

```
&{template:spell} {{level=school level}} {{name=name}} {{castingtime=castingtime}} {{range=range}} {{target=target}} {{v=1}} {{s=1}} {{m=1}} {{material=material}} {{duration=duration}} {{description=description}} {{athigherlevels=athigherlevels}} {{ritual=1}} {{concentration=1}} {{charname=charname}}
```

![](https://wiki.roll20.net/images/b/b8/D%26D_5E_OGL_Spell_Template.jpg)


### NPC Action

```
&{template:npcaction} {{attack=1}} {{damage=1}} {{dmg1flag=1}} {{dmg2flag=1}} {{name=name}} {{rname=rname}} {{r1=r1}} {{always=1}} {{r2=r2}} {{dmg1=dmg1}} {{dmg1type=dmg1type}} {{crit1=crit1}} {{dmg2=dmg2}} {{dmg2type=dmg2type}} {{crit2=crit2}} {{description=description}} 
```
![](https://wiki.roll20.net/images/3/3e/D%26D_5E_OGL_NpcAction_Template.jpg)

### NPC Attack
```
&{template:npcatk} {{attack=1}} {{name=name}} {{rname=rname}} {{rnamec=rnamec}} {{r1=r1}} {{always=1}} {{r2=r2}} {{description=description}} 
```
![](https://wiki.roll20.net/images/9/96/D%26D_5E_OGL_NpcAtk_Template.jpg)


### NPC Damage

```
&{template:npcdmg} {{damage=1}} {{dmg1flag=1}} {{dmg2flag=1}} {{dmg1=dmg1}} {{dmg1type=dmg1type}} {{dmg2=dmg2}} {{dmg2type=dmg2type}} {{crit=1}} {{crit1=crit1}} {{crit2=crit2}} 
```
![](https://wiki.roll20.net/images/c/c8/D%26D_5E_OGL_NpcDmg_Template.jpg)

![]()

![]()
## Скрипты

[GroupCheck](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#groupcheck)

[GroupInitiative](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#groupinitiative)

-[It's a Trap!](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#its-a-trap)

-[It's a Trap = D&D 5e Generic]()

[Welcome Package](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#welcome-package)

[TokenNameNumber](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#tokennamenumber)

[ChatSetAttr](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#chatsetattr)

[Aura/Tint Health Colors](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#auratint-healthcolors)

[5eOGL-statblock](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#5eogl-statblock)

[TokenStatus](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#token-status-manager)

[TokenMod](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#tokenmod)

[TokenActions](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#token-actions)

[5eogl-books](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#5eogl-books)

[5th Edition OGL by Roll20 Companion](https://github.com/palikhov/palant_roll20_setup/wiki/02.-API-Scripts#5th-edition-ogl-by-roll20-companion)

ApplyDamage

## Макросы

### Макросы для игроков

[Init](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#init)

[saves](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#savesogl)

[ability-checks](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#abilitychecksogl)

[skills](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#skills-ogl)

[PCUtilsOGL](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#pcutilsogl)

[InfoOGL](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#infoogl)


### Макросы для мастеров

[grp-init]()

[grp-check]()

[grp-attack]()

[its-trap]()

[ogl-statblock]()

[ogl-books]()

[💀MONSTER-SETUP](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#monster-setup)

[💀NAMED-NPC-SETUP](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#named-npc-setup)

[💀PC Setup](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#pc-setup)

[TokenModUtilsOGL](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#tokenmodutils)

[​​​​​​​​​GameUtils1](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#gameutils1)

[GameUtils2](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#menu-utility-ogl-2)

[Apply Damage](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#applydamage)

[✍🏻Easy-Exp-Macros-OGL](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#easy-exp-macros-ogl)



[TokenUtilsOGL](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#tokenutilsogl)


***

## Как настроить использование зарядов для расходуемых предметов?

[Automatic Ammunition Tracking - Step by Step Tutorial ](https://wiki.roll20.net/OGL_5e_DnD:_How_to_setup_Ammunition_and_Resource_tracker)

Automatic Ammunition Track is a feature that requires the above Companion API Script. Once installed, follow these instructions to enable automatic ammunition tracking in your game:

This example sets up a Longbow with a quiver of Arrows to track.

    On the Settings (Gear Icon) tab of a character sheet, under GENERAL OPTIONS, make sure that the INVENTORY option is set to "Compendium Compatible" and not "Simple".
    While still under GENERAL OPTIONS, set the AMMO TRACKING feature to ON.
    Create manually or drag a missile weapon (ex. Longbow) from the Compendium to your sheet.
    Create manually or drag a missile type (Arrows) from the compendium to your sheet
    Expand the missile type (Arrows) by clicking on the "I" information icon that appears when hovering the mouse over the item.
    Select the USE AS RESOURCE checkbox. (ammunition items dragged from the Compendium will have this option automatically checked off)
    On the CORE tab, expand the missile weapon (Long Bow) in the ATTACKS & SPELLCASTING section by clicking on the gear icon that appears when hovering over the attack.
    In the AMMUNITION section put the exact name of the ammunition resource (Arrows). If you want to spend more than one piece of ammunition per shot you want to add the number of pieces after the name of the ammunition resource and a comma. (ex. Arrows,2 ) 


Now, any time the missile weapon (Longbow) is rolled, a piece of ammunition will automatically be spent and the chat will make note. Additionally after the first time the missile weapon is used the AMMUNITION section will update with the ID of the resource repeating section, this is normal and expected. 

## Как настроить автоматическое использование слотов заклинаний?

 Automatic Spell Slot Tracking

Automatic Spell Slot Tracking is a feature that requires the above Companion API Script. Once installed, follow these instructions to enable automatic spell slot tracking in your game:

    In the chat input area of the Sidebar, type !5estatus and press Enter, to check if spelltracking is set to 'on'.
    If not, type !spelltracking on and press Enter to activate this feature.
    Alternatively, you may type !spelltracking quiet and press Enter to activate this feature, while preventing spelltracking messages from being displayed in the chat. 


Once the Spell Slot Tracking has been activated, each time a spell is cast:

    The number of cast spells of the appropriate level is updated in the Spell tab of the character sheet (see Spell Levels & Spells Per Day).
    A message is output in the chat, displaying the spell level, the number of available spell slots and the number of used spell slots for this level.
    Spell slots decrement as spells are cast.
    Spells that are marked as a Ritual do not affect the tally of spell slots when cast. 


At any time, you can manually adjust this count directly in the Spell Page of the character sheet. 


***


## Описание используемых игроками функций и макросов

### PCUtilities

Используется служебный персонаж - **PCUtilsOGL** в abilities которого хранятся выполняемые макросы.

![PCUtilsOGL](https://raw.githubusercontent.com/palikhov/palant_roll20_setup/master/img/img-5e-ogl-PCUtils-abilities-01.png)

Создан специальный макрос [🛠PC Utilities](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#pcutilsogl), который и вызывает abilities с листа персонажа **PCUtilsOGL**

### Общие макросы

Мастер создает 4 макроса, к которым предоставляет доступ всем игрокам - [Initiative](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#init)(отображается как ⚔), [Skills](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#skills-ogl)(отображается как ✅), [Checks](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#abilitychecksogl) (отображается как ✔️) [Saves](https://github.com/palikhov/palant_roll20_setup/wiki/01.--Макросы#savesogl) (отображается как 🎲)
 
К сожалению, пока в листе 5e OGL Roll20 невозможно создать универсальный макрос для атак и заклинаний.

###  Шаблон для макросов атак

#### Индивидуальная атака

#### Меню атак



### Шаблон для макросов заклинаний

#### Шаблон для книги заклинаний



## Настройка магических предметов в листе персонажа

### Staff of Power и его заклинания




***


## MODS in inventory section

### General

### Item Type

### Armor

### ac

### Spells

spell

spell attack

spell dc


### Stats

strength

dexterity

constitution

intelligence

wisdom

charisma

### Saving Throws

saving throws

strength save

dexterity save

constitution save

intelligence save

wisdom save

charisma save

### Skills

acrobatics

animal handling

arcana

athletics

deception

history

insight

intimidation

investigation

medicine

nature

perception

performance

persuasion

religion

sleight of hand

stealth

survival

### Attacks

Secondary Damage Type

Secondary Damage

Damage Type

Damage

Range

Attacks #NOTE: space before and after (affects attack modifier)

Damage #NOTE: space before and after (affects damage modifier)





## USER CREATED MACROS

Resources
```
/w @{character_name} &{template:atk} {{desc=**@{selected|token_name}**
==
@{selected|alignment}  @{selected|race}  @{selected|background} 
==
HP: [[ @{selected|hp} ]] /  [[ @{selected|hp|max} ]]
AC: @{selected|ac} Speed: @{selected|speed} 
Pasive Perception:
Senses: 
Languages: 
===
*Resources*
@{selected|other_resource_name}: [[@{selected|other_resource}]] / [[@{selected|multiclass1_lvl}*5]] HP ||| *LR*
@{selected|class_resource_name}: [[@{selected|class_resource}]] / [[01]] ||| *SR*
@: [[@{selected|class_resource}]] / [[1]] ||| *SR*
Divine Sense: [[@{selected|class_resource}]] / [[1+@{selected|charisma_mod}]] ||| *LR*
Encumbrance
Total Weight: [[@{selected|weighttotal}]] / [[@{selected|strength}*15]] lb}} 

```

 Appearance

```
?{Whisper?|Yes,/w gm |No, }&{template:desc} {{desc=**@{selected|token_name}**
Возраст:  @{selected|age} 
==
**Рост:** @{selected|height} **Вес:** @{selected|weight} 
==
Возраст:  @{selected|age} 
==
**Глаза:** @{selected|eyes} **Кожа:** @{selected|skin} **Волосы:** @{selected|hair} 
==
**Общее описание внешности:** @{selected|character_appearance} }}
```

```
?{Whisper?|Yes,/w gm |No, }&{template:desc}{{desc=@{selected|allies_and_organizations} }}
```



###

https://app.roll20.net/forum/post/4142821/slug%7D

The complete text of the Greatsword Customization:
Whatever the description for your attack is [Divine Smite](~Weapon Options|repeating_attack_$1_attack)}} {{r1=[[1d20cs>@{atkcritrange} + [[@{atkattr_base}]] + @{atkmod} + [[@{atkprofflag}]][PROF]?{Bless|No, |Yes, + 1d4cs>5cf<0[Bless]}?{Sacred|No, |Yes, + [[@{charisma_mod}]][Sacred]}?{Great Weapon Master|No, 0|Yes, -5[Great Weapon Master]}]]}} {{r2=[[1d20cs>@{atkcritrange} + [[@{atkattr_base}]] + @{atkmod} + [[@{atkprofflag}]][PROF]?{Bless}?{Sacred}?{Great Weapon Master}]]}} {{dmg1=[[@{dmgbase}+[[@{dmgattr}]] +@{dmgmod}[MOD]?{Great Weapon Master}*-2]]

And the formula in Divine Smite's Damage field for autocalcing the number of Divine Smite Dice to roll:
2d8 + [[?{Spell Level|1}-1]]d8[Higher Level Spell Slot]?{Undead Target|No, |Yes, +1d8[Undead Target]}


The Save Effect field text is: ?{Firearm Special Attack|None, &#125;&#125; {{save=|Flurry - Head, **Success:**makes attacks normally **Failure:** makes attacks with disadvantage till end of their next turn&#125;&#125; {{saveattr=Constitution|Flurry – Arms, **Success:** retains hold of item **Failure:** drops one held item of my choice|Flurry – Torso, **Success:** Is unmoved **Failure:** pushed back up to 10-ft| Flurry – Legs, **Success:** Remains upright **Failure:** knocked prone}

The Ammunition field text is: {{desc=**Ki-points:** @{class_resource}/@{Sturmak|class_resource|max} ?{Magic Bonus|Normal Ammo [@{repeating_resource_$2_resource_left}],**Ammo** @{repeating_resource_$2_resource_left}|@{repeating_resource_$0_resource_left}|+1 Bullet [@{repeating_resource_$0_resource_right}],``**+1 Ammo:** @{repeating_resource_$0_resource_right}|@{repeating_resource_$0_resource_left}``}}}







```
EQUIPMENT
===========
Head:
===========
Eyes: 
===========
Amulet:
===========
Gloves: 
===========
Ring 1:
===========
Ring 2:
===========
Ring 3:
===========
Ring 4:
===========
Armor: 
===========
Boots:
===========
Belt: 
===========
Bonded weapons: Шпага Паука, Создатель теней
===========
Щит: 
===========
Плащ: 
===========
Перевязь грудная: 
==========
Ходит сильно хромая на левую ногу.
==========
```
# Документация по 5eOGL Roll20 Character Sheet
* Информация и описание листа персонажа на Roll20 wiki[Character Sheet Info on Roll20 Wiki](https://wiki.roll20.net/5th_Edition_OGL_by_Roll20)
* Детальное описание template на Roll20 wiki [Roll Templates which are used in 5eOGL Roll20 Character Sheet](https://wiki.roll20.net/D%26D_5e_OGL_Roll_Templates)
* Последний тред по обсуждению листа персонажа [Roll20 forum]()


[5e OGL] How to use macros or /fx inside a spell description?https://app.roll20.net/forum/post/3185162/slug%7D


***

# Дополнительные ссылки

* [Описание листа персонажа 5e OGL Roll20 (eng) wiki Roll20](https://wiki.roll20.net/5th_Edition_OGL_by_Roll20)
* [Описание шаблонов листа персонажа 5e OGL Roll20 (eng) wiki Roll20](https://wiki.roll20.net/D%26D_5e_OGL_Roll_Templates)
* [Руководство по макросам для игроков](https://github.com/palikhov/palant_roll20_setup/wiki/11.-Руководство-по-макросам-для-игроков)
* [Советы по организации рабочего пространства, кнопок у токенов и поля (bar) для кнопок макросов](https://github.com/palikhov/palant_roll20_setup/wiki/Советы-по-организации-рабочего-пространства,-кнопок-у-токенов-и-поля-(bar)-для-кнопок-макросов)
* [Полезные ссылки](https://github.com/palikhov/palant_roll20_setup/wiki/Полезные-ссылки)
