---
title: "TimeUnit"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Единица измерения времени длительности проекта."
type: docs
weight: 47
url: /ru/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Единица измерения времени длительности проекта.

Перечисление TimeUnit представляет различные единицы времени для указания продолжительности проекта в компоненте GroupDocs.Viewer. Оно предоставляет набор предопределённых единиц времени, которые можно использовать для представления и расчёта продолжительности проекта, таких как дни, месяцы и т.д. Для подробностей см. [documentation][].

Пример использования:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## Поля

| Поле | Описание |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Неизвестная шкала времени. |
| [DAYS](#DAYS) | Шкала времени в днях. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Шкала времени в третьих частях месяца. |
| [MONTHS](#MONTHS) | Шкала времени в месяцах. |
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Неизвестная шкала времени. Эта единица времени представляет неизвестную или неуказанную шкалу времени.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Шкала времени в днях. Эта единица времени представляет интервал в один день.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Шкала времени в третьих частях месяца. Эта единица времени представляет интервал в одну треть месяца.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Шкала времени в месяцах. Эта единица времени представляет интервал в один месяц.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
