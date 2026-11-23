---
title: "SetLicense"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "コンポーネントにライセンスを付与します。"
type: docs
weight: 20
url: /ja/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(Stream licenseStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| licenseStream | ストリーム | ライセンス ストリームです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *licenseStream* が null のときにスローされます。 |

### 例

次の例は、ライセンス ファイルの Stream を渡してライセンスを設定する方法を示しています。

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### 関連項目

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

コンポーネントにライセンスを付与します。

```csharp
public void SetLicense(string licensePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| licensePath | String | ライセンス ファイルのパスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *licensePath* が null または空文字列のときにスローされます。 |

### 例

次の例は、ライセンス ファイルへのパスを渡してライセンスを設定する方法を示しています。

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### 関連項目

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
