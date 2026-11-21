---
title: Лист персонажа AZAG
description: Fillable character sheet for AZAG (Dank Dungeons) — shared with the whole table, with a personal character selection for every player
author: MMescherin93
image: https://mmescherin93.github.io/azag-sheet/docs/store-hero.png
icon: https://mmescherin93.github.io/azag-sheet/icon.png
tags:
  - tool
manifest: https://mmescherin93.github.io/azag-sheet/manifest.json
learn-more: https://github.com/MMescherin93/azag-sheet
---

# Лист персонажа AZAG

**Fillable character sheet for *AZAG (Dank Dungeons)*. The interface is in Russian.**

![Скриншот листа](https://mmescherin93.github.io/azag-sheet/docs/store-hero.png)

## Что это

Бланк персонажа AZAG из PDF превращён в интерактивный лист: поля ввода лежат
поверх отрисованной страницы, поэтому лист выглядит как бумажный, но заполняется
прямо в Owlbear Rodeo.

На листе есть всё, что нужно за столом: имя персонажа и игрока, динамика группы,
Умение, Выносливость, Удача, магические и обычные предметы, навыки с рангами и
использованием, оружие, броня и щит, черты характера и кости брони.

## Как пользоваться

1. Откройте лист кнопкой в левом верхнем углу комнаты.
2. Заполняйте поля — всё сохраняется автоматически в общие метаданные комнаты.
3. **«＋ Новый»** — завести второго персонажа; выпадающий список переключает
   листы. У каждого участника свой выбранный персонаж: выбор хранится локально
   и не переключает лист у остальных, а правки листов видны всем.
4. Масштаб листа — кнопки `− / % / +` в шапке; `%` вписывает лист по размеру окна.

## Установка в Owlbear Rodeo

Settings → Extensions → **Add Extension** → вставить ссылку на манифест:

```
https://mmescherin93.github.io/azag-sheet/manifest.json
```

Затем **Install**. Обновляется так же: снять расширение и поставить заново по
той же ссылке.

## Ограничения

Общая метадата комнаты Owlbear Rodeo — до 16 КБ. В расширении действуют лимиты:
до 12 персонажей, 1200 символов в многострочном поле и 140 символов в строке.
Если лимит превышен, лист сохраняется локально, а в статусе появляется
предупреждение.

## Поддержка

Вопросы и предложения — в разделе Issues:
<https://github.com/MMescherin93/azag-sheet/issues>
