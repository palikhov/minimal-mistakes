---
title: "Руководство по Roll20 от Паланта"
permalink: /roll20-guide/players-ogl-guide/
excerpt: "Руководство игрока по листу персонажа 5e OGL"
output: true
toc: true
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

## Общее описание листа персонажа 5e OGL by Roll20

### Системо-независимая вкладка общих сведений -  Bio&Info

#### Возможности встроенного текстового редактора Roll20

#### Встраивание  кнопок

#### Примеры организации общих сведений о персонаже


### Personality

Personality Traits

Ideals

Flaws

Bonds

### Основные характеристики

Strength

Dexterity

Constitution

Intelligence

Wisdom

Charisma

### Основные производные характеристики

HP - Current, Max, Temporary обратите внимание что в максимуме хит-поинтов можно да и нужно прописать формулу определения хитов персонажа в двойных квадратных скобках ([Inline rolls]()), на токене при этом в разделе максимальных хитов будет отображаться уже итог вычислений.

AC - с учетом предметов, настроек, глобального модификатора

Initiative - 

Speed - заполняется в ручную и особо нигде дальше не используется.

### Счетчики ресурсов

Первый ряд - левый

Первый ряд - правый

Следующие ряды - repeating_resource_$x_resource_left/repeating_resource_$x_resource_right, где x изменяется от 0 до последнего (т.е., чтобы определить имя счетчика ресурсов - посчитайте какой он в общей массе счетчиков и  отнимите два).

### Инструменты и настраиваемые навыки

Proficiency bonus - Expertise / Proficient / Jack of All trades

Attribute - ассоцированая характеристика. Используется для расчета бонуса к проверке владения инструментами или других навыков. Возможен вариант запроса данных от игрока при каждой проверки (Query)

### Атаки


### Биография

Character appearance -

Allies & Organisations - 

Character Backstory - 

Additional Features & Traits - 

Treasure - 

### Заклинания

Spellcasting ability -

Spell Save DC - 

Spell attack -

Маркер подготовленности -

Маркер ритуала -

Innate spells - 




## Макросы и настройка 5e OGL by Roll20

### Рекомендуемые API-скрипты     

### Глобальные модификаторы

#### Глобальный модификатор спас-бросков

В этом разделе возможно создать модификаторы спас-бросков, которые действуют не постоянно, такие как:

