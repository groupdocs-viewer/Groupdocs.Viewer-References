---
title: "CadViewInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "CAD 図面のビュー情報を表します。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

CAD 図面のビュー情報を表します。

CadViewInfo インターフェイスは、GroupDocs.Viewer コンポーネント内の CAD 図面に固有のビュー情報を取得するための契約を定義します。CAD 図面のレイヤーにアクセスするメソッドを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLayers()](#getLayers--) | CAD 図面のレイヤー一覧を取得します。 |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | CAD 図面のレイヤー一覧を設定します。 |
| [getLayouts()](#getLayouts--) | CAD 図面に含まれるレイアウトの一覧を取得します。 |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | CAD 図面に含まれるレイアウトの一覧を設定します。 |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


CAD 図面のレイヤー一覧を取得します。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 図面のレイヤー。
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


CAD 図面のレイヤー一覧を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| レイヤー | java.util.List<com.groupdocs.viewer.results.Layer> | CAD 図面に設定するレイヤー。 |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


CAD 図面に含まれるレイアウトの一覧を取得します。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - CAD 図面のレイアウト。
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


CAD 図面に含まれるレイアウトの一覧を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| レイアウト | java.util.List<com.groupdocs.viewer.results.Layout> | CAD 図面に設定するレイアウト。 |

