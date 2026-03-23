---
order: 3
title: 4.5.4 Наименование системных семейств АР
---

:::info 

Общие правила построения имен и требования отражены в [п.4.5.1 настоящего стандарта.](./4-5-1-obschie-pravila-naimenovaniya)

:::

Данные требования устанавливают наименование системных семейств АР, а именно типоразмеров следующих категорий Revit: **стены, перекрытия, потолки, крыши, фундаменты несущей конструкции.**

Наименование таких элементов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Код функции[/highlight]\_[highlight:mint-green]Расположение[/highlight]\_[highlight:lavender]Материалы и толщины слоев[/highlight]\_[highlight:ice-blue]Общая толщина[/highlight]\_[highlight:light-pink]Описание\*[/highlight]

**Примеры:**

-  ​**Стены:**

   -  [highlight:lemon-yellow]​01[/highlight]\_[highlight:mint-green]ВН[/highlight]\_[highlight:lavender]МЖБ200[/highlight]\_[highlight:ice-blue]200[/highlight]

   -  ​[highlight:lemon-yellow]04[/highlight]\_[highlight:mint-green]НА[/highlight]\_[highlight:lavender]МИН150[/highlight]\_[highlight:ice-blue]150[/highlight]

   -  ​[highlight:lemon-yellow]07[/highlight]\_[highlight:mint-green]НА[/highlight]\_[highlight:lavender]СТК50[/highlight]\_[highlight:ice-blue]50[/highlight]\_[highlight:light-pink]Витраж с импостом 50х100[/highlight]

-  ​**Перекрытия:**

   -  ​[highlight:lemon-yellow]05[/highlight]\_[highlight:mint-green]ВН[/highlight]\_[highlight:lavender]ЦПС90-ПЛТкрм10[/highlight]\_[highlight:ice-blue]100[/highlight]\_[highlight:light-pink]Полы МОП[/highlight]

-  ​**Потолки:**

   -  ​[highlight:lemon-yellow]05[/highlight]\_[highlight:mint-green]ВН[/highlight]\_[highlight:lavender]ПСПП16-АРМС16[/highlight]\_[highlight:ice-blue]32[/highlight]\_[highlight:light-pink]Армстронг 600х600 БКТ[/highlight]

-  ​**Крыши:**

   -  [highlight:lemon-yellow]​04[/highlight]\_[highlight:mint-green]НА[/highlight]\_[highlight:lavender]ППС200-ЦПС50-ГРВ250[/highlight]\_[highlight:ice-blue]490[/highlight]

-  ​**Фундаменты несущей конструкции:**

   -  [highlight:lemon-yellow]​01[/highlight]\_[highlight:mint-green]НА[/highlight]\_[highlight:lavender]МЖБ700[/highlight]\_[highlight:ice-blue]700[/highlight]

[highlight:lemon-yellow]Код функции[/highlight] – постоянное поле для обозначения функционального типа типоразмера. Содержит один из нижеперечисленных цифровых кодов, соответствующих функциональному типу:

{% table header="row" %}

---

*  {% colwidth=[257] %}

   Стены

*  {% colwidth=[247] %}

   Перекрытия

*  {% colwidth=[223] %}

   Потолки

*  {% colwidth=[251] %}

   Крыши

*  {% colwidth=[239] %}

   Фундаменты

---

*  {% colwidth=[257] %}

   [highlight:lemon-yellow]01[/highlight] – несущие стены;

*  {% colwidth=[247] %}

   [highlight:lemon-yellow]01[/highlight] – несущие перекрытия;

*  {% colwidth=[223] %}

   

*  {% colwidth=[251] %}

   

*  {% colwidth=[239] %}

   [highlight:lemon-yellow]01[/highlight] – несущие фундаменты;

---

*  {% colwidth=[257] %}

   [highlight:lemon-yellow]02[/highlight] – кладочные стены;

*  {% colwidth=[247] %}

   

*  {% colwidth=[223] %}

   

*  {% colwidth=[251] %}

   

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[257] %}

   [highlight:lemon-yellow]03[/highlight] – каркасные стены;

*  {% colwidth=[247] %}

   

*  {% colwidth=[223] %}

   

*  {% colwidth=[251] %}

   

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[257] %}

   [highlight:lemon-yellow]04[/highlight] – утеплители и изоляция;

*  {% colwidth=[247] %}

   [highlight:lemon-yellow]04[/highlight] – утеплители и изоляция;

*  {% colwidth=[223] %}

   

*  {% colwidth=[251] %}

   [highlight:lemon-yellow]04[/highlight] – утеплители и изоляция;

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[257] %}

   [highlight:lemon-yellow]05[/highlight] – отделка стен;

*  {% colwidth=[247] %}

   [highlight:lemon-yellow]05[/highlight] – отделка пола;

*  {% colwidth=[223] %}

   [highlight:lemon-yellow]05[/highlight] – отделка потолка;

*  {% colwidth=[251] %}

   

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[257] %}

   [highlight:lemon-yellow]06[/highlight] – фасады;

*  {% colwidth=[247] %}

   

*  {% colwidth=[223] %}

   

*  {% colwidth=[251] %}

   

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[257] %}

   [highlight:lemon-yellow]07[/highlight] – витражи.

*  {% colwidth=[247] %}

   

*  {% colwidth=[223] %}

   

*  {% colwidth=[251] %}

   

*  {% colwidth=[239] %}

   

{% /table %}

[highlight:mint-green]Расположение[/highlight] – постоянное поле для обозначения расположения относительно объема здания. Содержит одно из нижеперечисленных значений на кириллице:

-  ​[highlight:mint-green]НА[/highlight] – наружные элементы;

-  [highlight:lavender]​[/highlight][highlight:mint-green]ВН[/highlight] – внутренние элементы.

[highlight:lavender]Материалы и толщины слоев[/highlight] – постоянное поле для перечисления материалов и толщин входящих слоев. Содержит сокращенные названия (индексы) материалов на кириллице ([п. 4.5.10 настоящего стандарта](./4-5-9-naimenovanie-materialov)) и их толщины в виде цифрового обозначения. Слои указываются в порядке от наружных/верхних к внутренним/нижним и разделяются между собой дефисом "–".

[highlight:ice-blue]Общая толщина[/highlight] – постоянное поле для обозначения общей толщины (всех слоев) системного семейства. Содержит цифровое обозначение общей толщины.

[highlight:light-pink]Описание[/highlight] – опциональное поле, которое вводится для описания условий или места применения системного семейства. Содержит произвольное текстовое значение на кириллице или латинице.