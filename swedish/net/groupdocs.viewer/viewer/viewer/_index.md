---
title: Viewer
second_title: GroupDocs.Viewer för .NET API-referens
description: Initierar ny instans avViewergroupdocs.viewer/viewer class.
type: docs
weight: 10
url: /sv/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |
| getLoadOptions | Func`1 | Metoderna som returnerar alternativ för dokumentladdning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |
| ArgumentNullException | Kastas när*getLoadOptions* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |
| getLoadOptions | Func`1 | Metoderna som returnerar alternativ för dokumentladdning. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |
| ArgumentNullException | Kastas när*getLoadOptions* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |
| leaveOpen | Boolean | Sann att lämna strömmen öppen efter att Viewer-objektet har kasserats; annat,falsk. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |
| loadOptions | LoadOptions | Alternativen för dokumentladdning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |
| loadOptions | LoadOptions | Alternativen för dokumentladdning. |
| leaveOpen | Boolean | Sann att lämna strömmen öppen efter att Viewer-objektet har kasserats; annat,falsk. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |
| settings | ViewerSettings | Viewer-inställningarna. |
| leaveOpen | Boolean | Sann att lämna strömmen öppen efter att Viewer-objektet har kasserats; annat,falsk. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |
| loadOptions | LoadOptions | Alternativen för dokumentladdning. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Filströmmen. |
| loadOptions | LoadOptions | Alternativen för dokumentladdning. |
| settings | ViewerSettings | Viewer-inställningarna. |
| leaveOpen | Boolean | Sann att lämna strömmen öppen efter att Viewer-objektet har kasserats; annat,falsk. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*stream* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*filePath* är null eller tom. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*filePath* är null eller tom. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |
| loadOptions | LoadOptions | Alternativen som användes för att öppna filen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*filePath* är null eller tom. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initierar ny instans av[`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |
| loadOptions | LoadOptions | Alternativen som användes för att öppna filen. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*filePath* är null eller tom. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Anmärkningar

**Läs mer**

* Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mer om GroupDocs.Viewer för .NET-funktioner: [Utvecklarguide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Mer om att ladda krypterade dokument och visa filer från tredjepartslagringar med GroupDocs.Viewer för .NET: [Hur man laddar och visar dokument med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
