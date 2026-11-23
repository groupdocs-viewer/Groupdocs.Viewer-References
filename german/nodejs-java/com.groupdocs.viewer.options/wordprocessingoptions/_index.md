---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Optionen zum Rendern von Textverarbeitungsdokumenten bereit."
type: docs
weight: 38
url: /de/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Stellt Optionen zum Rendern von Textverarbeitungsdokumenten bereit.

Die WordProcessingOptions‑Klasse bietet Optionen zum Rendern von Textverarbeitungsdokumenten in der GroupDocs.Viewer‑Komponente. Sie fasst Einstellungen und Parameter zusammen, die zur Steuerung des Renderprozesses und des Ausgabeformats für Textverarbeitungsdateien verwendet werden können. Weitere Details finden Sie in der [documentation][].

Beispielhafte Verwendung:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | Initialisiert eine neue Instanz der WordProcessingOptions‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageSize()](#getPageSize--) | Ruft die Seitengröße für das Rendern von HTM‑ und HTML‑Dateien ab. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Legt die Seitengröße für das Rendern von HTM‑ und HTML‑Dateien fest. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Gibt an, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Legt fest, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist. |
| [getLeftMargin()](#getLeftMargin--) | Ruft den linken Seitenrand für das HTML‑Rendering ab. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Legt den linken Seitenrand für das HTML‑Rendering fest. |
| [getRightMargin()](#getRightMargin--) | Ruft den rechten Seitenrand für das HTML‑Rendering ab. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Legt den rechten Seitenrand für das HTML‑Rendering fest. |
| [getTopMargin()](#getTopMargin--) | Ruft den oberen Seitenrand für das HTML‑Rendering ab. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Legt den oberen Seitenrand für die HTML‑Darstellung fest. |
| [getBottomMargin()](#getBottomMargin--) | Unterer Seitenrand (nur für HTML‑Darstellung) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Legt den unteren Seitenrand für die HTML‑Darstellung fest. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Diese Option aktiviert Kerning und andere OpenType‑Features beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Diese Option aktiviert Kerning und andere OpenType‑Features beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Gibt an, ob die Navigation im Inhaltsverzeichnis beim Rendern zu HTML oder PDF deaktiviert werden soll. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Legt fest, ob die Navigation im Inhaltsverzeichnis beim Rendern zu HTML oder PDF deaktiviert werden soll. |
| [isUpdateFields()](#isUpdateFields--) | Ermittelt einen Wert, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Ausgabeformate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Legt einen Wert fest, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Ausgabeformate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. |
| [equals(Object o)](#equals-java.lang.Object-) | Prüfen, ob die Optionen geändert wurden. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initialisiert eine neue Instanz der WordProcessingOptions‑Klasse. Enthält Optionen für das Rendern von Textverarbeitungsdokumenten. Weitere Details finden Sie in der [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Ruft die Seitengröße für das Rendern von HTM‑ und HTML‑Dateien ab.

Bei Verwendung der Standard‑Seitengröße passt möglicherweise nicht der gesamte Inhalt in den Seitenrahmen. Um den Inhalt anzupassen, können Sie eine größere Seitengröße, z. B. A3, mit [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) festlegen.

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Legt die Seitengröße für das Rendern von HTM‑ und HTML‑Dateien fest.

Bei Verwendung der Standard‑Seitengröße passt möglicherweise nicht der gesamte Inhalt in den Seitenrahmen. Um den Inhalt anzupassen, können Sie eine größere Seitengröße, z. B. A3, mit [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) festlegen.

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Die Größe der Ausgabeseite. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Gibt an, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean –  true  wenn das Rendern von nachverfolgten Änderungen aktiviert ist,  false  sonst.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Legt fest, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  um das Rendern von nachverfolgten Änderungen zu aktivieren,  false  um es zu deaktivieren. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Ruft den linken Seitenrand für das HTML‑Rendering ab.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double – der Wert des linken Seitenrands.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Legt den linken Seitenrand für das HTML‑Rendering fest.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftMargin | java.lang.Double | Der zu setzende Wert des linken Seitenrands. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Ruft den rechten Seitenrand für das HTML‑Rendering ab.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double – der Wert des rechten Seitenrands.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Legt den rechten Seitenrand für das HTML‑Rendering fest.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rightMargin | java.lang.Double | Der zu setzende Wert des rechten Seitenrands. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Ruft den oberen Seitenrand für das HTML‑Rendering ab.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double – der obere Seitenrand.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Legt den oberen Seitenrand für die HTML‑Darstellung fest.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| topMargin | java.lang.Double | Der zu setzende obere Seitenrand. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Unterer Seitenrand (nur für HTML‑Darstellung)

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double – der untere Seitenrand.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Legt den unteren Seitenrand für die HTML‑Darstellung fest.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bottomMargin | java.lang.Double | Der zu setzende untere Seitenrand. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Diese Option aktiviert Kerning und andere OpenType‑Features beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften.

**Returns:**
boolean –  True wenn OpenType‑Funktionen aktiviert sind, false sonst.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Diese Option aktiviert Kerning und andere OpenType‑Features beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | True, um OpenType‑Funktionen zu aktivieren, sonst false. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Gibt an, ob die Navigation im Inhaltsverzeichnis beim Rendern zu HTML oder PDF deaktiviert werden soll. Wenn diese Option auf true gesetzt ist, werden beim HTML‑Rendering relative Links im Inhaltsverzeichnis durch span‑Tags ersetzt, wodurch die Funktionalität entfernt, aber das visuelle Erscheinungsbild erhalten bleibt. Beim PDF‑Rendering wird das Inhaltsverzeichnis als reiner Text ohne Links gerendert.

**Returns:**
boolean – True, wenn die Navigation im Inhaltsverzeichnis deaktiviert ist; andernfalls false.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Legt fest, ob die Navigation im Inhaltsverzeichnis beim Rendern zu HTML oder PDF deaktiviert werden soll. Wenn diese Option auf true gesetzt ist, werden beim HTML‑Rendering relative Links im Inhaltsverzeichnis durch span‑Tags ersetzt, wodurch die Funktionalität entfernt, aber das visuelle Erscheinungsbild erhalten bleibt. Beim PDF‑Rendering wird das Inhaltsverzeichnis als reiner Text ohne Links gerendert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unlinkTableOfContents | boolean | Gibt an, ob die Navigation im Inhaltsverzeichnis deaktiviert werden soll. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Ruft einen Wert ab, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Ausgabeformate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. Der Standardwert für diese Eigenschaft ist true \\u2014 Felder werden vor dem Speichern aktualisiert.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Legt einen Wert fest, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Ausgabeformate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. Der Standardwert für diese Eigenschaft ist true \\u2014 Felder werden vor dem Speichern aktualisiert.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Prüfen, ob die Optionen geändert wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das Objekt, das auf Gleichheit verglichen wird. |

**Returns:**
boolean – true, wenn die Optionen dem angegebenen Objekt entsprechen, sonst false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berechnet den Hashcode-Wert für dieses Objekt. Der Hashcode basiert auf dem internen Zustand des Objekts und wird in hashbasierten Datenstrukturen wie Hash-Maps und Hash-Sets verwendet.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - der Hashcode-Wert für dieses Objekt.
