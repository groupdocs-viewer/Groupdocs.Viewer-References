---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "CAD図面のビュー情報を表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

CAD図面のビュー情報を表します。


CadViewInfo インターフェイスは、CAD 図面固有のビュー情報を取得するための契約を定義します
GroupDocs.Viewer コンポーネント内です。CAD 図面のレイヤーにアクセスするためのメソッドを提供します


使用例:

````

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is CadViewInfoImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getLayers()](#getLayers--) | CAD 図面のレイヤー一覧を取得します。 |
|
|  | [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | CAD 図面のレイヤー一覧を設定します。 |
|
|  | [getLayouts()](#getLayouts--) | CAD 図面に含まれるレイアウトの一覧を取得します。 |
|
|  | [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | CAD 図面に含まれるレイアウトの一覧を設定します。 |
|
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


CAD 図面のレイヤー一覧を取得します。


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 図面のレイヤーです。

### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


CAD 図面のレイヤー一覧を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | CAD 図面に設定するレイヤーです。 |
|

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


CAD 図面に含まれるレイアウトの一覧を取得します。


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - CAD 図面のレイアウトです。

### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


CAD 図面に含まれるレイアウトの一覧を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | CAD 図面に設定するレイアウトです。 |
|

