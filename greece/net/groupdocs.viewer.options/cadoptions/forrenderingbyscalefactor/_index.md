---
title: "ForRenderingByScaleFactor"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί μια παρουσία της κλάσης CadOptionsgroupdocs.viewer.options/cadoptions για απόδοση με συντελεστή κλίμακας."
type: docs
weight: 20
url: /el/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

Αρχικοποιεί μια παρουσία της κλάσης [`CadOptions`](../../cadoptions) για απόδοση με συντελεστή κλίμακας.

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| scaleFactor | Single | Τιμή μεγαλύτερη από 1 μεγεθύνει το αποτέλεσμα εξόδου· τιμή μεταξύ 0 και 1 μειώνει το αποτέλεσμα εξόδου. |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`CadOptions`](../../cadoptions) για απόδοση με συντελεστή κλίμακας.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *scaleFactor* είναι μικρότερο ή ίσο με το μηδέν. |

### Παρατηρήσεις

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### Δείτε επίσης

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
