---
title: "TextElement"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί νέα παρουσία της κλάσης TextElementgroupdocs.viewer.results/textelement1."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

Αρχικοποιεί νέα παρουσία της κλάσης [`TextElement`](../../textelement-1).

```csharp
public TextElement()
```

### Δείτε επίσης

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

Αρχικοποιεί νέα παρουσία της κλάσης [`TextElement`](../../textelement-1).

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | T | Η τιμή του στοιχείου κειμένου. |
| x | Double | Η συντεταγμένη X του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει το στοιχείο. |
| y | Double | Η συντεταγμένη Y του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει το στοιχείο. |
| width | Double | Το πλάτος του ορθογωνίου που περιέχει το στοιχείο (σε pixel). |
| height | Double | Το ύψος του ορθογωνίου που περιέχει το στοιχείο (σε pixel). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Αναβαλλόμενη όταν *value* είναι null. |
| ArgumentException | Εγείρεται όταν το *width* είναι μικρότερο ή ίσο με το μηδέν. |
| ArgumentException | Εγείρεται όταν το *height* είναι μικρότερο ή ίσο με το μηδέν. |

### Δείτε επίσης

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
