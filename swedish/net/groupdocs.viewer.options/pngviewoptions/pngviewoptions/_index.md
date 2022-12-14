---
title: PngViewOptions
second_title: GroupDocs.Viewer för .NET API-referens
description: Initierar ny instans avPngViewOptionsgroupdocs.viewer.options/pngviewoptions class.
type: docs
weight: 10
url: /sv/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---
## PngViewOptions(CreatePageStream) {#constructor_1}

Initierar ny instans av[`PngViewOptions`](../../pngviewoptions) class.

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*createPageStream* är inget. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../pngviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Initierar ny instans av[`PngViewOptions`](../../pngviewoptions) class.

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| releasePageStream | ReleasePageStream | Metoden som släpper ström skapad av metod som tilldelats delegering som skickas till*createPageStream* parameter. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*createPageStream* är inget. |
| ArgumentNullException | Kastas när*releasePageStream* är inget. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../pngviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Initierar ny instans av[`PngViewOptions`](../../pngviewoptions) class.

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabriken som implementerar metoder för att skapa och släppa utdataström. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*pageStreamFactory* är inget. |

### Se även

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../pngviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Initierar ny instans av[`PngViewOptions`](../../pngviewoptions) class.

```csharp
public PngViewOptions()
```

### Anmärkningar

Denna konstruktor initierar ny instans av[`PngViewOptions`](../../pngviewoptions) med "p_{0}.png" som filsökvägsformat för utdatafilerna. Utdatafilerna kommer att placeras i applikationens nuvarande arbetskatalog.

### Se även

* class [PngViewOptions](../../pngviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../pngviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Initierar ny instans av[`PngViewOptions`](../../pngviewoptions) class.

```csharp
public PngViewOptions(string filePathFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet, t.ex. 'page_{0}.png'. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*filePathFormat* är null eller tom. |

### Se även

* class [PngViewOptions](../../pngviewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../pngviewoptions)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
