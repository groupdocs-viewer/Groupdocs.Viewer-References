---
title: "Line"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί νέα παρουσία της κλάσης Linegroupdocs.viewer.results/line."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

Αρχικοποιεί νέα παρουσία της κλάσης [`Line`](../../line).

```csharp
public Line()
```

### Δείτε επίσης

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Αρχικοποιεί νέα παρουσία της κλάσης [`Line`](../../line).

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| γραμμή | String | Η γραμμή. |
| x | Double | Η συντεταγμένη X του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη γραμμή. |
| y | Double | Η συντεταγμένη Y του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη γραμμή. |
| width | Double | Το πλάτος του ορθογωνίου που περιέχει τη γραμμή (σε εικονοστοιχεία). |
| height | Double | Το ύψος του ορθογωνίου που περιέχει τη γραμμή (σε εικονοστοιχεία). |
| λέξεις | List`1 | Οι λέξεις που περιέχονται στη γραμμή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν *line* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *words* είναι null. |

### Δείτε επίσης

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
