---
title: "Layout"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет макет, содержащийся в чертеже CAD."
type: docs
weight: 17
url: /ru/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Представляет макет, содержащийся в чертеже CAD.

Интерфейс Layout определяет контракт для доступа и манипулирования макетом внутри чертежа CAD в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации, такой как имя макета, размеры и другие свойства.

Пример использования:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Получает имя макета. |
| [setName(String name)](#setName-java.lang.String-) | Устанавливает имя макета. |
| [getWidth()](#getWidth--) | Получает ширину макета. |
| [setWidth(double width)](#setWidth-double-) | Устанавливает ширину макета. |
| [getHeight()](#getHeight--) | Получает высоту макета. |
| [setHeight(double height)](#setHeight-double-) | Устанавливает высоту макета. |
| [equals(Object other)](#equals-java.lang.Object-) | Проверяет, равен ли этот объект предоставленному объекту. |
### getName() {#getName--}
```
public abstract String getName()
```


Получает имя макета.

**Returns:**
java.lang.String - имя макета.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Устанавливает имя макета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя, которое следует установить для макета. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Получает ширину макета.

**Returns:**
double - ширина макета.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Устанавливает ширину макета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | Ширина, которую следует установить для макета. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Получает высоту макета.

**Returns:**
double - высота макета.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Устанавливает высоту макета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| height | double | Высота, которую следует установить для макета. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Проверяет, равен ли этот объект предоставленному объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | java.lang.Object | Объект для сравнения. |

**Returns:**
boolean -  true  если объекты равны,  false  иначе.
