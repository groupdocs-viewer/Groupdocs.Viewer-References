---
title: ForExternalResources
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions Klasse zum Rendern in HTML mit externen Ressourcen.
type: docs
weight: 20
url: /de/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initialisiert eine neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| createResourceStream | CreateResourceStream | Die Methode, die den von erstellten Stream freigibt*createPageStream* Methode. |
| createResourceUrl | CreateResourceUrl | Die Methode, die eine URL für eine HTML-Ressource erstellt. |

### Rückgabewert

Neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*createPageStream* ist Null. |
| ArgumentNullException | Wann geworfen*createResourceStream* ist Null. |
| ArgumentNullException | Wann geworfen*createResourceUrl* ist Null. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namensraum [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initialisiert eine neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| createResourceStream | CreateResourceStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabe-HTML-Ressourcendaten verwendet wird. |
| createResourceUrl | CreateResourceUrl | Die Methode, die eine URL für eine HTML-Ressource erstellt. |
| releasePageStream | ReleasePageStream | Die Methode, die den Stream freigibt, der von der Methode erstellt wurde, die dem Delegaten zugewiesen wurde, an den übergeben wurde*createPageStream* Parameter. |
| releaseResourceStream | ReleaseResourceStream | Die Methode, die den Stream freigibt, der von der Methode erstellt wurde, die dem Delegaten zugewiesen wurde, an den übergeben wurde*createResourceStream* Parameter. |

### Rückgabewert

Neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*createPageStream* ist Null. |
| ArgumentNullException | Wann geworfen*createResourceStream* ist Null. |
| ArgumentNullException | Wann geworfen*createResourceUrl* ist Null. |
| ArgumentNullException | Wann geworfen*releasePageStream* ist Null. |
| ArgumentNullException | Wann geworfen*releaseResourceStream* ist Null. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namensraum [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Initialisiert eine neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Die Factory, die Methoden zum Erstellen und Freigeben des Ausgabeseitenstroms implementiert. |
| resourceStreamFactory | IResourceStreamFactory | Die Factory, die Methoden implementiert, die zum Erstellen von Ressourcen-URLs, Instanziieren und Freigeben von Ausgabe-HTML-Ressourcenstreams erforderlich sind. |

### Rückgabewert

Neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse zum Rendern in HTML mit externen Ressourcen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*pageStreamFactory* ist Null. |
| ArgumentNullException | Wann geworfen*resourceStreamFactory* ist Null. |

### Siehe auch

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namensraum [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initialisiert eine neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Bemerkungen

Dieser Konstruktor initialisiert eine neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) - mit "p_{0}.html" als Dateipfadformat für die ausgegebenen HTML-Dateien; - mit "p_{0}_{1}" als Dateipfadformat für die ausgegebenen HTML-Ressourcendateien; - mit " p_{0}_{1}" als URL-Format für HTML-Ressourcen; Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namensraum [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Montage [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initialisiert eine neue Instanz von[`HtmlViewOptions`](../../htmlviewoptions) Klasse.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat zB 'page_{0}.html'. |
| resourceFilePathFormat | String | Das Pfadformat der Ressourcendatei, z. B. „page_{0}/resource_{1}“. |
| resourceUrlFormat | String | Das Ressourcen-URL-Format, z. B. „page_{0}/resource_{1}“. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*filePathFormat* ist null oder leer. |
| ArgumentException | Wann geworfen*resourceFilePathFormat* ist null oder leer. |
| ArgumentException | Wann geworfen*resourceUrlFormat* ist null oder leer. |

### Siehe auch

* class [HtmlViewOptions](../../htmlviewoptions)
* namensraum [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
