---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Initialiseert een instantie van de HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions‑klasse voor het renderen naar HTML met externe bronnen."
type: docs
weight: 20
url: /nl/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions)‑klasse voor het renderen naar HTML met externe bronnen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die de stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |
| createResourceStream | CreateResourceStream | De methode die de stream vrijgeeft die is aangemaakt door de *createPageStream*‑methode. |
| createResourceUrl | CreateResourceUrl | De methode die een URL voor een HTML-resource maakt. |

### Retourwaarde

Nieuwe instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met externe resources.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createPageStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *createResourceStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *createResourceUrl* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions)‑klasse voor het renderen naar HTML met externe bronnen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die de stream instantieert die wordt gebruikt om uitvoer‑pagedata te schrijven. |
| createResourceStream | CreateResourceStream | De methode die de stream maakt die wordt gebruikt om de uitvoer‑HTML‑resourcegegevens te schrijven. |
| createResourceUrl | CreateResourceUrl | De methode die een URL voor een HTML-resource maakt. |
| releasePageStream | ReleasePageStream | De methode die de stream vrijgeeft die is aangemaakt door de methode die aan de delegate is toegewezen die werd doorgegeven aan de *createPageStream*‑parameter. |
| releaseResourceStream | ReleaseResourceStream | De methode die de stream vrijgeeft die is aangemaakt door de methode die aan de delegate is toegewezen die werd doorgegeven aan de *createResourceStream*‑parameter. |

### Retourwaarde

Nieuwe instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met externe resources.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *createPageStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *createResourceStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *createResourceUrl* null is. |
| ArgumentNullException | Wordt gegooid wanneer *releasePageStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *releaseResourceStream* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions)‑klasse voor het renderen naar HTML met externe bronnen.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoer‑pagina‑stream. |
| resourceStreamFactory | IResourceStreamFactory | De fabriek die methoden implementeert die nodig zijn voor het maken van een resource‑URL, het instantieren en vrijgeven van de uitvoer‑HTML‑resource‑stream. |

### Retourwaarde

Nieuwe instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse voor het renderen naar HTML met externe resources.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *pageStreamFactory* null is. |
| ArgumentNullException | Wordt gegooid wanneer *resourceStreamFactory* null is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Zie ook

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Opmerkingen

Deze constructor initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions)

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie.

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Zie ook

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initialiseert een instantie van de [`HtmlViewOptions`](../../htmlviewoptions) klasse.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | Het bestandspadformaat bijv. 'page_{0}.html'. |
| resourceFilePathFormat | String | Het resource‑bestandspadformaat, bijv. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Het resource‑URL‑formaat, bijv. 'page_{0}/resource_{1}'. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid wanneer *filePathFormat* null of leeg is. |
| ArgumentException | Wordt opgegooid wanneer *resourceFilePathFormat* null of leeg is. |
| ArgumentException | Wordt opgegooid wanneer *resourceUrlFormat* null of leeg is. |

### Opmerkingen

Voor het code‑voorbeeld, zie de [documentatie](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Zie ook

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
