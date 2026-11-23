---
title: "disable_font_license_verifications プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

このプロパティは、現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。

フォントのライセンスで禁止されている場合、多くのフォント操作は実行できません。例えば、ライセンス規則により埋め込みが無効化されているフォントは PDF 文書に埋め込むことができません。このオプションを使用すると、これらの規則の検証をスキップできます。

このフラグを使用する際は注意してください。フラグが設定されると、そのフラグを設定した人物がライセンス違反や法的違反に対する全責任を負うことを意味します。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。デフォルト値は `False` です。

コード例については、https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files のドキュメントをご覧ください。

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
