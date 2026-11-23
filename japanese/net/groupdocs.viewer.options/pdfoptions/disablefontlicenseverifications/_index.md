---
title: "DisableFontLicenseVerifications"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### 備考

フォントに関する多くの操作は、そのフォントのライセンスで禁止されている場合は実行できません。例えば、ライセンス規則により埋め込みが無効化されているフォントは PDF ドキュメントに埋め込むことができません。このオプションを使用すると、これらの規則の検証をスキップできます。

このフラグを使用する際は注意してください。フラグが設定されると、その設定者が可能なライセンス／法的違反に関する全責任を自ら負うことを意味します。したがって、自己責任で使用することになります。このフラグは、著作権法に違反していないことに完全に自信がある場合にのみ使用することを強く推奨します。デフォルト値は `false` です。

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files) を参照してください。

### 関連項目

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
