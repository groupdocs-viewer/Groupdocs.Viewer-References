---
title: SetLicense
second_title: GroupDocs.Viewer för .NET API-referens
description: Licensierar komponenten.
type: docs
weight: 20
url: /sv/net/groupdocs.viewer/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licensierar komponenten.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseStream | Stream | Licensströmmen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*licenseStream* är inget. |

### Exempel

Följande exempel visar hur man ställer in en license som passerar Stream av licensfilen.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### Se även

* class [License](../../license)
* namnutrymme [GroupDocs.Viewer](../../license)
* hopsättning [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Licensierar komponenten.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licensePath | String | Licensfilens sökväg. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*licensePath* är null eller tom sträng. |

### Exempel

Följande exempel visar hur man ställer in en licens genom att skicka en sökväg till licensfilen.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### Se även

* class [License](../../license)
* namnutrymme [GroupDocs.Viewer](../../license)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->