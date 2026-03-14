---
order: 1
title: 4.5.2 Наименование файлов модели
---

:::info 

Общие правила построения имен и требования отражены в п.4.5.1 настоящего стандарта.

:::

## Наименование основных файлов модели

Наименование основных файлов модели (п. 2.2 настоящего стандарта) должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Компания[/highlight]\_[highlight:mint-green]Тип[/highlight]\_[highlight:lavender]Код проекта[/highlight]\_[highlight:light-pink]Зона\*[/highlight]\_[highlight:light-pink]Корпус\*[/highlight]\_[highlight:light-pink]Секция или Блок\*[/highlight]\_[highlight:ice-blue]Раздел[/highlight]\_[highlight:light-pink]Стадия\*[/highlight]\_[highlight:light-pink]Дополнение\*[/highlight]\_[highlight:peach]ПО[/highlight]

**Примеры:**

-  [highlight:lemon-yellow]​МП[/highlight]\_[highlight:mint-green]МКД[/highlight]\_[highlight:lavender]ГОВ[/highlight]\_[highlight:light-pink]ЗУ03[/highlight]\_[highlight:light-pink]К01[/highlight]\_[highlight:light-pink]С1[/highlight]\_[highlight:ice-blue]АР1[/highlight]\_[highlight:light-pink]2 вариант[/highlight]\_[highlight:peach]R23[/highlight]

-  ​[highlight:lemon-yellow]МП[/highlight]\_[highlight:mint-green]МКД[/highlight]\_[highlight:lavender]ВЕР12Б[/highlight]\_[highlight:light-pink]К02[/highlight]\_[highlight:light-pink]С1-2[/highlight]\_[highlight:ice-blue]КЖ1.2[/highlight]\_[highlight:peach]R23[/highlight]

-  [highlight:lemon-yellow]МП[/highlight]\_[highlight:mint-green]МКД[/highlight]\_[highlight:lavender]9МАЯ24[/highlight]\_[highlight:ice-blue]КЖ07-09,12[/highlight]\_[highlight:peach]R23[/highlight]

-  [highlight:lemon-yellow]МП[/highlight]\_[highlight:mint-green]ШКОЛ[/highlight]\_[highlight:lavender]КОМ[/highlight]\_[highlight:light-pink]Б1-2[/highlight]\_[highlight:ice-blue]КЖ1.1.1-3[/highlight]\_[highlight:peach]R23[/highlight]

-  [highlight:lemon-yellow]​МП[/highlight]\_[highlight:mint-green]АВТО[/highlight]\_[highlight:lavender]ГОРБОР[/highlight]\_[highlight:ice-blue]АР[/highlight]\_[highlight:light-pink]Автостоянка[/highlight]\_[highlight:peach]R23[/highlight]

-  ​[highlight:lemon-yellow]МП[/highlight]\_[highlight:mint-green]СПОРТ[/highlight]\_[highlight:lavender]МНЕВ[/highlight]\_[highlight:ice-blue]АР[/highlight]\_[highlight:light-pink]Бассейн[/highlight]\_[highlight:peach]R23[/highlight]

-  ​[highlight:lemon-yellow]МП[/highlight]\_[highlight:mint-green]МКД[/highlight]\_[highlight:lavender]БСК[/highlight]\_[highlight:ice-blue]АР[/highlight]\_[highlight:light-pink]ПД[/highlight]\_[highlight:peach]R23[/highlight]

-  [highlight:lemon-yellow]​МП[/highlight]\_[highlight:mint-green]МКД[/highlight]\_[highlight:lavender]3ПАВ6[/highlight]\_[highlight:ice-blue]ЭОМ[/highlight]\_[highlight:peach]R23[/highlight]

-  ​[highlight:lemon-yellow]МП[/highlight]\_[highlight:mint-green]МЕД[/highlight]\_[highlight:lavender]ПРК4[/highlight]\_[highlight:ice-blue]КР[/highlight]\_[highlight:peach]R23[/highlight]

[highlight:lemon-yellow]Компания[/highlight] – постоянное поле для обозначения компании, разрабатывающей ЦИМ. Содержит код или аббревиатуру на кириллице или латинице. Для разработанных в компании АО "Моспроект" информационных моделей принят код  [highlight:lemon-yellow]«МП»[/highlight].

[highlight:mint-green]Тип[/highlight] – постоянное поле для обозначения типа разрабатываемого объекта. Содержит один из нижеперечисленных кодов на кириллице:

{% table header="row" %}

---

*  {% colwidth=[193] %}

   Группа

*  {% colwidth=[574] %}

   Код типа объекта

---

*  {% colwidth=[193] %}

   Здания, предназначенные для постоянного проживания и временного пребывания людей

