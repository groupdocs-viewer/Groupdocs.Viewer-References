---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine Instanz der HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions-Klasse für das Rendern in HTML mit externen Ressourcen."
type: docs
weight: 20
url: /de/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse für das Rendern in HTML mit externen Ressourcen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream erstellt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
| createResourceStream | CreateResourceStream | Die Methode, die den von *createPageStream*-Methode erstellten Stream freigibt. |
| createResourceUrl | CreateResourceUrl | Die Methode, die eine URL für die HTML‑Ressource erstellt. |

### Rückgabewert

Neue Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern von HTML mit externen Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createPageStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *createResourceStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *createResourceUrl* null ist. |

### Bemerkungen

Für das Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse für das Rendern in HTML mit externen Ressourcen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream erstellt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
| createResourceStream | CreateResourceStream | Die Methode, die den Stream instanziiert, der zum Schreiben der Ausgabedaten der HTML‑Ressource verwendet wird. |
| createResourceUrl | CreateResourceUrl | Die Methode, die eine URL für die HTML‑Ressource erstellt. |
| releasePageStream | ReleasePageStream | Die Methode, die den von der dem Delegaten zugewiesenen Methode erstellten Stream freigibt, die an den Parameter *createPageStream* übergeben wurde. |
| releaseResourceStream | ReleaseResourceStream | Die Methode, die den von der dem Delegaten zugewiesenen Methode erstellten Stream freigibt, die an den Parameter *createResourceStream* übergeben wurde. |

### Rückgabewert

Neue Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern von HTML mit externen Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *createPageStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *createResourceStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *createResourceUrl* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *releasePageStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *releaseResourceStream* null ist. |

### Bemerkungen

Für das Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Siehe auch

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

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse für das Rendern in HTML mit externen Ressourcen.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten‑Streams implementiert. |
| resourceStreamFactory | IResourceStreamFactory | Die Fabrik, die Methoden implementiert, die zum Erstellen der Ressourcen‑URL, zum Instanziieren und Freigeben des Ausgabestreams der HTML‑Ressource erforderlich sind. |

### Rückgabewert

Neue Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse zum Rendern von HTML mit externen Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *pageStreamFactory* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *resourceStreamFactory* null ist. |

### Bemerkungen

Für das Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Siehe auch

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Bemerkungen

Dieser Konstruktor initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.

Für das Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initialisiert eine Instanz der [`HtmlViewOptions`](../../htmlviewoptions)-Klasse.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat, z. B. 'page_{0}.html'. |
| resourceFilePathFormat | String | Das Ressourcen-Dateipfadformat z. B. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Das Ressourcen-URL-Format z. B. 'page_{0}/resource_{1}'. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *filePathFormat* null oder leer ist. |
| ArgumentException | Wird ausgelöst, wenn *resourceFilePathFormat* null oder leer ist. |
| ArgumentException | Wird ausgelöst, wenn *resourceUrlFormat* null oder leer ist. |

### Bemerkungen

Für das Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
