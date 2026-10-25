---
title: "SetLicense"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Lizenziert die Komponente."
type: docs
weight: 20
url: /de/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| licenseStream | Stream | Der Lizenz-Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *licenseStream* null ist. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine Lizenz setzt, indem man einen Stream der Lizenzdatei übergibt.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| licensePath | String | Der Pfad zur Lizenzdatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *licensePath* null oder ein leerer String ist. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine Lizenz setzt, indem man einen Pfad zur Lizenzdatei übergibt.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
