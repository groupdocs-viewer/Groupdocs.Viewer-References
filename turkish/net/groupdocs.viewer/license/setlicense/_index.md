---
title: "SetLicense"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Bileşeni lisanslar."
type: docs
weight: 20
url: /tr/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

Bileşeni lisanslar.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| licenseStream | Akış | Lisans akışı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *licenseStream* null olduğunda fırlatılır. |

### Örnekler

Aşağıdaki örnek, lisans dosyasının Stream'ini geçerek lisansı nasıl ayarlayacağınızı gösterir.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### Ayrıca Bakınız

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licensePath)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| licensePath | String | Lisans dosyası yolu. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *licensePath* null veya boş bir dize olduğunda fırlatılır. |

### Örnekler

Aşağıdaki örnek, lisans dosyasının yolunu geçirerek lisansı nasıl ayarlayacağınızı gösterir.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### Ayrıca Bakınız

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