*  {% colwidth=[574] %}

   -  ​[highlight:mint-green]МКД[/highlight] – многоквартирные жилые дома, включая общежития квартирного типа;

   -  [highlight:mint-green]​ОКД[/highlight] – одноквартирные жилые дома, включая блокированные;

   -  ​[highlight:mint-green]ДЕТ[/highlight] – здания детских организаций (лагеря, санатории для детей и т.п.);

   -  ​[highlight:mint-green]САН[/highlight] – спальные корпуса санаториев и домов отдыха;

   -  ​[highlight:mint-green]МЕДС[/highlight] – медицинские стационары (здания медицинских организаций для круглосуточной помощи);

   -  [highlight:mint-green]​ДОШК[/highlight] – здания дошкольных образовательных учреждений;

   -  [highlight:mint-green]​ИНТЕРН[/highlight] – спальные корпуса образовательных организаций с интернатом;

   -  ​[highlight:mint-green]ОБЩЕЖ[/highlight] – общежития (кроме квартирного типа);

   -  ​[highlight:mint-green]СПЕЦДОМ[/highlight] – специализированные дома престарелых и инвалидов;

   -  ​[highlight:mint-green]ГОСТ[/highlight] – гостиницы;

   -  ​[highlight:mint-green]КЕМП[/highlight] – кемпинги;

---

*  {% colwidth=[193] %}

   Здания зрелищных и культурно-просветительных учреждений

*  {% colwidth=[574] %}

   -  ​[highlight:mint-green]ЦИРК[/highlight] – цирк;

   -  ​[highlight:mint-green]КЛУБ[/highlight] – клубы;

   -  ​[highlight:mint-green]ВЫСТ[/highlight] – выставка;

   -  ​[highlight:mint-green]БИБ[/highlight] – библиотека;

   -  ​[highlight:mint-green]КИНО[/highlight] – кинотеатры;

   -  ​[highlight:mint-green]КОНЦ[/highlight] – концертные залы;

   -  ​[highlight:mint-green]ТАНЦ[/highlight] – танцевальные залы;

   -  [highlight:mint-green]​СПОРТ[/highlight] – спортивные сооружения с трибунами;

   -  ​[highlight:mint-green]ДРУГ[/highlight] – другие учреждения с посадочными местами в закрытых помещениях;

   -  ​[highlight:mint-green]ДРУГЗАК[/highlight] – другие подобные учреждения в закрытых помещениях;

   -  ​[highlight:mint-green]МУЗН[/highlight] – музей на открытом воздухе;

   -  ​[highlight:mint-green]ТЕАТН[/highlight] – театр на открытом воздухе;

   -  ​[highlight:mint-green]ТЕАТ[/highlight] – театры;

   -  [highlight:mint-green]​МУЗ[/highlight] – музей;

---

*  {% colwidth=[193] %}

   Здания организаций по обслуживанию населения

*  {% colwidth=[574] %}

   -  [highlight:mint-green]​РЕЛ[/highlight] – объекты религиозного назначения;

   -  [highlight:mint-green]​МЕД[/highlight] – медицинские организации (кроме стационаров);

   -  [highlight:mint-green]​БЫТ[/highlight] – помещения для посетителей организаций бытового и коммунального обслуживания без расчетного числа посадочных мест;

   -  ​[highlight:mint-green]СПОРТ[/highlight] – физкультурно-оздоровительные комплексы, спортивные учреждения без трибун, бытовые помещения, бани;

   -  [highlight:mint-green]​ОБПИТ[/highlight] – здания организаций общественного питания;

   -  ​[highlight:mint-green]ТОРГ[/highlight] – здания организации торговли;

   -  ​[highlight:mint-green]ВОКЗ[/highlight] – вокзал;

---

*  {% colwidth=[193] %}

   Здания образовательных, научных, проектных организаций и органов управления

*  {% colwidth=[574] %}

   -  [highlight:mint-green]​ЗАГС[/highlight] - органы записи актов гражданского состояния;

   -  ​[highlight:mint-green]НАУКА[/highlight] – научные организации;

   -  ​[highlight:mint-green]ПРОЕКТ[/highlight] – проектные организации;

   -  ​[highlight:mint-green]ШКОЛ[/highlight] – общеобразовательные школы;

   -  ​[highlight:mint-green]ИНФОР[/highlight] – информационные организации;

   -  ​[highlight:mint-green]ДОПДЕТ[/highlight] – организации дополнительного образования детей;

   -  ​[highlight:mint-green]ВУЗ[/highlight] – вузы, организации дополнительного профессионального образования;

   -  ​[highlight:mint-green]ОРУП[/highlight] – органы управления (министерства, департаменты, администрации и т.п.);

   -  ​[highlight:mint-green]ОФИС[/highlight] – офисы (корпоративные, представительства, call-центры);

   -  ​[highlight:mint-green]ПРОФ[/highlight] – профессиональные учебные заведения;

   -  ​[highlight:mint-green]ПОЖД[/highlight] – пожарное дело;

   -  ​[highlight:mint-green]БАНК[/highlight] – банк;

