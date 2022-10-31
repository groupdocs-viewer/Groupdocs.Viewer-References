---
title: Viewer
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonViewergroupdocs.viewer/viewer Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*getFileStream* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| getLoadOptions | Func`1 | Die Methoden, die Dokumentladeoptionen zurückgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*getFileStream* ist Null. |
| ArgumentNullException | Wann geworfen*getLoadOptions* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*getFileStream* ist Null. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| getLoadOptions | Func`1 | Die Methoden, die Dokumentladeoptionen zurückgeben. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*getFileStream* ist Null. |
| ArgumentNullException | Wann geworfen*getLoadOptions* ist Null. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |
| leaveOpen | Boolean | Stimmt um den Stream offen zu lassen, nachdem das Viewer-Objekt verworfen wurde; Andernfalls,FALSCH. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Optionen zum Laden von Dokumenten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |
| ArgumentNullException | Wann geworfen*loadOptions* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Optionen zum Laden von Dokumenten. |
| leaveOpen | Boolean | Stimmt um den Stream offen zu lassen, nachdem das Viewer-Objekt verworfen wurde; Andernfalls,FALSCH. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |
| ArgumentNullException | Wann geworfen*loadOptions* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |
| leaveOpen | Boolean | Stimmt um den Stream offen zu lassen, nachdem das Viewer-Objekt verworfen wurde; Andernfalls,FALSCH. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Optionen zum Laden von Dokumenten. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |
| ArgumentNullException | Wann geworfen*loadOptions* ist Null. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Optionen zum Laden von Dokumenten. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |
| leaveOpen | Boolean | Stimmt um den Stream offen zu lassen, nachdem das Viewer-Objekt verworfen wurde; Andernfalls,FALSCH. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*stream* ist Null. |
| ArgumentNullException | Wann geworfen*loadOptions* ist Null. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zu der zu rendernden Datei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*filePath* ist null oder leer. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zu der zu rendernden Datei. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*filePath* ist null oder leer. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zu der zu rendernden Datei. |
| loadOptions | LoadOptions | Die Optionen, die zum Öffnen der Datei verwendet wurden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*filePath* ist null oder leer. |
| ArgumentNullException | Wann geworfen*loadOptions* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initialisiert eine neue Instanz von[`Viewer`](../../viewer) Klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zu der zu rendernden Datei. |
| loadOptions | LoadOptions | Die Optionen, die zum Öffnen der Datei verwendet wurden. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*filePath* ist null oder leer. |
| ArgumentNullException | Wann geworfen*loadOptions* ist Null. |
| ArgumentNullException | Wann geworfen*settings* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Mehr zu den von GroupDocs.Viewer unterstützten Dateitypen: [Von GroupDocs.Viewer unterstützte Dokumentformate](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Mehr über GroupDocs.Viewer für .NET-Funktionen: [Entwicklerhandbuch](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Weitere Informationen zum Laden verschlüsselter Dokumente und Anzeigen von Dateien aus Drittanbieterspeichern mit GroupDocs.Viewer für .NET: [So laden und betrachten Sie Dokumente mit GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
