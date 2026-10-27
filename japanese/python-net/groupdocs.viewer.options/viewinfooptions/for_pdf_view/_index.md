---
title: "for_pdf_view メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PDF にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/
is_root: false
weight: 1050
---


## for_pdf_view

PDF にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。

```python
def for_pdf_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 例

```python
    from groupdocs.viewer.options import ViewInfoOptions

    # PDF 形式用のビュー情報オプションを作成する
    view_info_options_pdf = ViewInfoOptions.for_pdf_view()
    ```

### 参照
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
