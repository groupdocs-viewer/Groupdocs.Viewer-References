---
title: Viewer
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Initialiseert nieuw exemplaar vanViewergroupdocs.viewer/viewer klasse.
type: docs
weight: 10
url: /nl/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| getLoadOptions | Func`1 | De methoden die opties voor het laden van documenten retourneren. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |
| ArgumentNullException | Wanneer gegooid*getLoadOptions* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| getLoadOptions | Func`1 | De methoden die opties voor het laden van documenten retourneren. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |
| ArgumentNullException | Wanneer gegooid*getLoadOptions* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |
| leaveOpen | Boolean | WAAR om de stream open te laten nadat het Viewer-object is weggegooid; anders,vals. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |
| loadOptions | LoadOptions | De opties voor het laden van documenten. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |
| loadOptions | LoadOptions | De opties voor het laden van documenten. |
| leaveOpen | Boolean | WAAR om de stream open te laten nadat het Viewer-object is weggegooid; anders,vals. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |
| settings | ViewerSettings | De Viewer-instellingen. |
| leaveOpen | Boolean | WAAR om de stream open te laten nadat het Viewer-object is weggegooid; anders,vals. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |
| loadOptions | LoadOptions | De opties voor het laden van documenten. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestandsstroom. |
| loadOptions | LoadOptions | De opties voor het laden van documenten. |
| settings | ViewerSettings | De Viewer-instellingen. |
| leaveOpen | Boolean | WAAR om de stream open te laten nadat het Viewer-object is weggegooid; anders,vals. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*stream* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand dat moet worden weergegeven. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*filePath* is null of leeg. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand dat moet worden weergegeven. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*filePath* is null of leeg. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand dat moet worden weergegeven. |
| loadOptions | LoadOptions | De opties waarmee het bestand werd geopend. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*filePath* is null of leeg. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initialiseert nieuw exemplaar van[`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand dat moet worden weergegeven. |
| loadOptions | LoadOptions | De opties waarmee het bestand werd geopend. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*filePath* is null of leeg. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer over bestandstypen die worden ondersteund door GroupDocs.Viewer: [Documentformaten ondersteund door GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Meer over GroupDocs.Viewer voor .NET-functies: [Handleiding voor ontwikkelaars](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Meer over het laden van versleutelde documenten en het bekijken van bestanden uit opslag van derden met GroupDocs.Viewer voor .NET: [Documenten laden en bekijken met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
