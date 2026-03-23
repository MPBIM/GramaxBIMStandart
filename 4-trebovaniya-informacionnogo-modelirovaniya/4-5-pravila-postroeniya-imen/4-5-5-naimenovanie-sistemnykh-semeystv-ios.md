---
order: 5
title: 4.5.6 Наименование системных семейств ИОС
---

:::info 

Общие правила построения имен и требования отражены в [п.4.5.1 настоящего стандарта.](./4-5-1-obschie-pravila-naimenovaniya)

:::

Данные требования устанавливают наименование системных семейств ИОС, а именно типоразмеров следующих категорий Revit: **трубы, гибкие трубы, воздуховоды, гибкие воздуховоды, кабельные лотки, короба.**

## Наименование типоразмеров труб

Наименование типоразмеров труб должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Материал[/highlight]\_[highlight:mint-green]Функциональное назначение[/highlight]\_[highlight:light-pink]Тип\*[/highlight]\_[highlight:light-pink]ГОСТ или Производитель\*[/highlight]

**Примеры:**

-  ​[highlight:lemon-yellow]Полиэтилен (ПЭ100)[/highlight]\_[highlight:mint-green]Водогазопроводная[/highlight]\_[highlight:light-pink]Сварная SDR17\_ГОСТ 18599-2001[/highlight]

-  ​[highlight:lemon-yellow]Поливинилхлорид (PVC)[/highlight]\_[highlight:mint-green]Канализационная[/highlight]\_[highlight:light-pink]SN4[/highlight]

-  ​[highlight:lemon-yellow]ЧГН[/highlight]\_[highlight:mint-green]Канализационная[/highlight]\_[highlight:light-pink]Раструбная\_ГОСТ 6942-98[/highlight]

-  ​[highlight:lemon-yellow]СТЛоц[/highlight]\_[highlight:mint-green]Водогазопроводная[/highlight]\_[highlight:light-pink]ГОСТ3262-75[/highlight]

[highlight:lemon-yellow]Материал[/highlight] – постоянное поле для обозначения материала. Содержит сокращенное название (индекс) материала на кириллице ([п. 4.5.10 настоящего стандарта](./4-5-9-naimenovanie-materialov)).

[highlight:mint-green]Функциональное назначение[/highlight] – постоянное поле для обозначения выполняемой функции. Содержит произвольное текстовое значение на кириллице.

[highlight:light-pink]Тип[/highlight] – опциональное поле, которое вводится для обозначения типа. Содержит произвольное текстовое значение на кириллице или латинице.

[highlight:light-pink]ГОСТ или Производитель[/highlight] – опциональное поле, которое вводится для обозначения нормативного документа или производителя. Содержит произвольное текстовое значение на кириллице или латинице.

## Наименование типоразмеров воздуховодов

Наименование типоразмеров воздуховодов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Материал[/highlight]\_[highlight:mint-green]Функциональное назначение[/highlight]\_[highlight:light-pink]Огнестойкость\*[/highlight]\_[highlight:light-pink]Дым\*[/highlight]\_[highlight:lavender]ГОСТ или Производитель[/highlight]

**Примеры:**

-  [highlight:lemon-yellow]​СТЛоц[/highlight]\_[highlight:mint-green]Тройник[/highlight]\_[highlight:light-pink]С огнезащитой[/highlight]\_[highlight:light-pink]Дым[/highlight]\_[highlight:lavender]ГОСТ 14918-2020[/highlight]

-  ​[highlight:lemon-yellow]СТЛоц[/highlight]\_[highlight:mint-green]Врезка[/highlight]\_[highlight:lavender]ГОСТ 14918-2020[/highlight]

-  [highlight:lemon-yellow]​СТЛоц[/highlight]\_[highlight:mint-green]Полоса[/highlight]\_[highlight:lavender]DKC[/highlight]

:::info 

Описания вышеуказанных полей не отличается от полей наименования труб, если это не указано ниже.

:::

[highlight:light-pink]Огнестойкость[/highlight] – опциональное поле, которое вводится для воздуховодов с огнезащитой. В случае необходимости огнезащиты (например, для противодымной системы) поле принимает значение «С огнезащитой».

[highlight:light-pink]Дым[/highlight] – опциональное поле, которое вводится для воздуховодов противодымной системы. В случае необходимости поле принимает значение «Дым».

[highlight:lavender]ГОСТ или Производитель[/highlight] – постоянное поле для обозначения нормативного документа или производителя. Содержит произвольное текстовое значение на кириллице.

