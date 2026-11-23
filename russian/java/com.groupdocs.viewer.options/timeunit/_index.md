---
title: "TimeUnit"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Единица времени продолжительности проекта."
type: docs
weight: 47
url: /ru/java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Единица времени продолжительности проекта.


Перечисление TimeUnit представляет различные единицы времени для указания длительности проекта в компоненте GroupDocs.Viewer.
Оно предоставляет набор предопределённых единиц времени, которые можно использовать для представления и расчёта длительности проекта,
таких как дни, месяцы и т.д.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


Пример использования:

````

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | Неизвестная шкала времени. |
|
|  | [DAYS](#DAYS) | Шкала времени в днях. |
|
|  | [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Треть месяца — шкала времени. |
|
|  | [MONTHS](#MONTHS) | Месячная шкала времени. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Неизвестная шкала времени.
Эта единица времени представляет неизвестную или неопределённую шкалу времени.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Шкала времени в днях.
Эта единица времени представляет однодневный интервал.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Треть месяца — шкала времени.
Эта единица времени представляет интервал в одну треть месяца.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Месячная шкала времени.
Эта единица времени представляет одномесячный интервал.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


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
