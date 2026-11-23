---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine Instanz der PngViewOptionsgroupdocs.viewer.options/pngviewoptions-Klasse."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

Initialisiert eine Instanz der [`PngViewOptions`](../../pngviewoptions)-Klasse.

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die einen Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createPageStream* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Initialisiert eine Instanz der [`PngViewOptions`](../../pngviewoptions)-Klasse.

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die einen Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| releasePageStream | ReleasePageStream | Die Methode, die einen Stream freigibt, der von einer Methode erstellt wurde, die dem Delegaten zugewiesen wurde, der an den Parameter *createPageStream* übergeben wurde. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createPageStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *releasePageStream* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Initialisiert eine Instanz der [`PngViewOptions`](../../pngviewoptions)-Klasse.

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten‑Streams implementiert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *pageStreamFactory* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Siehe auch

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Initialisiert eine Instanz der [`PngViewOptions`](../../pngviewoptions)-Klasse.

```csharp
public PngViewOptions()
```

### Bemerkungen

Dieser Konstruktor initialisiert eine Instanz der [`PngViewOptions`](../../pngviewoptions) mit "p_{0}.png" als Dateipfadformat für die Ausgabedateien. Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Siehe auch

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Initialisiert eine Instanz der [`PngViewOptions`](../../pngviewoptions)-Klasse.

```csharp
public PngViewOptions(string filePathFormat)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat z. B. 'page_{0}.png'. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *filePathFormat* null oder leer ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Siehe auch

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
