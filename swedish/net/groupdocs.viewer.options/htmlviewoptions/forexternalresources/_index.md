---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Initierar en instans av klassen HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions för rendering till HTML med externa resurser."
type: docs
weight: 20
url: /sv/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initierar en instans av [`HtmlViewOptions`](../../htmlviewoptions) klassen för rendering till HTML med externa resurser.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| createResourceStream | CreateResourceStream | Metoden som frigör strömmen som skapats av *createPageStream*-metoden. |
| createResourceUrl | CreateResourceUrl | Metoden som skapar URL för HTML-resurs. |

### Returvärde

Ny instans av klassen [`HtmlViewOptions`](../../htmlviewoptions) för rendering till HTML med externa resurser.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *createPageStream* är null. |
| ArgumentNullException | Kastas när *createResourceStream* är null. |
| ArgumentNullException | Kastas när *createResourceUrl* är null. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Se även

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initierar en instans av [`HtmlViewOptions`](../../htmlviewoptions) klassen för rendering till HTML med externa resurser.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| createResourceStream | CreateResourceStream | Metoden som instansierar strömmen som används för att skriva utdata‑HTML‑resursdata. |
| createResourceUrl | CreateResourceUrl | Metoden som skapar URL för HTML-resurs. |
| releasePageStream | ReleasePageStream | Metoden som frigör strömmen som skapats av metoden tilldelad delegaten som skickades till parametern *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | Metoden som frigör strömmen som skapats av metoden tilldelad delegaten som skickades till parametern *createResourceStream*. |

### Returvärde

Ny instans av klassen [`HtmlViewOptions`](../../htmlviewoptions) för rendering till HTML med externa resurser.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *createPageStream* är null. |
| ArgumentNullException | Kastas när *createResourceStream* är null. |
| ArgumentNullException | Kastas när *createResourceUrl* är null. |
| ArgumentNullException | Kastas när *releasePageStream* är null. |
| ArgumentNullException | Kastas när *releaseResourceStream* är null. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Se även

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

Initierar en instans av [`HtmlViewOptions`](../../htmlviewoptions) klassen för rendering till HTML med externa resurser.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabriken som implementerar metoder för att skapa och frigöra utdata‑sidström. |
| resourceStreamFactory | IResourceStreamFactory | Fabriken som implementerar metoder som krävs för att skapa resurs‑URL, instansiera och frigöra utdata‑HTML‑resursström. |

### Returvärde

Ny instans av klassen [`HtmlViewOptions`](../../htmlviewoptions) för rendering till HTML med externa resurser.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *pageStreamFactory* är null. |
| ArgumentNullException | Kastas när *resourceStreamFactory* är null. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Se även

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initierar en instans av klassen [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Anmärkningar

Denna konstruktor initierar en instans av [`HtmlViewOptions`](../../htmlviewoptions)

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

Utdatafilerna kommer att placeras i applikationens aktuella arbetskatalog.

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Se även

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initierar en instans av klassen [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filens sökvägsformat, t.ex. 'page_{0}.html'. |
| resourceFilePathFormat | String | Resursfilens sökvägsformat, t.ex. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Resurs‑URL‑formatet t.ex. 'page_{0}/resource_{1}'. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *filePathFormat* är null eller tom. |
| ArgumentException | Kastas när *resourceFilePathFormat* är null eller tom. |
| ArgumentException | Kastas när *resourceUrlFormat* är null eller tom. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Se även

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
