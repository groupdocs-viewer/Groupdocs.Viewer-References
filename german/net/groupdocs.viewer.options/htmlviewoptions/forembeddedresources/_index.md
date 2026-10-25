---
title: "ForEmbeddedResources"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine Instanz der HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions-Klasse zum Rendern in HTML mit eingebetteten Ressourcen."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream erstellt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |

### Rückgabewert

Neue Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createPageStream* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream erstellt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
| releasePageStream | ReleasePageStream | Die Methode, die den von der dem Delegaten zugewiesenen Methode erstellten Stream freigibt, die an den Parameter *createPageStream* übergeben wurde. |

### Rückgabewert

Neue Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createPageStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *releasePageStream* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten‑Streams implementiert. |

### Rückgabewert

Neue Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern in HTML mit eingebetteten Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *pageStreamFactory* null ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Siehe auch

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse.

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse.

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat, z. B. 'page_{0}.html'. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *filePathFormat* null oder leer ist. |

### Bemerkungen

Für das Codebeispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
