---
title: "ForEmbeddedResources"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Initierar en instans av HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions‑klassen för rendering till HTML med inbäddade resurser."
type: docs
weight: 10
url: /sv/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Initierar en instans av [`HtmlViewOptions`](../../htmlviewoptions)-klassen för rendering till HTML med inbäddade resurser.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar strömmen som används för att skriva utdata siddata. |

### Returvärde

Ny instans av [`HtmlViewOptions`](../../htmlviewoptions)-klassen för rendering till HTML med inbäddade resurser.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *createPageStream* är null. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Se även

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Initierar en instans av [`HtmlViewOptions`](../../htmlviewoptions)-klassen för rendering till HTML med inbäddade resurser.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| releasePageStream | ReleasePageStream | Metoden som frigör strömmen som skapats av metoden tilldelad delegaten som skickades till parametern *createPageStream*. |

### Returvärde

Ny instans av [`HtmlViewOptions`](../../htmlviewoptions)-klassen för rendering till HTML med inbäddade resurser.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *createPageStream* är null. |
| ArgumentNullException | Kastas när *releasePageStream* är null. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Se även

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Initierar en instans av [`HtmlViewOptions`](../../htmlviewoptions)-klassen för rendering till HTML med inbäddade resurser.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabriken som implementerar metoder för att skapa och frigöra utdata‑sidström. |

### Returvärde

Ny instans av [`HtmlViewOptions`](../../htmlviewoptions)-klassen för rendering till HTML med inbäddade resurser.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *pageStreamFactory* är null. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Se även

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Initierar en instans av klassen [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Se även

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Initierar en instans av klassen [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filens sökvägsformat, t.ex. 'page_{0}.html'. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *filePathFormat* är null eller tom. |

### Anmärkningar

För kodexemplet, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Se även

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
