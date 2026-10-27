---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет информацию о представлении чертежа CAD."
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Представляет информацию о представлении чертежа CAD.

Интерфейс CadViewInfo определяет контракт для получения информации о представлении, специфичной для CAD‑чертежа, в компоненте GroupDocs.Viewer. Он предоставляет методы для доступа к слоям CAD‑чертежа.

Пример использования:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Методы

| Метод | Описание |
| --- | --- |
| [getLayers()](#getLayers--) | Получает список слоёв в CAD‑чертежe. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Устанавливает список слоёв в CAD‑чертежe. |
| [getLayouts()](#getLayouts--) | Получает список компоновок, содержащихся в CAD‑чертежe. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Устанавливает список компоновок, содержащихся в CAD‑чертежe. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Получает список слоёв в CAD‑чертежe.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> — слои в CAD‑чертежe.
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Устанавливает список слоёв в CAD‑чертежe.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | слои, которые необходимо установить для CAD‑чертежа. |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Получает список компоновок, содержащихся в CAD‑чертежe.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> — компоновки в CAD‑чертежe.
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Устанавливает список компоновок, содержащихся в CAD‑чертежe.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | компоновки, которые необходимо установить для CAD‑чертежа. |

