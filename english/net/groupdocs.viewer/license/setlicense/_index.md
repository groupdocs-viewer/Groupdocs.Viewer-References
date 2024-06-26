---
title: SetLicense
second_title: GroupDocs.Viewer for .NET API Reference
description: Licenses the component.
type: docs
weight: 20
url: /net/groupdocs.viewer/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licenses the component.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | Stream | The license stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *licenseStream* is null. |

### Examples

The following example demonstrates how to set a license passing Stream of the license file.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### See Also

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Licenses the component.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | String | The license file path. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *licensePath* is null or empty string. |

### Examples

The following example demonstrates how to set a license passing a path to the license file.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### See Also

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
