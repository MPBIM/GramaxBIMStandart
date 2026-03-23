---
order: 4
title: 4.5.5 Наименование системных семейств КР
---

:::info 

Общие правила построения имен и требования отражены в [п.4.5.1 настоящего стандарта.](./4-5-1-obschie-pravila-naimenovaniya)

:::

Данные требования устанавливают наименование системных семейств КР, а именно типоразмеров следующих категорий Revit: **стены, перекрытия, фундаменты несущей конструкции, крыши**.

### Однослойные типоразмеры

Наименование однослойных (имеющих в структуре один материал) типоразмеров элементов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Код функции[/highlight]\_[highlight:mint-green]Индекс материала[/highlight]\_[highlight:light-pink]Характеристика материала\*[/highlight]\_[highlight:lavender]Общая толщина[/highlight]\_[highlight:light-pink]Описание\*[/highlight]

**Примеры:**

-  ​**Стены:**

   -  ​[highlight:lemon-yellow]01[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]B20 W4 F200[/highlight]\_[highlight:lavender]200[/highlight]

   -  [highlight:lemon-yellow]​02[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]B25 W6 F150[/highlight]\_[highlight:lavender]250[/highlight]\_[highlight:light-pink]Пилоны[/highlight]

   -  ​[highlight:lemon-yellow]03[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]B30 W8 F200[/highlight]\_[highlight:lavender]300[/highlight]\_[highlight:light-pink]Подпорные стены[/highlight]

   -  [highlight:lemon-yellow]​04[/highlight]\_[highlight:mint-green]МИН[/highlight]\_100

-  ​**Перекрытия:**

   -  [highlight:lemon-yellow]​01[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]B20 W4 F200[/highlight]\_[highlight:lavender]200[/highlight]

   -  ​[highlight:lemon-yellow]02[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]B25 W6 F150[/highlight]\_[highlight:lavender]250[/highlight]\_[highlight:light-pink]Лестничные площадки[/highlight]

   -  ​[highlight:lemon-yellow]03[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]B30 W8 F200[/highlight]\_[highlight:lavender]300[/highlight]\_[highlight:light-pink]Капители[/highlight]

   -  ​[highlight:lemon-yellow]04[/highlight]\_[highlight:mint-green]МИН[/highlight]\_[highlight:lavender]100[/highlight]

-  ​**Фундаменты несущей конструкции:**

   -  ​[highlight:lemon-yellow]01[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]В35 W8 F150[/highlight]\_[highlight:lavender]300[/highlight]

   -  ​[highlight:lemon-yellow]02[/highlight]\_[highlight:mint-green]МЖБ[/highlight]\_[highlight:light-pink]B35 W6 F150[/highlight]\_[highlight:lavender]200[/highlight]\_[highlight:light-pink]Ростверки[/highlight]

-  ​**Крыши:**

   -  [highlight:lemon-yellow]​01[/highlight]\_[highlight:mint-green]БТН[/highlight]\_[highlight:light-pink]B10[/highlight]\_[highlight:lavender]100[/highlight]\_[highlight:light-pink]Бетонная подготовка[/highlight]

[highlight:lemon-yellow]Код функции[/highlight] – постоянное поле для обозначения функционального типа типоразмера. Содержит один из нижеперечисленных цифровых кодов, соответствующих функциональному типу:

{% table header="row" %}

---

*  {% colwidth=[238] %}

   Стены

*  {% colwidth=[283] %}

   Перекрытия

*  {% colwidth=[255] %}

   Фундаменты

*  {% colwidth=[239] %}

   Крыши

---

*  {% colwidth=[238] %}

   [highlight:lemon-yellow]01[/highlight] – Несущие стены

*  {% colwidth=[283] %}

   [highlight:lemon-yellow]01[/highlight] – Несущие перекрытия

*  {% colwidth=[255] %}

   [highlight:lemon-yellow]01[/highlight] – Фундаментные плиты

*  {% colwidth=[239] %}

   [highlight:lemon-yellow]01[/highlight] - Подготовка

---

*  {% colwidth=[238] %}

   [highlight:lemon-yellow]02[/highlight] – Пилоны

*  {% colwidth=[283] %}

   [highlight:lemon-yellow]02[/highlight] – Лестничные площадки

*  {% colwidth=[255] %}

   [highlight:lemon-yellow]02[/highlight] – Ростверки

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[238] %}

   [highlight:lemon-yellow]03[/highlight] – Подпорные стены

*  {% colwidth=[283] %}

   [highlight:lemon-yellow]03[/highlight] – Капители

*  {% colwidth=[255] %}

   

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[238] %}

   [highlight:lemon-yellow]04[/highlight] – Изоляция

*  {% colwidth=[283] %}

   [highlight:lemon-yellow]04[/highlight] – Изоляция

*  {% colwidth=[255] %}

   

*  {% colwidth=[239] %}

   

---

*  {% colwidth=[238] %}

   

*  {% colwidth=[283] %}

   [highlight:lemon-yellow]05[/highlight] – Рампы/Пандусы

*  {% colwidth=[255] %}

   

*  {% colwidth=[239] %}

   

{% /table %}

[highlight:mint-green]Индекс материала[/highlight] – постоянное поле для указания материала. Содержит сокращенное название (индекс) материала на кириллице (согласно [п. 4.5.10 настоящего стандарта](./4-5-9-naimenovanie-materialov)).

[highlight:light-pink]Характеристика материала[/highlight] – опциональное поле, которое вводится для обозначения характеристик материала. Содержит произвольное текстовое значение на кириллице или латинице.

[highlight:lavender]Общая толщина[/highlight] – постоянное поле для обозначения общей толщины или ширины системного семейства. Содержит цифровое обозначение общей толщины или ширины.

[highlight:light-pink]Описание[/highlight] – опциональное поле, которое вводится для описания условий или места применения системного семейства. Содержит произвольное текстовое значение на кириллице или латинице.

### Многослойные типоразмеры

Наименование многослойных (имеющих в структуре несколько материалов) типоразмеров элементов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Код функции[/highlight]\_[highlight:mint-green]Материалы и толщины слоев[/highlight]\_[highlight:lavender]Общая толщина[/highlight]\_[highlight:light-pink]Описание\*[/highlight]

**Примеры:**

-  ​**Стены:**

   -  [highlight:lemon-yellow]​04[/highlight]\_[highlight:mint-green]ГИрл8-ГИнп-ПРМ[/highlight]\_[highlight:lavender]8[/highlight]

-  ​**Крыши:**

   -  ​[highlight:lemon-yellow]01[/highlight]\_[highlight:mint-green]ЦПС50-ГИнп-ПРМ-БТН100[/highlight]\_[highlight:lavender]150[/highlight]

:::info 

Описания вышеуказанных полей не отличается от полей наименования однослойных типоразмеров, если это не указано ниже.

:::

[highlight:mint-green]Материалы и толщины слоев[/highlight] – постоянное поле для перечисления материалов и толщин входящих слоев. Содержит сокращенные названия (индексы) материалов на кириллице ([п. 4.5.10 настоящего стандарта](./4-5-9-naimenovanie-materialov)) и их толщины в виде цифрового обозначения. Слои указываются в порядке от наружных/верхних к внутренним/нижним и разделяются между собой дефисом "–".