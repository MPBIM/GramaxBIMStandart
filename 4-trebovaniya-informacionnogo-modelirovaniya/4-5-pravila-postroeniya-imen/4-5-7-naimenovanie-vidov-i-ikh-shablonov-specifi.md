---
order: 7
title: 4.5.8 Наименование видов и их шаблонов, спецификаций, легенд
---

:::info 

Общие правила построения имен и требования отражены в [п.4.5.1 настоящего стандарта.](./4-5-1-obschie-pravila-naimenovaniya)

:::

## Наименование видов

Наименование видов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:light-pink]Задание\*[/highlight]\_[highlight:lemon-yellow]Раздел или Комплект[/highlight]\_[highlight:light-pink]Номер уровня\*[/highlight]\_[highlight:mint-green]Отметка\*[/highlight]\_[highlight:lavender]Описание[/highlight]

**Примеры:**

-  [highlight:light-pink]​З[/highlight]\_[highlight:lemon-yellow]АР-КР[/highlight]\_[highlight:light-pink]1[/highlight]\_[highlight:mint-green]\+5,500[/highlight]\_[highlight:lavender]План этажа[/highlight]

-  [highlight:light-pink]​З[/highlight]\_[highlight:lemon-yellow]КР-АР[/highlight]\_[highlight:light-pink]16\.1[/highlight]\_[highlight:mint-green]\+46,500[/highlight]\_[highlight:lavender]План технического этаж[/highlight]а

-  ​[highlight:lemon-yellow]АР-КР[/highlight]\_[highlight:light-pink]8[/highlight]\_[highlight:mint-green]\+24,500[/highlight]\_[highlight:lavender]Вертикальные конструкции[/highlight]

-  [highlight:lemon-yellow]​КР[/highlight]\_[highlight:light-pink]1[/highlight]\_[highlight:mint-green]\+0,000[/highlight]\_[highlight:lavender]Схема горизонтальных конструкций[/highlight]

-  [highlight:lemon-yellow]​АПР[/highlight]\_[highlight:light-pink]1[/highlight]\_[highlight:mint-green]\+0,000[/highlight]\_[highlight:lavender]План этажа[/highlight]

-  ​[highlight:lemon-yellow]АР[/highlight]\_[highlight:mint-green]Разрез 1-1[/highlight]

:::info 

Наименование видов, находящихся во вкладке **03\_ВРЕМЕННЫЕ** и **00_BIM** диспетчера проекта ([п. 4.4 настоящего стандарта](./../4-4-organizaciya-dispetchera-proekta)), не регламентируется.

:::

[highlight:light-pink]Задание[/highlight] – опциональное поле, которое вводится для видов обмена заданиями (получения и передачи). Содержит буквенное обозначение "З", которое обозначает функцию вида -- задание.

[highlight:lemon-yellow]Раздел или Комплект[/highlight] – постоянное поле для обозначения раздела или комплекта (если в модели разрабатывается несколько комплектов) разрабатываемой документации. Содержит код раздела/комплекта, который может содержать обозначение раздела/комплекта на кириллице и включать в себя цифровые обозначения комплектов.

:::info 

Также информационные модели содержат виды и спецификации раздела BIM, которые скрыты от для проектировщика организационной схемой диспетчера проекта.

:::

[highlight:light-pink]Номер уровня[/highlight] – опциональное поле, которое вводится для обозначения номера уровня горизонтальных видов проекта (планов этажа, потолка и т.д.). Содержит цифровое обозначение номера уровня.

[highlight:mint-green]Отметка уровня[/highlight] – опциональное поле, которое вводится для обозначения отметки уровня горизонтальных видов проекта (планов этажа, потолка и т.д.). Содержит цифровое обозначение отметки уровня в формате ±x,xxx (метры).

[highlight:lavender]Описание[/highlight] – постоянное поле для описания назначения данного вида или спецификации. Содержит произвольное текстовое значение на кириллице или латинице.

## Наименование шаблонов видов

Наименование шаблонов видов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:light-pink]Стадия\*[/highlight]\_[highlight:lemon-yellow]Раздел или Комплект[/highlight]\_[highlight:peach]Описание[/highlight]

:::info 

Описания полей наименования шаблонов видов не отличается от полей наименования видов, если это не указано ниже.

:::

[highlight:lemon-yellow]Стадия[/highlight] – опциональное поле, которое вводится для обозначение стадии проектирования. Содержит одно из нижеперечисленных значений на кириллице:

-  ​[highlight:lemon-yellow]ЭП[/highlight] – эскизный проект/концепция;

-  ​[highlight:lemon-yellow]АГР[/highlight] – архитектурно-градостроительные решения;

-  [highlight:lemon-yellow]​АПР[/highlight] – архитектурно-планировочные решения;

-  ​[highlight:lemon-yellow]ПД[/highlight] – проектная документация;

-  ​[highlight:lemon-yellow]РД[/highlight] – рабочая документация.

## Наименование спецификаций

Наименование спецификаций должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Раздел или комплект[/highlight]\_[highlight:peach]Описание[/highlight]

Для спецификаций заполнения параметров для передачи в экспертизу поле "Раздел или комплект принимает" значение "[highlight:lemon-yellow]МГЭ[/highlight]".

:::info 

Описания полей наименования спецификаций не отличается от полей наименования видов, если это не указано ниже.

:::

## Наименование легенд

Наименование легенд должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:light-pink]Раздел или Комплект\*[/highlight]\_[highlight:peach]Описание[/highlight]

:::info 

Описания полей наименования легенд не отличается от полей наименования видов, если это не указано ниже.

:::