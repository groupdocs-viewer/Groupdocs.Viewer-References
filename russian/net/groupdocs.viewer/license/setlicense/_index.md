---
title: "SetLicense"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Лицензирует компонент."
type: docs
weight: 20
url: /ru/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

Лицензирует компонент.

```csharp
public void SetLicense(Stream licenseStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| licenseStream | Поток | Поток лицензии. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *licenseStream* равен null. |

### Примеры

В следующем примере показано, как установить лицензию, передавая Stream файла лицензии.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### См. также

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Лицензирует компонент.

```csharp
public void SetLicense(string licensePath)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| licensePath | String | Путь к файлу лицензии. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *licensePath* равен null или пустой строке. |

### Примеры

В следующем примере показано, как установить лицензию, передавая путь к файлу лицензии.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### См. также

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
