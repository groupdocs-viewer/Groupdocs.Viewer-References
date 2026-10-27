---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга файлов управления проектами."
type: docs
weight: 27
url: /ru/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Предоставляет параметры для рендеринга файлов управления проектами.

Класс ProjectManagementOptions инкапсулирует различные настройки и параметры, которые можно использовать для управления рендерингом файлов управления проектами (например, Microsoft Project или аналогичных) в компоненте GroupDocs.Viewer. Для подробностей см. [documentation][].

Пример использования:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | Инициализирует новый экземпляр класса  ProjectManagementOptions . |
## Методы

| Метод | Описание |
| --- | --- |
| [getPageSize()](#getPageSize--) | Получает размер выходной страницы. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Устанавливает размер выходной страницы. |
| [getTimeUnit()](#getTimeUnit--) | Получает единицу измерения времени. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Получает единицу измерения времени. |
| [getStartDate()](#getStartDate--) | Получает дату начала представления диаграммы Ганта, которая будет включена в вывод. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Устанавливает дату начала представления диаграммы Ганта, которая будет включена в вывод. |
| [getEndDate()](#getEndDate--) | Получает дату окончания представления диаграммы Ганта, которая будет включена в вывод. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Устанавливает дату окончания представления диаграммы Ганта, которая будет включена в вывод. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Инициализирует новый экземпляр класса  ProjectManagementOptions .

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Получает размер выходной страницы.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Устанавливает размер выходной страницы.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Размер выходной страницы. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Получает единицу измерения времени.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Получает единицу измерения времени.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Единица измерения времени. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Получает дату начала представления диаграммы Ганта, которая будет включена в вывод.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date — дата начала представления диаграммы Ганта.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Устанавливает дату начала представления диаграммы Ганта, которая будет включена в вывод.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Дата начала представления диаграммы Ганта. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Получает дату окончания представления диаграммы Ганта, которая будет включена в вывод.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date — дата окончания представления диаграммы Ганта.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Устанавливает дату окончания представления диаграммы Ганта, которая будет включена в вывод.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Дата окончания представления диаграммы Ганта. |

