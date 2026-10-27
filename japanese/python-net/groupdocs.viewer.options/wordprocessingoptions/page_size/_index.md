---
title: "page_size プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "出力ページのサイズ。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

出力ページのサイズ。

既定値は `PageSize.Unspecified` で、ページ設定（ページ設定）で指定されたページサイズが使用されることを意味します。

HTM および HTML ファイルをレンダリングする際、既定のページサイズは Letter（792 x 612 ポイント）に設定されます。

その結果、コンテンツの一部がページ枠に収まらない可能性があります。

コンテンツに合わせるため、例えば `PageSize.A3` のように大きなページサイズを設定してください。

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### 参照
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
