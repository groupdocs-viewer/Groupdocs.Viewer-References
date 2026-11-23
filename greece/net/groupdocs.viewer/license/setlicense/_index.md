---
title: "SetLicense"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αδειοδοτεί το στοιχείο."
type: docs
weight: 20
url: /el/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(Stream licenseStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| licenseStream | Stream | Η ροή άδειας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *licenseStream* είναι null. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε μια άδεια περνώντας το Stream του αρχείου άδειας.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Αδειοδοτεί το στοιχείο.

```csharp
public void SetLicense(string licensePath)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| licensePath | String | Η διαδρομή του αρχείου άδειας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *licensePath* είναι null ή κενή συμβολοσειρά. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε μια άδεια περνώντας μια διαδρομή στο αρχείο άδειας.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
