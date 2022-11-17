---
title: ForExternalResources
second_title: GroupDocs.Viewer för .NET API-referens
description: Initierar ny instans avHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions klass för rendering till HTML med externa resurser.
type: docs
weight: 20
url: /sv/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initierar ny instans av[`HtmlViewOptions`](../../htmlviewoptions) klass för rendering till HTML med externa resurser.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| createResourceStream | CreateResourceStream | Metoden som släpper stream skapad av*createPageStream* metod. |
| createResourceUrl | CreateResourceUrl | Metoden som skapar URL för HTML-resurs. |

### Returvärde

Ny instans av[`HtmlViewOptions`](../../htmlviewoptions) klass för rendering till HTML med externa resurser.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*createPageStream* är inget. |
| ArgumentNullException | Kastas när*createResourceStream* är inget. |
| ArgumentNullException | Kastas när*createResourceUrl* är inget. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../htmlviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initierar ny instans av[`HtmlViewOptions`](../../htmlviewoptions) klass för rendering till HTML med externa resurser.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| createResourceStream | CreateResourceStream | Metoden som instansierar ström som används för att skriva utgående HTML-resursdata. |
| createResourceUrl | CreateResourceUrl | Metoden som skapar URL för HTML-resurs. |
| releasePageStream | ReleasePageStream | Metoden som släpper ström skapad av metod som tilldelats delegering som skickas till*createPageStream* parameter. |
| releaseResourceStream | ReleaseResourceStream | Metoden som släpper ström skapad av metod som tilldelats delegering som skickas till*createResourceStream* parameter. |

### Returvärde

Ny instans av[`HtmlViewOptions`](../../htmlviewoptions) klass för rendering till HTML med externa resurser.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*createPageStream* är inget. |
| ArgumentNullException | Kastas när*createResourceStream* är inget. |
| ArgumentNullException | Kastas när*createResourceUrl* är inget. |
| ArgumentNullException | Kastas när*releasePageStream* är inget. |
| ArgumentNullException | Kastas när*releaseResourceStream* är inget. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../htmlviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Initierar ny instans av[`HtmlViewOptions`](../../htmlviewoptions) klass för rendering till HTML med externa resurser.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabriken som implementerar metoder för att skapa och släppa utdataström. |
| resourceStreamFactory | IResourceStreamFactory | Fabriken som implementerar metoder som krävs för att skapa resurs-URL, instansiera och släppa ut HTML-resursström. |

### Returvärde

Ny instans av[`HtmlViewOptions`](../../htmlviewoptions) klass för rendering till HTML med externa resurser.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*pageStreamFactory* är inget. |
| ArgumentNullException | Kastas när*resourceStreamFactory* är inget. |

### Se även

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../htmlviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initierar ny instans av[`HtmlViewOptions`](../../htmlviewoptions) class.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Anmärkningar

Denna konstruktor initierar ny instans av[`HtmlViewOptions`](../../htmlviewoptions) - med "p_{0}.html" som filsökvägsformat för utdata-HTML-filerna; - med "p_{0}_{1}" som filsökvägsformat för utdata-HTML-resursfilerna; - med " p_{0}_{1}" som URL-format för HTML-resurser; Utdatafilerna kommer att placeras i applikationens aktuella arbetskatalog.

### Se även

* class [HtmlViewOptions](../../htmlviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../htmlviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initierar ny instans av[`HtmlViewOptions`](../../htmlviewoptions) class.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet, t.ex. 'page_{0}.html'. |
| resourceFilePathFormat | String | Resursfilens sökvägsformat t.ex. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Resurs-URL-formatet, t.ex. 'page_{0}/resource_{1}'. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*filePathFormat* är null eller tom. |
| ArgumentException | Kastas när*resourceFilePathFormat* är null eller tom. |
| ArgumentException | Kastas när*resourceUrlFormat* är null eller tom. |

### Se även

* class [HtmlViewOptions](../../htmlviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../htmlviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
