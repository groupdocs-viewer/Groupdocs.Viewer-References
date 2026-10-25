---
title: "GetViewInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες εγγράφου."
type: docs
weight: 60
url: /el/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες εγγράφου.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| options | ViewInfoOptions | Οι επιλογές πληροφοριών προβολής. |

### Τιμή Επιστροφής

Πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες εγγράφου.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *options* είναι null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |

### Παρατηρήσεις

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Δείτε επίσης

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες εγγράφου.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| options | ViewInfoOptions | Οι επιλογές πληροφοριών προβολής. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης. |

### Τιμή Επιστροφής

Πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες εγγράφου.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *options* είναι null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |

### Παρατηρήσεις

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Δείτε επίσης

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
