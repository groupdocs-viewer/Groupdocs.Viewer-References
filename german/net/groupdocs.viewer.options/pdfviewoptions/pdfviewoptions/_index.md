---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine Instanz der Klasse PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createFileStream | CreateFileStream | Die Methode, die den Stream erzeugt, der zum Schreiben von Ausgabedateidaten verwendet wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createFileStream* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Siehe auch

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createFileStream | CreateFileStream | Die Methode, die den Stream erzeugt, der zum Schreiben von Ausgabedateidaten verwendet wird. |
| releaseFileStream | ReleaseFileStream | Die Methode, die den von der Methode, die dem Delegaten zugewiesen wurde und an den Parameter *createFileStream* übergeben wurde, erstellten Stream freigibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createFileStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *releaseFileStream* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Siehe auch

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | Die Fabrik, die Methoden zum Erzeugen und Freigeben des Ausgabedateistreams implementiert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *fileStreamFactory* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Siehe auch

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions()
```

### Bemerkungen

Dieser Konstruktor initialisiert eine Instanz von [`PdfViewOptions`](../../pdfviewoptions) mit "output.pdf" als Dateipfadformat für die Ausgabedatei. Die Ausgabedatei wird im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Siehe auch

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Initialisiert eine Instanz der Klasse [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(string outputFilePath)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| outputFilePath | String | Der Pfad für die Ausgabedatei im PDF-Format. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *outputFilePath* null oder leer ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Siehe auch

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
