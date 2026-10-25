---
title: "Προβολέας"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί νέα παρουσία της κλάσης Viewergroupdocs.viewer/viewer."
type: docs
weight: 10
url: /el/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *getFileStream* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| getLoadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *getFileStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *getLoadOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *getFileStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| getLoadOptions | Func`1 | Οι μέθοδοι που επιστρέφουν επιλογές φόρτωσης εγγράφου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *getFileStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *getLoadOptions* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| leaveOpen | Boolean | αληθές για να αφήσετε τη ροή ανοιχτή μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, ψευδές. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *loadOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| leaveOpen | Boolean | αληθές για να αφήσετε τη ροή ανοιχτή μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, ψευδές. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *loadOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |
| leaveOpen | Boolean | αληθές για να αφήσετε τη ροή ανοιχτή μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, ψευδές. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *loadOptions* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή αρχείου. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |
| leaveOpen | Boolean | αληθές για να αφήσετε τη ροή ανοιχτή μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, ψευδές. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *stream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *loadOptions* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο για απόδοση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *filePath* είναι null ή κενό. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο για απόδοση. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Δείτε επίσης

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο για απόδοση. |
| loadOptions | LoadOptions | Οι επιλογές που χρησιμοποιούνται για το άνοιγμα του αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν το *loadOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή προς το αρχείο για απόδοση. |
| loadOptions | LoadOptions | Οι επιλογές που χρησιμοποιούνται για το άνοιγμα του αρχείου. |
| settings | ViewerSettings | Οι ρυθμίσεις του Viewer. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν το *loadOptions* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *settings* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Δείτε επίσης

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
