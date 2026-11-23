---
title: "enable_layered_rendering プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、HTML へのレンダリング時に元の PDF ドキュメントの Z オーダーでテキストとグラフィックのレンダリングを有効にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

このプロパティは、HTML へのレンダリング時に元の PDF ドキュメントの Z オーダーでテキストとグラフィックのレンダリングを有効にします。

デフォルトでは、GroupDocs.Viewer はテキストとグラフィックを HTML の単一レイヤーとしてレンダリングします。このオプションを使用すると、オブジェクトを元ファイルと同じ順序で配置できます。デフォルト値は False です。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