---

*  {% colwidth=[193] %}

   Здания производственного или складского назначения

*  {% colwidth=[574] %}

   -  [highlight:mint-green]ПРОД[/highlight] – производственные здания, лаборатории, мастерские, крематории;

   -  ​[highlight:mint-green]СКЛАД[/highlight] – склады, книгохранилища, архивы;

   -  ​[highlight:mint-green]СЕЛЬХ[/highlight] – сельскохозяйственные здания;

   -  ​[highlight:mint-green]КРЕМТ[/highlight] – крематорий;

   -  ​[highlight:mint-green]АВТО[/highlight] – автостоянки, гаражи, паркинги;

---

*  {% colwidth=[193] %}

   Прочее

*  {% colwidth=[574] %}

   -  [highlight:mint-green]​КЛАДБ[/highlight] – кладбище;

{% /table %}

[highlight:lavender]Код проекта[/highlight] – постоянное поле для обозначения уникального кода объекта для его идентификации среди других объектов. Содержит код на кириллице.

[highlight:light-pink]Зона[/highlight] – опциональное поле, которое вводится для обозначения зоны или земельного участка ЦИМ, если объект капитального строительства подразделяется на несколько зон. Содержит символы "ЗУ" на кириллице и номер зоны в формате "00". Если объекта капитального строительства представлен одной зоной поле не используется.

[highlight:light-pink]Корпус[/highlight] – опциональное поле, которое вводится для обозначения корпуса ЦИМ в соответствии с планом реализации BIM-проекта (BEP), если модель объекта капитального строительства состоит из нескольких отдельно стоящих зданий или обособленных частей. Содержит символ "К" на кириллице и номер корпуса в формате "00". Если объект капитального строительства представлен одним корпусом поле не используется.

[highlight:light-pink]Секция[/highlight] – опциональное поле, которое вводится для обозначения секции ЦИМ, если модель корпуса объекта капитального строительства подразделяется на несколько секций. Содержит символ "C" (для секции) или "Б" (для блока) на кириллице и номер(а) секции или блока. Если ЦИМ содержит несколько секций или блоков они указываются через "–" (дефис). Если корпус объекта капитального строительства представлен одной секцией поле не используется.

[highlight:ice-blue]Раздел[/highlight] – постоянное поле для обозначения раздела проектирования. Содержит одно из нижеперечисленных значений на кириллице ((!) если модель не делится на подразделы):

{% table header="row" %}

---

*  {% colwidth=[160] %}

   Раздел проекта

*  {% colwidth=[610] %}

   Описание

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]АР[/highlight]

*  {% colwidth=[610] %}

   Архитектурные решения

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]АИ[/highlight]

*  {% colwidth=[610] %}

   Архитектурные интерьеры

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]КР (!)[/highlight]

*  {% colwidth=[610] %}

   Конструктивные решения

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]КЖ[/highlight]

*  {% colwidth=[610] %}

   Конструктивные решения - Конструкции железобетонные

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]КМ[/highlight]

*  {% colwidth=[610] %}

   Конструктивные решения - Конструкции металлические

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]КД[/highlight]

*  {% colwidth=[610] %}

   Конструктивные решения - Конструкции деревянные

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]КК[/highlight]

*  {% colwidth=[610] %}

   Конструкции каменные и армокаменные

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]АРМ[/highlight]

*  {% colwidth=[610] %}

   Армирование

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ЭОМ (!)[/highlight]

*  {% colwidth=[610] %}

   Электрооборудование и освещение

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ЭС[/highlight]

*  {% colwidth=[610] %}

   Электроснабжение

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ЭО[/highlight]

*  {% colwidth=[610] %}

   Электрическое освещение (внутреннее)

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ЭМ[/highlight]

*  {% colwidth=[610] %}

   Силовое электрооборудование

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ВК (!)[/highlight]

*  {% colwidth=[610] %}

   Водоснабжение и водоотведение (внутренние)

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ВО[/highlight]

*  {% colwidth=[610] %}

   Водоотведение

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ВВ[/highlight]

*  {% colwidth=[610] %}

   Водоснабжение внутреннее

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ПТ[/highlight]

*  {% colwidth=[610] %}

   Система пожаротушения

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ОВиК (!)[/highlight]

