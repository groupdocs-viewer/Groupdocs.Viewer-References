---
title: "ForEmbeddedResources"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Initialiseert een instantie van de HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions klasse voor het renderen naar HTML met ingebedde bronnen."
type: docs
weight: 10
url: /nl/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde bronnen.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die de stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |

### Retourwaarde

Nieuwe instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde bronnen.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createPageStream* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde bronnen.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die de stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |
| releasePageStream | ReleasePageStream | De methode die de stream vrijgeeft die is aangemaakt door de methode die aan de delegate is toegewezen die werd doorgegeven aan de *createPageStream*‑parameter. |

### Retourwaarde

Nieuwe instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde bronnen.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createPageStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *releasePageStream* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde bronnen.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoer‑pagina‑stream. |

### Retourwaarde

Nieuwe instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met ingebedde bronnen.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *pageStreamFactory* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Zie ook

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse.

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Zie ook

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse.

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | Het bestandspadformaat bijv. 'page_{0}.html'. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid wanneer *filePathFormat* null of leeg is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Zie ook

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
