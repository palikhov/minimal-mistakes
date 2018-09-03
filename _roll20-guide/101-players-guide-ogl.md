---
title: "Руководство по Roll20 от Паланта"
permalink: /roll20-guide/main/
excerpt: "Как удобно использовать Roll20 при игре в D&D 5e онлайн"
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

***
