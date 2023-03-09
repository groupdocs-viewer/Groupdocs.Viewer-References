---
title: ForExternalResources
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Initialiseert nieuw exemplaar vanHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions klasse voor weergave in HTML met externe bronnen.
type: docs
weight: 20
url: /nl/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse voor weergave in HTML met externe bronnen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die stream instantiseert die wordt gebruikt om uitvoerpaginagegevens te schrijven. |
| createResourceStream | CreateResourceStream | De methode die stream vrijgeeft die is gemaakt door*createPageStream* methode. |
| createResourceUrl | CreateResourceUrl | De methode die een URL maakt voor een HTML-bron. |

### Winstwaarde

Nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse voor weergave in HTML met externe bronnen.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*createPageStream* is niets. |
| ArgumentNullException | Wanneer gegooid*createResourceStream* is niets. |
| ArgumentNullException | Wanneer gegooid*createResourceUrl* is niets. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* naamruimte [GroupDocs.Viewer.Options](../../htmlviewoptions)
* montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse voor weergave in HTML met externe bronnen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | De methode die stream instantiseert die wordt gebruikt om uitvoerpaginagegevens te schrijven. |
| createResourceStream | CreateResourceStream | De methode die stream instantiseert die wordt gebruikt om uitvoer-HTML-resourcegegevens te schrijven. |
| createResourceUrl | CreateResourceUrl | De methode die een URL maakt voor een HTML-bron. |
| releasePageStream | ReleasePageStream | De methode die een stream vrijgeeft die is gemaakt door een methode die is toegewezen aan delegeren en waaraan is doorgegeven*createPageStream* parameter. |
| releaseResourceStream | ReleaseResourceStream | De methode die een stream vrijgeeft die is gemaakt door een methode die is toegewezen aan delegeren en waaraan is doorgegeven*createResourceStream* parameter. |

### Winstwaarde

Nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse voor weergave in HTML met externe bronnen.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*createPageStream* is niets. |
| ArgumentNullException | Wanneer gegooid*createResourceStream* is niets. |
| ArgumentNullException | Wanneer gegooid*createResourceUrl* is niets. |
| ArgumentNullException | Wanneer gegooid*releasePageStream* is niets. |
| ArgumentNullException | Wanneer gegooid*releaseResourceStream* is niets. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* naamruimte [GroupDocs.Viewer.Options](../../htmlviewoptions)
* montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse voor weergave in HTML met externe bronnen.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | De fabriek die methoden implementeert voor het maken en vrijgeven van uitvoerpaginastreams. |
| resourceStreamFactory | IResourceStreamFactory | De fabriek die methoden implementeert die vereist zijn voor het maken van een bron-URL, het instantiëren en vrijgeven van de uitvoer-HTML-bronstroom. |

### Winstwaarde

Nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse voor weergave in HTML met externe bronnen.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*pageStreamFactory* is niets. |
| ArgumentNullException | Wanneer gegooid*resourceStreamFactory* is niets. |

### Zie ook

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* naamruimte [GroupDocs.Viewer.Options](../../htmlviewoptions)
* montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Opmerkingen

Deze constructor initialiseert een nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) - met "p_{0}.html" als bestandspadindeling voor de HTML-uitvoerbestanden; - met "p_{0}_{1}" als bestandspadindeling voor de uitvoer HTML-bronbestanden; - met " p_{0}_{1}" als URL-formaat voor HTML-resources; De uitvoerbestanden worden in de huidige werkmap van de toepassing geplaatst.

### Zie ook

* class [HtmlViewOptions](../../htmlviewoptions)
* naamruimte [GroupDocs.Viewer.Options](../../htmlviewoptions)
* montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initialiseert nieuw exemplaar van[`HtmlViewOptions`](../../htmlviewoptions) klasse.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | De indeling van het bestandspad, bijvoorbeeld 'page_{0}.html'. |
| resourceFilePathFormat | String | De indeling van het pad naar het bronbestand, bijvoorbeeld 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | De indeling van de resource-URL, bijvoorbeeld 'page_{0}/resource_{1}'. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*filePathFormat* is null of leeg. |
| ArgumentException | Wanneer gegooid*resourceFilePathFormat* is null of leeg. |
| ArgumentException | Wanneer gegooid*resourceUrlFormat* is null of leeg. |

### Zie ook

* class [HtmlViewOptions](../../htmlviewoptions)
* naamruimte [GroupDocs.Viewer.Options](../../htmlviewoptions)
* montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
