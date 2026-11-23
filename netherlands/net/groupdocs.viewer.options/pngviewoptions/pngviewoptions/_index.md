---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Initialiseert een instantie van de PngViewOptionsgroupdocs.viewer.options/pngviewoptions klasse."
type: docs
weight: 10
url: /nl/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

Initialiseert een instantie van de [`PngViewOptions`](../../pngviewoptions) klasse.

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die een stream instantieert die wordt gebruikt om uitvoerpagina‑gegevens te schrijven. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createPageStream* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Initialiseert een instantie van de [`PngViewOptions`](../../pngviewoptions) klasse.

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Initialiseert een instantie van de [`PngViewOptions`](../../pngviewoptions) klasse.

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoer‑pagina‑stream. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *pageStreamFactory* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Zie ook

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Initialiseert een instantie van de [`PngViewOptions`](../../pngviewoptions) klasse.

```csharp
public PngViewOptions()
```

### Opmerkingen

Deze constructor initialiseert een instantie van de [`PngViewOptions`](../../pngviewoptions) met "p_{0}.png" als bestandspadformaat voor de uitvoerbestanden. De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie.

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Zie ook

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Initialiseert een instantie van de [`PngViewOptions`](../../pngviewoptions) klasse.

```csharp
public PngViewOptions(string filePathFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | Het bestandspadformaat, bijv. 'page_{0}.png'. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid wanneer *filePathFormat* null of leeg is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Zie ook

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
