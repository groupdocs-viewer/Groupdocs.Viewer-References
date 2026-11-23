---
title: "Layer"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет слой, содержащийся в CAD‑чертежe."
type: docs
weight: 16
url: /ru/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Представляет слой, содержащийся в CAD‑чертежe.


Интерфейс Layer определяет контракт для доступа и манипулирования слоем в CAD‑чертежe
в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации, такой как имя слоя,
видимость и другие свойства.


Пример использования:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## Методы

| Метод | Описание |
| --- | --- |
|  | [getName()](#getName--) | Получает имя слоя. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Устанавливает имя слоя. |
|
|  | [isVisible()](#isVisible--) | Проверяет видимость слоя. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | Устанавливает видимость слоя. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Проверяет, равен ли этот объект предоставленному объекту. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Получает имя слоя.


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - имя слоя.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Устанавливает имя слоя.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя | java.lang.String | Новое имя слоя. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Проверяет видимость слоя.


Слои чертежа CAD, которые отключены или заморожены, невидимы.
Чтобы отобразить невидимые слои, используйте параметр [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-).


**Returns:**
boolean -  true  если слой видим,  false  в противном случае.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Устанавливает видимость слоя.


Если
true
, слой будет видим; если
false
, он будет скрыт.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | isVisible | boolean | Должен ли слой быть видимым или нет. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Проверяет, равен ли этот объект предоставленному объекту.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | другое | java.lang.Object | Объект для сравнения. |
|

**Returns:**
boolean -  true  если объекты равны,  false  в противном случае.

