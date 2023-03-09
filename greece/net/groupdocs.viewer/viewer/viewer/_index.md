---
title: Viewer
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Αρχικοποιεί νέα παρουσία τουViewergroupdocs.viewer/viewer τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| getLoadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*getLoadOptions* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| getLoadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν τις επιλογές φόρτωσης εγγράφου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*getLoadOptions* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |
| leaveOpen | Boolean | αληθής να αφήσετε τη ροή ανοιχτή μετά την απόρριψη του αντικειμένου Viewer. σε διαφορετική περίπτωση,ψευδής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| leaveOpen | Boolean | αληθής να αφήσετε τη ροή ανοιχτή μετά την απόρριψη του αντικειμένου Viewer. σε διαφορετική περίπτωση,ψευδής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |
| leaveOpen | Boolean | αληθής να αφήσετε τη ροή ανοιχτή μετά την απόρριψη του αντικειμένου Viewer. σε διαφορετική περίπτωση,ψευδής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή του αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |
| leaveOpen | Boolean | αληθής να αφήσετε τη ροή ανοιχτή μετά την απόρριψη του αντικειμένου Viewer. σε διαφορετική περίπτωση,ψευδής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*stream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο προς απόδοση. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο προς απόδοση. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο προς απόδοση. |
| loadOptions | LoadOptions | Οι επιλογές που χρησιμοποιήθηκαν για το άνοιγμα του αρχείου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Αρχικοποιεί νέα παρουσία του[`Viewer`](../../viewer) τάξη.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο προς απόδοση. |
| loadOptions | LoadOptions | Οι επιλογές που χρησιμοποιήθηκαν για το άνοιγμα του αρχείου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Viewer για δυνατότητες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Περισσότερα σχετικά με τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: [Τρόπος φόρτωσης και προβολής εγγράφου με το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
