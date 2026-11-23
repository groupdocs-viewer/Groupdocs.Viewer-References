---
title: "ForRenderingByWidthAndHeight"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί μια παρουσία της κλάσης CadOptionsgroupdocs.viewer.options/cadoptions για απόδοση με βάση το πλάτος και το ύψος."
type: docs
weight: 40
url: /el/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

Αρχικοποιεί μια παρουσία της κλάσης [`CadOptions`](../../cadoptions) για απόδοση με βάση το πλάτος και το ύψος.

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| width | Int32 | Το πλάτος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |
| height | Int32 | Το ύψος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`CadOptions`](../../cadoptions) για απόδοση με βάση το πλάτος και το ύψος.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται όταν το *width* είναι μικρότερο ή ίσο με το μηδέν. |
| ArgumentException | Εγείρεται όταν το *height* είναι μικρότερο ή ίσο με το μηδέν. |

### Παρατηρήσεις

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### Δείτε επίσης

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
