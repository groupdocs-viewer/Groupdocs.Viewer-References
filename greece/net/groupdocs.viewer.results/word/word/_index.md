---
title: "Word"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί νέα παρουσία της κλάσης Wordgroupdocs.viewer.results/word."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

Αρχικοποιεί νέα παρουσία της κλάσης [`Word`](../../word).

```csharp
public Word()
```

### Δείτε επίσης

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

Αρχικοποιεί νέα παρουσία της κλάσης [`Word`](../../word).

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| λέξη | String | Η λέξη. |
| x | Double | Η συντεταγμένη X του υψηλότερου αριστερού σημείου στη διάταξη της σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη λέξη. |
| y | Double | Η συντεταγμένη Y του υψηλότερου αριστερού σημείου στη διάταξη της σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη λέξη. |
| width | Double | Το πλάτος του ορθογωνίου που περιέχει τη λέξη. |
| height | Double | Το ύψος του ορθογωνίου που περιέχει τη λέξη. |
| χαρακτήρες | List`1 | Οι χαρακτήρες που περιέχονται στη λέξη. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν *word* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *characters* είναι null. |

### Δείτε επίσης

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