* 1d4[Bless]
* -1d4[Bane]
* 3[Paladin's aura]
* 2[Arcane Durable]

По умолчанию предлагается 1d4[Bless].

#### Глобальный модификатор навыков

В этом разделе возможно создать модификаторы для проверок навыков, характеристик и инструментов, которые действуют не постоянно, такие как:

* 1d4[Guidance]
* -1d6[Synaptic Static]
* @{pb}[Skill Empowerment]

По умолчанию предлагается 1d4[Guidance].

#### Глобальный модификатор атак

В этом разделе возможно создать модификаторы для бросков атаки, которые действуют не постоянно, такие как:

* 1d4[Bless]
* -1d4[Bane]
* -5[Sharpshooter or GWM]

Как вариант, можно использовать следующий способ записи влияния Sharpshooter или ГВМ на броски атаки '''?{Sharpshooter|No, 0|Yes, -5}'''

По умолчанию предлагается 1d4[Bless].

#### Глобальный модификатор урона

В этом разделе возможно создать модификаторы для бросков атаки, которые действуют не постоянно, такие как:

* 1d4[Divine Favor]
* @{pb}[Hexblade's Curse]
* 10[Sharpshooter or GWM]
* 2[rage]
* @{intelligence_mod}[Bladesong + Song of Victory]
* 1d4[Elemental weapon]
* 1d6[Flame arrows]
и т.д.

По умолчанию предлагается 1d4[Divine Favor]


#### Глобальный модификатор класса защиты 

В этом разделе возможно создать модификаторы для класса защиты, которые действуют не постоянно или являются свойством класса. Например:

* 1[Defense]
* 2[Haste/Shield of Faith/Shield guardian]
* 1[Blessing]
* 2[Durable magic]
* 1[Warding Bond]
* -2[Slow]
* +3[Shield +1]

Достаточно удобно указывать в этом разделе и обычный щит, поскольку включить/выключить чек-бокс быстрее чем убрать или добавить к надетому снаряжению щит в инвентаре.

По умолчанию предлагается 1[Defense]


### Советы по заполнению атак персонажа

#### Дополнительные опции атаки

Divine / Eldritch Smite

Вариант 1 - с созданием на закладке Заклинаний заклинания Divine Smite




Вариант 2



Hex, Hunter's Mark

Divine Strike

Sneak attack

Maneuvers


####  Создание кнопок вызова дополнительных опций атаки

~~~
[Option z](~PC Sheet Template|repeating_attack_$x_attack) 
~~~

~~~
[Divine Smite](~PC Sheet Template|repeating_attack_$0_attack) **|**  [Divine Strike](~PC Sheet Template|repeating_attack_$1_attack) **|**  [Sneak attack](~PC Sheet Template|repeating_attack_$2_attack) **|**  
[Wounds](~PC Sheet Template|repeating_attack_$6_attack) 
~~~


#### Описание настройки некоторых видов оружия

Vicious sword

Vorpal sword

Wounding sword

Wound

Sword of Sharpness

Giant Slayer

Dragon Slayer

Mace of Disruption

Mace of Smithing

Oathbow

Javeling of lighting

Staff of Power (staff of striking)

Extra damage of Staff of Power


#### Использование запросов для формирования броска атаки и урона


В разделе Description (Описание) записать следующую часть формата

~~~}} {{r1=[[1d20cs>@{atkcritrange} + [[@{atkattr_base}]] @{atkmod} + [[@{atkprofflag}]][PROF]?{Bless|No, |Yes, + 1d4cs>5cf<0[Bless]}?{Sacred|No, |Yes, + [[@{charisma_mod}]][Sacred]}]]}} {{r2=[[1d20cs>@{atkcritrange} + [[@{atkattr_base}]] @{atkmod} + [[@{atkprofflag}]][PROF]?{Bless}?{Sacred}]]~~~


### Макросы

5etools - Make Token actions

Saves
~~~
@{selected|wtype}&{template:simple} @{selected|rtype}?{Save|Strength, +@{selected|strength_save_bonus}@{selected|pbd_safe}]]&#125;&#125; {{rname=Strength Save&#125;&#125 {{mod=@{selected|strength_save_bonus}&#125;&#125; {{r1=[[@{selected|d20}+@{selected|strength_save_bonus}@{selected|pbd_safe}]]&#125;&#125; |Dexterity, +@{selected|dexterity_save_bonus}@{selected|pbd_safe}]]&#125;&#125; {{rname=Dexterity Save&#125;&#125 {{mod=@{selected|dexterity_save_bonus}&#125;&#125; {{r1=[[@{selected|d20}+@{selected|dexterity_save_bonus}@{selected|pbd_safe}]]&#125;&#125; |Constitution, +@{selected|constitution_save_bonus}@{selected|pbd_safe}]]&#125;&#125; {{rname=Constitution Save&#125;&#125 {{mod=@{selected|constitution_save_bonus}&#125;&#125; {{r1=[[@{selected|d20}+@{selected|constitution_save_bonus}@{selected|pbd_safe}]]&#125;&#125; |Intelligence, +@{selected|intelligence_save_bonus}@{selected|pbd_safe}]]&#125;&#125; {{rname=Intelligence Save&#125;&#125 {{mod=@{selected|intelligence_save_bonus}&#125;&#125; {{r1=[[@{selected|d20}+@{selected|intelligence_save_bonus}@{selected|pbd_safe}]]&#125;&#125; |Wisdom, +@{selected|wisdom_save_bonus}@{selected|pbd_safe}]]&#125;&#125; {{rname=Wisdom Save&#125;&#125 {{mod=@{selected|wisdom_save_bonus}&#125;&#125; {{r1=[[@{selected|d20}+@{selected|wisdom_save_bonus}@{selected|pbd_safe}]]&#125;&#125; |Charisma, +@{selected|charisma_save_bonus}@{selected|pbd_safe}]]&#125;&#125; {{rname=Charisma Save&#125;&#125 {{mod=@{selected|charisma_save_bonus}&#125;&#125; {{r1=[[@{selected|d20}+@{selected|charisma_save_bonus}@{selected|pbd_safe}]]&#125;&#125;}@{selected|global_save_mod}@{selected|charname_output}
~~~



Skill-checks
~~~
@{selected|wtype}&{template:simple} @{selected|rtype}?{Ability|Acrobatics, +@{selected|acrobatics_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Acrobatics&#125;&#125; {{mod=@{selected|acrobatics_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|acrobatics_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Animal Handling, +@{selected|animal_handling_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Animal Handling&#125;&#125; {{mod=@{selected|animal_handling_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|animal_handling_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Arcana, +@{selected|arcana_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Arcana&#125;&#125; {{mod=@{selected|arcana_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|arcana_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Athletics, +@{selected|athletics_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Athletics&#125;&#125; {{mod=@{selected|athletics_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|athletics_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Deception, +@{selected|deception_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Deception&#125;&#125; {{mod=@{selected|deception_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|deception_bonus}@{selected|pbd_safe} ]]&#125;&#125; |History, +@{selected|history_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=History&#125;&#125; {{mod=@{selected|history_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|history_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Insight, +@{selected|insight_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Insight&#125;&#125; {{mod=@{selected|insight_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|insight_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Intimidation, +@{selected|intimidation_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Intimidation&#125;&#125; {{mod=@{selected|intimidation_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|intimidation_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Investigation, +@{selected|investigation_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Investigation&#125;&#125; {{mod=@{selected|investigation_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|investigation_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Medicine, +@{selected|medicine_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Medicine&#125;&#125; {{mod=@{selected|medicine_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|medicine_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Nature, +@{selected|nature_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Nature&#125;&#125; {{mod=@{selected|nature_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|nature_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Perception, +@{selected|perception_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Perception&#125;&#125; {{mod=@{selected|perception_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|perception_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Performance, +@{selected|performance_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Performance&#125;&#125; {{mod=@{selected|performance_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|performance_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Persuasion, +@{selected|persuasion_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Persuasion&#125;&#125; {{mod=@{selected|persuasion_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|persuasion_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Religion, +@{selected|religion_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Religion&#125;&#125; {{mod=@{selected|religion_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|religion_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Sleight of Hand, +@{selected|sleight_of_hand_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Sleight of Hand&#125;&#125; {{mod=@{selected|sleight_of_hand_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|sleight_of_hand_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Stealth, +@{selected|stealth_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Stealth&#125;&#125; {{mod=@{selected|stealth_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|stealth_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Survival, +@{selected|survival_bonus}@{selected|pbd_safe} ]]&#125;&#125; {{rname=Survival&#125;&#125; {{mod=@{selected|survival_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|survival_bonus}@{selected|pbd_safe} ]]&#125;&#125; |Strength, +@{selected|strength_mod}@{selected|jack_attr}[STR]]]&#125;&#125; {{rname=Strength&#125;&#125; {{mod=@{selected|strength_mod}@{selected|jack_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|strength_mod}@{selected|jack_attr}[STR]]]&#125;&#125; |Dexterity, +@{selected|dexterity_mod}@{selected|jack_attr}[DEX]]]&#125;&#125; {{rname=Dexterity&#125;&#125; {{mod=@{selected|dexterity_mod}@{selected|jack_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|dexterity_mod}@{selected|jack_attr}[DEX]]]&#125;&#125; |Constitution, +@{selected|constitution_mod}@{selected|jack_attr}[CON]]]&#125;&#125; {{rname=Constitution&#125;&#125; {{mod=@{selected|constitution_mod}@{selected|jack_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|constitution_mod}@{selected|jack_attr}[CON]]]&#125;&#125; |Intelligence, +@{selected|intelligence_mod}@{selected|jack_attr}[INT]]]&#125;&#125; {{rname=Intelligence&#125;&#125; {{mod=@{selected|intelligence_mod}@{selected|jack_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|intelligence_mod}@{selected|jack_attr}[INT]]]&#125;&#125; |Wisdom, +@{selected|wisdom_mod}@{selected|jack_attr}[WIS]]]&#125;&#125; {{rname=Wisdom&#125;&#125; {{mod=@{selected|wisdom_mod}@{selected|jack_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|wisdom_mod}@{selected|jack_attr}[WIS]]]&#125;&#125; |Charisma, +@{selected|charisma_mod}@{selected|jack_attr}[CHA]]]&#125;&#125; {{rname=Charisma&#125;&#125; {{mod=@{selected|charisma_mod}@{selected|jack_bonus}&#125;&#125; {{r1=[[ @{selected|d20} + @{selected|charisma_mod}@{selected|jack_attr}[CHA]]]&#125;&#125; } @{selected|global_skill_mod} @{selected|charname_output}
~~~

Initiative
~~~
%{selected|npc_init}
~~~




Attack 1
~~~
%{selected|repeating_attack_$0_attack}
~~~
Attack 2
~~~
%{selected|repeating_attack_$1_attack}
~~~
Attack 3
~~~
%{selected|repeating_attack_$2_attack}
~~~

Список трех основных атак

~~~
/w @{selected|character_name} &{template:npcaction} {{rname=Checks}} {{description=Select Attack
[@{selected|repeating_attack_$0_atkname}](~selected|repeating_attack_$0_attack)[@{selected|repeating_attack_$1_atkname}](~selected|repeating_attack_$1_attack) [@{selected|repeating_attack_$2_atkname}](~selected|repeating_attack_$2_attack)
}}
~~~


Tool 1
~~~
%{selected|repeating_tool_$0_tool}
~~~
Favorite Spells
~~~
/w @{character_name} &{template:npcaction} {{rname=Favorite Spells}} {{description=Favorite Spells are the first spells in each level of your spellbook.

[Cantrip](~selected|repeating_spell-cantrip_$0_spell)
[1st Level](~selected|repeating_spell-1_$0_spell)

[2nd Level](~selected|repeating_spell-2_$0_spell)

[3rd Level](~selected|repeating_spell-3_$0_spell)

[4th Level](~selected|repeating_spell-4_$0_spell)

[5th Level](~selected|repeating_spell-5_$0_spell)}}
~~~



Список заклинаний выбранного токена

Использован скрипт: Powercards

~~~
!power {{
--format|bigbad
--orowbg|#CEC7B6
--erowbg|#CEC7B6
--name|Spell List
--tokenid|@{selected|token_id}
--emote|@{selected|character_name}
--leftsub|Atk Bonus: @{selected|spell_attack_bonus}
--rightsub|Save DC: @{selected|spell_save_dc}
--spell_slots|@{selected|character_id}
--spell_list|@{selected|character_id}
}}
~~~



Если не используется никакой аналог Combat Tracker, то разумно использовать следующий макрос, чтобы обозначить окончание своего хода.

~~~
&{template:default} {{name=End Turn}}
~~~


Макрос атаки наемников, скелетов
~~~
{{rname=[ranged Attacks](~skeleton-bow-damage)}}{{description=[[{?{Number of attacks?}d20+4}>@{target|enemy|npc_ac}]] hits on ?{Number of attacks?} attacks vs. @{target|enemy|npc_name} (AC @{target|enemy|npc_ac})
~~~

Макрос урона по нескольким попаданиям
~~~
&{template:npcaction} {{name=Skeleton Bow}} {{rname=Ranged Damage}}{{description=Rolling damage for ?{Number of hits?} hits, ?{Crit damage dice?} of which were critical. [[?{Number of hits?}d8+?{Number of hits?}*7+?{Crit damage dice?}d8]] piercing damage total.}}
~~~

### Горячие клавиши

Открыть свойства токена - двойной клик левой кнопкой мыши

Открыть лист персонажа на вкладке Био - Shift+двойной клик левой кнопкой мыши

Открыть лист персонажа на листе персонажа - Alt+двойной клик левой кнопкой мыши





***


