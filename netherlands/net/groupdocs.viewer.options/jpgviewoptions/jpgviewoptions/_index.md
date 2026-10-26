---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Initialiseert een instantie van de JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions klasse."
type: docs
weight: 10
url: /nl/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

Initialiseert een instantie van de [`JpgViewOptions`](../../jpgviewoptions) klasse.

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die een stream instantieert die wordt gebruikt om uitvoerpagina‑gegevens te schrijven. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createPageStream* null is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Initialiseert een instantie van de [`JpgViewOptions`](../../jpgviewoptions) klasse.

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die een stream instantieert die wordt gebruikt om uitvoerpagina‑gegevens te schrijven. |
| releasePageStream | ReleasePageStream | De methode die een stream vrijgeeft die is gemaakt door een methode toegewezen aan de delegate die is doorgegeven aan de *createPageStream* parameter. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createPageStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *releasePageStream* null is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

Initialiseert een instantie van de [`JpgViewOptions`](../../jpgviewoptions) klasse.

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoer‑pagina‑stream. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *pageStreamFactory* null is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Zie ook

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

Initialiseert een instantie van de [`JpgViewOptions`](../../jpgviewoptions) klasse.

```csharp
public JpgViewOptions()
```

### Opmerkingen

Deze constructor initialiseert een instantie van de [`JpgViewOptions`](../../jpgviewoptions) met "p_{0}.jpg" als bestandsnaamformaat voor de uitvoerbestanden. De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie.

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Zie ook

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

Initialiseert een instantie van de [`JpgViewOptions`](../../jpgviewoptions) klasse.

```csharp
public JpgViewOptions(string filePathFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | Het bestandsnaamformaat bijv. 'page_{0}.jpg'. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid wanneer *filePathFormat* null of leeg is. |

### Opmerkingen

Voor het codevoorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Zie ook

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
