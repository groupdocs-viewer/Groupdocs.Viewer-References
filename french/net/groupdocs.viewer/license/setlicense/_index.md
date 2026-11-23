---
title: "SetLicense"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Licence le composant."
type: docs
weight: 20
url: /fr/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

Licence le composant.

```csharp
public void SetLicense(Stream licenseStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseStream | Flux | Le flux de licence. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *licenseStream* est nul. |

### Exemples

L'exemple suivant montre comment définir une licence en passant le flux du fichier de licence.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licensePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licensePath | String | Le chemin du fichier de licence. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *licensePath* est nul ou une chaîne vide. |

### Exemples

L'exemple suivant montre comment définir une licence en passant un chemin vers le fichier de licence.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
