---
title: "Rotation"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Содержит вращение страницы в градусах по часовой стрелке."
type: docs
weight: 45
url: /ru/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Содержит вращение страницы в градусах (по часовой стрелке).


Перечисление Rotation представляет различные углы вращения страницы в компоненте GroupDocs.Viewer.
Он предоставляет набор предопределённых вариантов вращения, которые можно использовать для указания угла вращения
для рендеринга страницы в различных сценариях просмотра документов или их конвертации.


Пример использования:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | Вращение страницы на 90 градусов. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | Вращение страницы на 180 градусов. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | Вращение страницы на 270 градусов. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


Вращение страницы на 90 градусов.
Это вращение представляет собой поворот страницы на 90 градусов по часовой стрелке.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


Вращение страницы на 180 градусов.
Это вращение представляет собой поворот страницы на 180 градусов по часовой стрелке.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


Вращение страницы на 270 градусов.
Это вращение представляет собой поворот страницы на 270 градусов по часовой стрелке.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
