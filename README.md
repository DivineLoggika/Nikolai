## Тема реферата: Понятия информационного обеспечения и информационной базы.

## Реферат к лекции 11 (27). [Базы данных.](https://github.com/stankin/design-part-2/wiki/lecture11)

**Выполнил:** [Шавыкина Таисия, ИДБ-19-07](https://github.com/pumpurik)

**Проверил:** [Маргита Елизавета, ИДБ-19-07](https://github.com/Bublock)

## Определения информационного обеспечения и информационной базы

* **Информационная база (ИБ)** — совокупность упорядоченной информации, используемой при функционировании АС.
* **Информационное обеспечение** - совокупность форм документов, классификаторов, нормативной базы и реализованных решений по объемам, размещению и формам существования информации, применяемой в АС при ее функционировании.

_Информационное обеспечение ИС_ является средством для решения следующих задач:

* однозначного и экономичного представления информации в системе (на основе кодирования объектов);
* организации процедур анализа и обработки информации с учетом характера связей между объектами (на основе классификации объектов);
* организации взаимодействия пользователей с системой (на основе экранных форм ввода-вывода данных);
* обеспечения эффективного использования информации в контуре управления деятельностью объекта автоматизации (на основе унифицированной системы документации ).

_Информационное обеспечение ИС_ включает два комплекса: внемашинное информационное обеспечение и внутримашинное информационное обеспечение (рис. 1).

![ForRef1](https://github.com/DivineLoggika/Nikolai.github.io/blob/3fc47c216aa5c75b95c36bd2b14e08cef92350a8/ForRef/ForRef1.png)

**Рис. 1. Два комплекса информационного обеспечения**

**К информационному обеспечению предъявляются следующие общие требования:**

* информационное обеспечение должно быть достаточным для поддержания всех автоматизируемых функций объекта;
* для кодирования информации должны использоваться принятые у заказчика классификаторы;
* для кодирования входной и выходной информации, которая используется на высшем уровне управления, должны быть использованы классификаторы этого уровня;
* должна быть обеспечена совместимость с информационным обеспечением систем, взаимодействующих с разрабатываемой системой;
* формы документов должны отвечать требованиям корпоративных стандартов заказчика (или унифицированной системы документации);
* структура документов и экранных форм должна соответствовать характеристикам терминалов на рабочих местах конечных пользователей;
* графики формирования и содержание информационных сообщений, а также используемые аббревиатуры должны быть общеприняты в этой предметной области и согласованы с заказчиком;

В ИС должны быть предусмотрены средства контроля входной и результатной информации, обновления данных в информационных массивах, контроля целостности информационной базы, защиты от несанкционированного доступа

### Внемашинное информационное обеспечение

Для того чтобы обеспечить эффективный поиск, обработку на [ЭВМ](https://ru.wikipedia.org/wiki/Электронная_вычислительная_машина) и передачу по каналам связи технико-экономической информации, ее необходимо представить в цифровом виде. С этой целью ее нужно сначала упорядочить (классифицировать), а затем формализовать (закодировать) с использованием **классификатора**.

**Классификация** – это разделение множества объектов на подмножества по их сходству или различию в соответствии с принятыми методами. Классификация фиксирует закономерные связи между классами объектов. Под объектом понимается любой предмет, процесс, явление материального или нематериального свойства. Система классификации позволяет сгруппировать объекты и выделить определенные классы, которые будут характеризоваться рядом общих свойств. Таким образом, совокупность правил распределения объектов множества на подмножества называется системой классификации.

**Классификатор** — это документ, с помощью которого осуществляется формализованное описание информации в ИС, содержащей наименования объектов, наименования классификационных группировок и их кодовые обозначения

По сфере действия выделяют следующие **виды классификаторов**: международные, общегосударственные (общесистемные), отраслевые и локальные классификаторы.
Каждая система классификации характеризуется следующими свойствами:
* гибкостью системы;
* емкостью системы;
* степенью заполненности системы.

**Гибкость системы** — это способность допускать включение новых признаков, объектов без разрушения структуры классификатора. Необходимая гибкость определяется временем жизни системы.

**Емкость системы** — это наибольшее количество классификационных группировок, допускаемое в данной системе классификации.

**Степень заполненности** системы определяется как частное от деления фактического количества группировок на величину емкости системы.

### Внутримашинное информационное обеспечение
Внутримашинное информационное обеспечение включает макеты (экранные формы) для ввода первичных данных в [ЭВМ](https://ru.wikipedia.org/wiki/Электронная_вычислительная_машина) или вывода результатной информации, и структуры информационной базы: входных, выходных файлов, базы данных.
Проектирование экранных форм электронных документов

**[Электронная форма документа (ЭД)](https://its.1c.ru/db/eldocs/content/12/hdoc)** — это страница с пустыми полями, оставленными для заполнения пользователем. Формы могут допускать различный тип входной информации и содержать командные кнопки, переключатели, выпадающие меню или списки для выбора.

Создание форм электронных документов требует использования специального программного обеспечения.

![ForRef2](https://github.com/DivineLoggika/Nikolai.github.io/blob/a436d28d939b7bbf4cee09754f39909254853c16/ForRef/ForRef.jpg)

**Рис. 2. Элементы электронного документа**

**К недостаткам электронных документов** можно отнести неполную юридическую проработку процесса их утверждения или подписания.

Технология обработки электронных документов требует использования специализированного программного обеспечения — программ управления документооборотом, которые зачастую встраиваются в корпоративные ИС.

Проектирование форм электронных документов, т.е. создание шаблона формы с помощью программного обеспечения проектирования форм, обычно включает в себя выполнение следующих шагов:

* создание структуры ЭД — подготовка внешнего вида с помощью графических средств проектирования;
* определение содержания формы ЭД, т.е. выбор способов, которыми будут заполняться поля. Поля могут быть заполнены вручную или посредством выбора  значений из какого-либо списка, меню, базы данных;
* определения перечня макетов экранных форм — по каждой задаче проектировщик анализирует "постановку" каждой задачи, в которой приводятся перечни используемых входных документов с оперативной и постоянной информацией и документов с результатной информацией;
* определение содержания макетов — выполняется на основе анализа состава реквизитов первичных документов с постоянной и оперативной информацией и результатных документов.

Работа заканчивается программированием разработанных макетов экранных форм и их апробацией.

### Информационная база и способы ее организации

Все файлы ИБ можно классифицировать по следующим признакам:

* по этапам обработки (входные, базовые, результатные);
* по типу носителя (на промежуточных носителях — гибких магнитных дисках и магнитных лентах и на основных носителях — жестких магнитных дисках, магнитооптических дисках и др.);
* по составу информации (файлы с оперативной информацией и файлы с постоянной информацией);
* по назначению (по типу функциональных подсистем);
* по типу логической организации (файлы с линейной и [иерархической структурой записи](https://ru.wikipedia.org/wiki/Иерархическая_модель_данных), [реляционные](https://translated.turbopages.org/proxy_u/en-ru.ru.b4783683-6398d562-323a3ff9-74722d776562/https/en.wikipedia.org/wiki/Relational_DB), [табличные](https://ru.wikipedia.org/wiki/Таблица_(база_данных)));
* по способу физической организации (файлы с последовательным, индексным и прямым способом доступа).

**Входные файлы** создаются с первичных документов для ввода данных или обновления базовых файлов.

Файлы с **результатной информацией** предназначаются для вывода ее на печать или передачи по каналам связи и не подлежат долговременному хранению.

К числу базовых файлов, хранящихся в информационной базе, относят основные, рабочие, промежуточные, служебные и архивные файлы.

Основные файлы должны иметь однородную структуру записей и могут содержать записи с оперативной и **условно-постоянной информацией.** Оперативные файлы могут создаваться на базе одного или нескольких входных файлов и отражать информацию одного или нескольких первичных документов. Файлы с условно-постоянной информацией могут содержать справочную, расценочную, табличную и другие виды информации, изменяющейся в течение года не более чем на 40%, а следовательно, имеющие коэффициент стабильности не менее 0,6.

Файлы со **справочной информацией** должны отражать все характеристики элементов материального производства (материалы, сырье, основные фонды, трудовые ресурсы и т.п.). Как правило, справочники содержат информацию классификаторов и дополнительные сведения об элементах Материальной сферы, например о ценах. Нормативно-расценочные файлы должны содержать данные о нормах расхода и расценках на выполнение операций и услуг. Табличные файлы содержат сведения об экономических показателях, считающихся постоянными в течение длительного времени (например, процент удержания, отчисления и пр.). Плановые файлы содержат плановые показатели, хранящиеся весь плановый период.

**Рабочие файлы** создаются для решения конкретных задач на базе основных файлов путем выборки части информации из нескольких основных файлов с целью сокращения времени обработки данных.

**Промежуточные файлы** отличаются от рабочих файлов тем, что они образуются в результате решения экономических задач, подвергаются хранению с целью дальнейшего использования для решения других задач. Эти файлы, так же как и рабочие файлы, при высокой частоте обращений могут быть также переведены в категорию основных файлов.

**Служебные файлы** предназначаются для ускорения поиска информации в основных файлах и включают в себя справочники, индексные файлы и каталоги.

**Архивные файлы** содержат ретроспективные данные из основных файлов, которые используются для решения аналитических, например прогнозных, задач. Архивные данные могут также использоваться для восстановления информационной базы при разрушениях.

Организация хранения файлов в информационной базе должна отвечать следующим требованиям:

* полнота хранимой информации для выполнения всех функций управления и решения экономических задач;
* целостность хранимой информации, т. е. обеспечение непротиворечивости данных при вводе информации в ИБ;
* своевременность и одновременность обновления данных во всех копиях данных;
* гибкость системы, т.е. адаптируемость ИБ к изменяющимся информационным потребностям;
* реализуемость системы, обеспечивающая требуемую степень сложности структуры ИБ;
* релевантность ИБ, под которой подразумевается способность системы осуществлять поиск и выдавать информацию, точно соответствующую запросам пользователей;
* удобство языкового интерфейса, позволяющее быстро формулировать запрос к ИБ;
* разграничение прав доступа, т.е. определение для каждого пользователя доступных типов записей, полей, файлов и видов операций над ними

Существуют следующие **способы организации ИБ:** совокупность локальных файлов, поддерживаемых функциональными пакетами прикладных программ, и интегрированная база данных, основывающаяся на использовании универсальных программных средств загрузки, хранения, поиска и ведения данных, т.е. системы управления базами данных (СУБД).

**Интегрированная ИБ**, т.е. база данных (БД) — это совокупность взаимосвязанных, хранящихся вместе данных при такой минимальной избыточности, которая допускает их использование оптимальным образом для множества приложений.

### Ссылки
* [Информация. Лекция проектирование информационных систем](https://intuit.ru/studies/courses/2195/55/lecture/1634?page=2)
* [Информационная база и способы ее организации](https://studfile.net/preview/2915208/page:20/)