*  {% colwidth=[610] %}

   Отопление, вентиляция и кондиционирование

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ОВ1[/highlight]

*  {% colwidth=[610] %}

   Отопление

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ОВ2[/highlight]

*  {% colwidth=[610] %}

   Вентиляция, кондиционирование и холодоснабжение

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ОВ3[/highlight]

*  {% colwidth=[610] %}

   Противодымная вентиляция

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ТМ[/highlight]

*  {% colwidth=[610] %}

   Тепломеханическая часть (ИТП)

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]СС (!)[/highlight]

*  {% colwidth=[610] %}

   Сети связи

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]СС[/highlight]

*  {% colwidth=[610] %}

   Слаботочные сети

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]АВ[/highlight]

*  {% colwidth=[610] %}

   Автоматика и диспетчеризация

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]АИС[/highlight]

*  {% colwidth=[610] %}

   Автоматизация инженерных систем

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ГВС[/highlight]

*  {% colwidth=[610] %}

   Газоснабжение (внутреннее)

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ТХ[/highlight]

*  {% colwidth=[610] %}

   Технологические решения

---

*  {% colwidth=[160] %}

   [highlight:ice-blue]ГП[/highlight]

*  {% colwidth=[610] %}

   Генеральный план

{% /table %}

:::info 

Если ЦИМ содержит несколько разделов они указываются через символ "–" (дефис).

:::

[highlight:light-pink]Стадия[/highlight] – опциональное поле, которое вводится для обозначения стадии проектирования. Содержит одно из нижеперечисленных значений на кириллице:

-  ​[highlight:light-pink]ЭП[/highlight] – эскизный проект/концепция;

-  [highlight:light-pink]​АГР[/highlight] – архитектурно-градостроительные решения;

-  [highlight:light-pink]​АПР[/highlight] – архитектурно-планировочные решения;

-  [highlight:light-pink]​ПД[/highlight] – проектная документация;

-  [highlight:light-pink]​РД[/highlight] – рабочая документация.

:::info 

Обозначение стадии вносится в наименование модели при необходимости и зависит от файловой структуры информационных моделей, в том числе деления моделей конкретного раздела. Указание стадии проектирования **обязательно при архивации** модели, например, при переходе на другую стадию или при передаче заказчику или в экспертизу.

:::

[highlight:light-pink]Дополнение[/highlight] – опциональное поле, которое вводится для обозначения примечаний к модели или для деления моделей раздела по назначению, когда невозможно указать зону, корпус, секцию или блок отдельностоящих сооружений, например "КПП", "Ресторан", "ДСШ", "Фасад", "Паркинг", "Автостоянка" и т.д.. Может содержать буквенные и цифровые символы на кириллице.

[highlight:peach]Версия ПО[/highlight] - постоянное поле для обозначения программного обеспечения с помощью которого была разработана ЦИМ и его версии. Содержит код обозначения программного обеспечения на латинице и версию в формате "00". Наиболее используемые значения поля:

-  [highlight:peach]​R23[/highlight] – для Autodesk Revit 2023;

-  [highlight:peach]​NW23[/highlight] – для Autodesk Navisworks 2023;

-  ​[highlight:peach]CV23[/highlight] – для Autodesk Civil 3D 2023.

## Наименование вспомогательных файлов модели

Наименование базовых файлов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Компания[/highlight]\_[highlight:mint-green]Код проекта[/highlight]\_[highlight:light-pink]Зона\*[/highlight]\_БФ\_[highlight:peach]Версия ПО[/highlight]

Наименование разбивочных файлов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Компания[/highlight]\_[highlight:mint-green]Код проекта[/highlight]\_[highlight:light-pink]Зона\*[/highlight]\_[highlight:light-pink]Корпус\*[/highlight]\_РФ\_[highlight:peach]Версия ПО[/highlight]

Наименование файла заданий на отверстия должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Компания[/highlight]\_[highlight:mint-green]Код проекта[/highlight]\_[highlight:light-pink]Зона\*[/highlight]\_[highlight:light-pink]Корпус\*[/highlight]\_ОТВ\_[highlight:peach]Версия ПО[/highlight]

Наименование сводных файлов должно соответствовать следующей схеме (опциональные поля помечены символом \*):

[highlight:lemon-yellow]Компания[/highlight]\_[highlight:mint-green]Код проекта[/highlight]\_[highlight:light-pink]Зона\*[/highlight]\_[highlight:light-pink]Корпус\*[/highlight]\_[highlight:light-pink]Раздел\*[/highlight]\_СФ\_[highlight:peach]Версия ПО[/highlight]

:::info 

Описания полей наименования вспомогательных файлов модели (п. 2.2 настоящего стандарта) не отличается от основных файлов, если это не указано ниже.

:::