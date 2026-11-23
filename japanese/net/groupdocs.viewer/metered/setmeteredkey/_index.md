---
title: "SetMeteredKey"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Metered キーで製品を有効化します。"
type: docs
weight: 20
url: /ja/net/groupdocs.viewer/metered/setmeteredkey/
---

## Metered.SetMeteredKey method

Metered キーで製品を有効化します。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| publicKey | String | 公開鍵です。 |
| privateKey | String | 秘密鍵です。 |

### 例

以下の例は、メータードキーを使用して製品を有効化する方法を示しています。

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### 関連項目

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
