---
title: "FromStream"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Εντοπίζει τον τύπο του αρχείου διαβάζοντας την υπογραφή του αρχείου."
type: docs
weight: 2000
url: /el/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

Εντοπίζει τον τύπο του αρχείου διαβάζοντας την υπογραφή του αρχείου.

```csharp
public static FileType FromStream(Stream stream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |

### Δείτε επίσης

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

Εντοπίζει τον τύπο του αρχείου διαβάζοντας την υπογραφή του αρχείου.

```csharp
public static FileType FromStream(Stream stream, string password)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| password | String | Ο κωδικός για το άνοιγμα του αρχείου. |

### Δείτε επίσης

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

Εντοπίζει τον τύπο του αρχείου διαβάζοντας την υπογραφή του αρχείου.

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| logger | ILogger | Ο καταγραφέας. |

### Τιμή Επιστροφής

Επιστρέφει τον τύπο αρχείου σε περίπτωση που εντοπίστηκε επιτυχώς, διαφορετικά επιστρέφει τον προεπιλεγμένο τύπο αρχείου [`Unknown`](../unknown).

### Δείτε επίσης

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

Εντοπίζει τον τύπο του αρχείου διαβάζοντας την υπογραφή του αρχείου.

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| password | String | Ο κωδικός για το άνοιγμα του αρχείου. |
| logger | ILogger | Ο καταγραφέας. |

### Τιμή Επιστροφής

Επιστρέφει τον τύπο αρχείου σε περίπτωση που εντοπίστηκε επιτυχώς, διαφορετικά επιστρέφει τον προεπιλεγμένο τύπο αρχείου [`Unknown`](../unknown).

### Δείτε επίσης

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
