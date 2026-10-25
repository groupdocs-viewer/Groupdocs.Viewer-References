---
title: "DetectEncoding"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Προσπάθειες για ανίχνευση κωδικοποίησης αρχείων κειμένου TXTgroupdocs.viewer/filetype/txt TSVgroupdocs.viewer/filetype/tsv και CSVgroupdocs.viewer/filetype/csv με βάση τη διαδρομή."
type: docs
weight: 2060
url: /el/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

Προσπάθειες για ανίχνευση κωδικοποίησης αρχείων κειμένου [`TXT`](../txt), [`TSV`](../tsv), και [`CSV`](../csv) με βάση τη διαδρομή.

```csharp
public static Encoding DetectEncoding(string filePath)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Το όνομα αρχείου ή η διαδρομή του αρχείου. |

### Τιμή Επιστροφής

Κωδικοποίηση ή null όταν αποτυγχάνει η ανίχνευση κωδικοποίησης αρχείου.

### Παραδείγματα

Το παράδειγμα δείχνει πώς να ανιχνεύσετε την κωδικοποίηση αρχείου κειμένου.

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### Δείτε επίσης

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

Προσπάθειες για ανίχνευση κωδικοποίησης αρχείων κειμένου [`TXT`](../txt), [`TSV`](../tsv), και [`CSV`](../csv) με βάση τη ροή.

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |

### Τιμή Επιστροφής

Κωδικοποίηση ή null όταν αποτυγχάνει η ανίχνευση κωδικοποίησης αρχείου.

### Παραδείγματα

Το παράδειγμα δείχνει πώς να ανιχνεύσετε την κωδικοποίηση αρχείου κειμένου.

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### Δείτε επίσης

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
