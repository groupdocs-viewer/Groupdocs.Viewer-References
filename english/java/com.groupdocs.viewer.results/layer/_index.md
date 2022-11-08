---
title: Layer
second_title: GroupDocs.Viewer for Java API Reference
description: Represents layer contained by the CAD drawing.
type: docs
weight: 16
url: /java/com.groupdocs.viewer.results/layer/
---```
public interface Layer
```

Represents layer contained by the CAD drawing. Default implementation is LayerImpl
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | The name of the layer. |
| [isVisible()](#isVisible--) | The layer visibility indicator. |
| [equals(Object other)](#equals-java.lang.Object-) | Checks equality |
### getName() {#getName--}
```
public abstract String getName()
```


The name of the layer. Layer names are case sensitive.

**Returns:**
java.lang.String
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


The layer visibility indicator. The CAD drawing layers that are switched off or frozen are invisible. To render layers that are invisible, use ([CadOptions.getLayers](../../com.groupdocs.viewer.options/cadoptions\#getLayers)/[CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-) option.

**Returns:**
boolean
### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Checks equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | object to compare |

**Returns:**
boolean - true if equal, otherwise false