## Наименование типоразмеров гибких труб и гибких воздуховодов

Наименование типоразмеров гибких труб и воздуховодов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Материал[/highlight]\_[highlight:mint-green]Функциональное назначение[/highlight]\_[highlight:light-pink]Производитель или Тип\*[/highlight]

**Примеры:**

-  ​[highlight:lemon-yellow]Полипропилен (PP)[/highlight]\_[highlight:mint-green]Гофра для сифона[/highlight]

-  [highlight:lemon-yellow]​СТЛ[/highlight]\_[highlight:mint-green]Подводка для воды[/highlight]\_[highlight:light-pink]Гайка-гайка[/highlight]

-  ​[highlight:lemon-yellow]ПЛС[/highlight]\_[highlight:mint-green]Гибкий воздуховод[/highlight]\_[highlight:light-pink]Галвент[/highlight]

:::info 

Описания вышеуказанных полей не отличается от полей наименования труб, если это не указано ниже.

:::

[highlight:light-pink]Производитель или Тип[/highlight] – опциональное поле, которое вводится для обозначения производителя или типа. Содержит произвольное текстовое значение на кириллице или латинице.

## Наименование типоразмеров кабельных лотков

Наименование типоразмеров кабельных лотков должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:mint-green]Функциональное назначение[/highlight]\_[highlight:lavender]Марка[/highlight]\_[highlight:light-pink]Характеристика\*[/highlight]\_[highlight:ice-blue]Производитель[/highlight]\_[highlight:peach]Длина участка[/highlight]

**Примеры:**

-  ​[highlight:mint-green]Перфорированный лотоr[/highlight]\_[highlight:lavender]G5[/highlight]*\_*[highlight:light-pink]Стеклопластиковый[/highlight]\_[highlight:ice-blue]DKC[/highlight]\_[highlight:peach]2000[/highlight]

-  ​[highlight:mint-green]Проволочный лоток[/highlight]\_[highlight:lavender]PL[/highlight]\_[highlight:light-pink]Тяжелый[/highlight]\_[highlight:ice-blue]EKF[/highlight]\_[highlight:peach]3000[/highlight]

-  ​[highlight:mint-green]Лестничный лоток[/highlight]\_[highlight:lavender]L5[/highlight]\_[highlight:ice-blue]DKC[/highlight]\_[highlight:peach]3000[/highlight]

[highlight:mint-green]Функциональное назначение[/highlight] – постоянное поле для обозначения вида кабельного лотка и его изготовления. Содержит произвольное текстовое значение на кириллице.

[highlight:lavender]Марка[/highlight] – постоянное поле для обозначения марки по каталогу производителя. Содержит произвольное значение на кириллице или латинице.

[highlight:light-pink]Характеристика[/highlight] – опциональное поле, которое вводится для обозначения дополнительных характеристик кабельного лотка. Содержит произвольное значение на кириллице или латинице.

[highlight:ice-blue]Производитель[/highlight] – постоянное поле для обозначения производителя. Содержит произвольное значение на кириллице или латинице.

[highlight:peach]Длина участка[/highlight] – постоянное поле для обозначения длины поставляемого с завода изделия на стройку. Содержит цифровое обозначение длины.

## Наименование типоразмеров коробов

Наименование типоразмеров коробов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:mint-green]Функциональное назначение[/highlight]\_[highlight:lavender]Тип[/highlight]\_[highlight:ice-blue]Характеристика\*[/highlight]

**Примеры:**

-  [highlight:mint-green]Труба водогазопроводная[/highlight]\_[highlight:lavender]Стальная[/highlight]\_[highlight:ice-blue]Тяжелая[/highlight]

-  [highlight:mint-green]Гладкая труба[/highlight]\_[highlight:lavender]ПВХ[/highlight]\_[highlight:ice-blue]Легкая[/highlight]

-  [highlight:mint-green]Гладкая труба[/highlight]\_[highlight:lavender]ПНД[/highlight]

[highlight:mint-green]Функциональное назначение[/highlight] – постоянное поле для обозначения назначения короба. Содержит произвольное текстовое значение на кириллице.

[highlight:lavender]Тип[/highlight] – постоянное поле для обозначения типа. Содержит произвольное текстовое значение на кириллице.

[highlight:ice-blue]Характеристика[/highlight] – опциональное поле, которое вводится для обозначения дополнительных характеристик короба. Содержит произвольное текстовое значение на кириллице или латинице.