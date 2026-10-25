---
title: "PageSize"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Размер страницы."
type: docs
weight: 42
url: /ru/java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

Размер страницы.


Перечисление PageSize представляет различные размеры страниц в компоненте GroupDocs.Viewer.
Оно предоставляет набор предопределённых размеров страниц, которые можно использовать для указания размеров
страницы в различных сценариях рендеринга документов.


Пример использования:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | Размер страницы по умолчанию, не указанный явно. |
|
|  | [LETTER](#LETTER) | Размер страницы Letter в пунктах: 792 × 612. |
|
|  | [LEDGER](#LEDGER) | Размер страницы A0 в пунктах: 3371 × 2384. |
|
|  | [A0](#A0) | Размер страницы A1 в пунктах: 2384 × 1685. |
|
|  | [A1](#A1) | Размер страницы A2 в пунктах составляет 1684 x 1190. |
|
|  | [A2](#A2) | Размер страницы A3 в пунктах составляет 1190 x 842. |
|
|  | [A3](#A3) | Размер страницы A3 в пунктах составляет 1190 x 842. |
|
|  | [A4](#A4) | Размер страницы A4 в пунктах составляет 842 x 595. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


Размер страницы по умолчанию, не указанный явно.
Этот размер используется, когда не указан конкретный размер страницы.


### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Размер страницы Letter в пунктах: 792 × 612.
Этот размер страницы обычно используется для писем и документов в Северной Америке.


### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


Размер страницы A0 в пунктах: 3371 × 2384.
Этот большой размер страницы является частью международного стандарта ISO 216.


### A0 {#A0}
```
public static final PageSize A0
```


Размер страницы A1 в пунктах: 2384 × 1685.
Этот размер страницы является частью международного стандарта ISO 216.


### A1 {#A1}
```
public static final PageSize A1
```


Размер страницы A2 в пунктах составляет 1684 x 1190.
Этот размер страницы является частью международного стандарта ISO 216.


### A2 {#A2}
```
public static final PageSize A2
```


Размер страницы A3 в пунктах составляет 1190 x 842.
Этот размер страницы является частью международного стандарта ISO 216.


### A3 {#A3}
```
public static final PageSize A3
```


Размер страницы A3 в пунктах составляет 1190 x 842.
Этот размер страницы является частью международного стандарта ISO 216.


### A4 {#A4}
```
public static final PageSize A4
```


Размер страницы A4 в пунктах составляет 842 x 595.
Этот размер страницы является частью международного стандарта ISO 216.


### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
