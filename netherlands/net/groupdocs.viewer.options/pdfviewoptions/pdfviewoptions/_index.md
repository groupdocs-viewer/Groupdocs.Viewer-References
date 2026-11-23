---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Initialiseert een instantie van de PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions-klasse."
type: docs
weight: 10
url: /nl/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

Initialiseert een instantie van de [`PdfViewOptions`](../../pdfviewoptions)-klasse.

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createFileStream | CreateFileStream | De methode die de stream instantieert die wordt gebruikt om uitvoerbestandsgegevens te schrijven. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createFileStream* null is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Zie ook

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Initialiseert een instantie van de [`PdfViewOptions`](../../pdfviewoptions)-klasse.

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createFileStream | CreateFileStream | De methode die de stream instantieert die wordt gebruikt om uitvoerbestandsgegevens te schrijven. |
| releaseFileStream | ReleaseFileStream | De methode die de stream vrijgeeft die is gemaakt door de methode die is toegewezen aan de delegate die is doorgegeven aan de *createFileStream*-parameter. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createFileStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *releaseFileStream* null is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Zie ook

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Initialiseert een instantie van de [`PdfViewOptions`](../../pdfviewoptions)-klasse.

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | De fabriek die methoden implementeert voor het maken en vrijgeven van de output‑bestandstroom. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *fileStreamFactory* null is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Zie ook

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Initialiseert een instantie van de [`PdfViewOptions`](../../pdfviewoptions)-klasse.

```csharp
public PdfViewOptions()
```

### Opmerkingen

Deze constructor initialiseert een instantie van [`PdfViewOptions`](../../pdfviewoptions) met "output.pdf" als bestandspadformaat voor het uitvoerbestand. Het uitvoerbestand wordt geplaatst in de huidige werkmap van de applicatie.

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Zie ook

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Initialiseert een instantie van de [`PdfViewOptions`](../../pdfviewoptions)-klasse.

```csharp
public PdfViewOptions(string outputFilePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| outputFilePath | String | Het pad voor het uitvoer‑PDF‑bestand. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer *outputFilePath* null of leeg is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Zie ook

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
