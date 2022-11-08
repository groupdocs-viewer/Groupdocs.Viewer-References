---
title: CadViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for CAD drawing.
type: docs
weight: 13
url: /java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Represents view information for CAD drawing. Default implementation is CadViewInfoImpl
## Methods

| Method | Description |
| --- | --- |
| [getLayers()](#getLayers--) | The list of layers contained by the CAD drawing. |
| [getLayouts()](#getLayouts--) | The list of layouts contained by the CAD drawing. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


The list of layers contained by the CAD drawing.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer>
### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


The list of layouts contained by the CAD drawing.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout>
