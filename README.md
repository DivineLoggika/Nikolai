## Тема реферата: Понятия информационного обеспечения и информационной базы.

## Реферат к лекции 11 (27). [Базы данных.](https://github.com/stankin/design-part-2/wiki/lecture11)

**Выполнил:** [Шавыкина Таисия, ИДБ-19-07](https://github.com/pumpurik)

**Проверил:** [Маргита Елизавета, ИДБ-19-07](https://github.com/Bublock)

## Определения информационного обеспечения и информационной базы

### Информационное обеспечение

**Информационное обеспечение автоматизированной системы** - это совокупность форм документов, классификаторов, нормативной базы и реализованных решений по объемам, размещению и формам существования информации, применяемой в автоматизированной системе при ее функционировании.

**Информационное средство** - комплекс упорядоченной относительно постоянной информации на носителе данных, описывающей параметры и характеристики заданной области применения и соответствующей документации, предназначенный для поставки пользователю.

*Примечание. Документация информационного средства может поставляться на носителе данных.*

**Внешнему информационному обеспечению** относят создание и ведение классификаторов технико-экономической информации, организации хранения и движения документов с условно-постоянной информацией на объекте автоматизации. Разрабатываются маршруты движения документов, определяются места хранения; периодичность и технологию введения информационного обеспечения, поиска, хранения и уничтожения документов. Разрабатывается организационная структура для управления вышеперечисленными процессами.

**Внутреннее информационное обеспечение** обеспечивает все функции создания и ведения условно-постоянной информации на машинных носителях, включая резервные копии и архивы.

К информационному обеспечению предъявляются следующие **общие требования**:

− информационное обеспечение должно быть достаточным для поддержания всех автоматизируемых функций объекта;

− для кодирования информации должны использоваться принятые у заказчика классификаторы;

− для кодирования входной и выходной информации, которая используется на высшем уровне управления, должны быть использованы классификаторы этого уровня;

− должна быть обеспечена совместимость с информационным обеспечением систем, взаимодействующих с разрабатываемой системой;

− формы документов должны отвечать требованиям корпоративных стандартов заказчика (или унифицированной системы документации);

− структура документов и экранных форм должна соответствовать характеристиками терминалов на рабочих местах конечных пользователей;

− графики формирования и содержание информационных сообщений, а также используемые аббревиатуры должны быть общеприняты в этой предметной области и согласованы с заказчиком;

− в ИС должны быть предусмотрены средства контроля входной и результатной информации, обновления данных в информационных массивах, контроля целостности информационной базы, защиты от несанкционированного доступа.

**Информационное обеспечение управленческой деятельности** должно учитывать существующие законодательные и нормативные ограничения и необходимость внутренней регламентации, а также обеспечивать необходимый уровень безопасности при использовании технических средств в рамках соответствующих информационных технологий и уровень информационной безопасности.

**Нормативно-методическая база информационного обеспечения управленческой деятельности** - это совокупность законов, нормативных правовых актов и методических документов, регламентирующих технологии создания документов, их обработки, хранения и использования в текущей деятельности организации.

**Информационная база автоматизированной системы** - совокупность упорядоченной информации, используемой при функционировании автоматизированной системы.

**Внемашинная информационная база автоматизированной системы** - часть информационной базы автоматизированной системы, представляющая собой совокупность документов, предназначенных для непосредственного восприятия человеком без применения средств вычислительной техники.

**Машинная информационная база автоматизированной системы** - часть информационной базы автоматизированной системы, представляющая собой совокупность используемой в автоматизированной системе информации на носителях данных.

### Описание организации информационной базы согласно ГОСТ Р 59795 - 2021

Документ **«Описание организации информационной базы»** должен содержать разделы:

* описание внутримашинной информационной базы;
* описание внемашинной информационной базы.

Раздел **«Описание внутримашинной информационной базы»** должен содержать следующие подразделы:

* логическая структура;
* физическая структура;
* организация ведения внутримашинной информационной базы.

В подразделе **«Логическая структура»** приводят описание состава данных, их форматов и взаимосвязей между данными.

В подразделе **«Физическая структура»** приводят описания физической реализации всех баз данных и массивов информации.

При описании структуры внутримашинной информационной базы должны быть приведены перечни баз данных и массивов информации, а также логические связи между ними. Для массива информации указывают логическую структуру внутри массива информации или дают ссылку на документ «Описание массива информации».

В подразделе **«Организация ведения внутримашинной информационной базы»** приводят последовательность процедур при ее создании, актуализации и обслуживании с указанием, при необходимости, регламента выполнения процедур и средств ее защиты от разрушения и несанкционированного доступа. Должны быть описаны связи между данными, содержащимися во внутримашинной информационной базе, и входными данными.

Раздел **«Описание внемашинной информационной базы»** должен содержать перечень документов и других информационных сообщений, использование которых предусмотрено в АС, с указанием для каждого документа или сообщения автоматизируемых функций, при реализации которых его формируют или используют.

Для каждого документа или сообщения должна быть описана процедура его формирования и передачи.

### Информационная база

**Информационная база (в обобщенном виде)** — совокупность упорядоченной информации, используемой при функционировании автоматизированной системы.

**Информационная база** — это экземпляр одного прикладного решения. Она представляет собой логически целостную систему, включающую две конфигурации (как минимум), базу данных, а также дополнительную информацию, необходимую для администрирования.

![](https://github.com/pumpurik/VKR/blob/ef6b43f218d3fdd6b71dadb7e654b5637c2473b2/001.png)

Назначение отдельных элементов информационной базы можно определить следующим образом:
**Конфигурация** — это программа, которая исполняется;

**Административная информация** — это, например, список пользователей, которые имеют те или иные права.
Имея одну конфигурацию (прикладное решение) вы можете создать несколько информационных баз (экземпляров прикладного решения), которые будут содержать разные данные и разный состав пользователей.

**База данных (database)** - совокупность взаимосвязанных данных, организованных в соответствии со схемой базы данных таким образом, чтобы с ними мог работать пользователь.

**Данные (data)** - информация, представленная в формализованном виде, пригодном для передачи, интерпретации или обработки с участием человека или автоматическими средствами.

**Схема базы данных (database schema)** - формальное описание данных в соответствии с конкретной схемой данных

**Схема данных (data schema)** - логическое представление организации данных

**Тип данных (data type)** - поименованная совокупность данных с общими свойствами

**Система управления базами данных (database management system)** - совокупность программных и языковых средств, обеспечивающих управление базами данных

Две конфигурации, которые всегда есть в информационной базе, имеют следующее назначение:

**Конфигурация базы данных** — это исполняемая конфигурация. С ней работают пользователи прикладного решения. Непосредственно редактировать эту конфигурацию нельзя. Изменить ее можно только в результате регламентной операции Обновление конфигурации базы данных.

**Основная конфигурация** — это конфигурация, которую можно редактировать непосредственно в режиме Конфигуратор, или можно загрузить из XML-файлов.
Процесс разработки прикладного решения заключается в изменении основной конфигурации. Чтобы эти изменения стали доступны пользователям, необходимо выполнить обновление конфигурации базы данных. Эта операция заключается в том, что основная конфигурация объединяется с конфигурацией базы данных, после чего платформа, выполняет реструктуризацию базы данных. Реструктуризация базы данных выполняется не всегда, а только в тех случаях, когда изменяется структура таблиц, хранящих данные.

### Ссылки
* [Описание организации информационной базы по ГОСТ Р 59795 - 2021](https://www.swrit.ru/articles/opisanie-organizacii-informacionnoj-bazy-59795-2021.html)
* [ГОСТ 34.003-90 Информационная технология (ИТ). Комплекс стандартов на автоматизированные системы. Автоматизированные системы. Термины и определения](https://internet-law.ru/gosts/gost/10673/)
* [ГОСТ 34.321-96 Информационные технологии (ИТ). Система стандартов по базам данных. Эталонная модель управления данными](https://docs.cntd.ru/document/1200017662)
* [Информационная база :: 1C:Enterprise Development Tools Руководство разработчика](https://its.1c.ru/db/edtdoc#content:10316:hdoc)

