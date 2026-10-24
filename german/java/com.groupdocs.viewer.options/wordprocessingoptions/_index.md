---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Textverarbeitungs‑Dokumenten bereit."
type: docs
weight: 38
url: /de/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Stellt Optionen zum Rendern von Textverarbeitungs‑Dokumenten bereit.


Die WordProcessingOptions-Klasse bietet Optionen zum Rendern von Textverarbeitungsdokumenten
im GroupDocs.Viewer‑Komponente. Sie kapselt Einstellungen und Parameter, die verwendet werden können
um den Rendering-Prozess und das Ausgabeformat für Textverarbeitungsdateien zu steuern.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Beispielverwendung:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Initialisiert eine neue Instanz von |
WordProcessingOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Ruft die Seitengröße für das Rendern von HTM- und HTML-Dateien ab. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Legt die Seitengröße für das Rendern von HTM- und HTML-Dateien fest. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Gibt an, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Legt fest, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Ruft den linken Seitenrand für das HTML-Rendering ab. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Legt den linken Seitenrand für das HTML-Rendering fest. |
|
|  | [getRightMargin()](#getRightMargin--) | Ruft den rechten Seitenrand für das HTML-Rendering ab. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Legt den rechten Seitenrand für das HTML-Rendering fest. |
|
|  | [getTopMargin()](#getTopMargin--) | Ruft den oberen Seitenrand für das HTML-Rendering ab. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Legt den oberen Seitenrand für das HTML-Rendering fest. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Unterer Seitenrand (nur für HTML-Rendering) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Legt den unteren Seitenrand für das HTML-Rendering fest. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Diese Option aktiviert Kerning und andere OpenType‑Funktionen beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Diese Option aktiviert Kerning und andere OpenType‑Funktionen beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Gibt an, ob die Navigation im Inhaltsverzeichnis beim Rendern zu HTML oder PDF deaktiviert werden soll. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Legt fest, ob die Navigation im Inhaltsverzeichnis beim Rendern zu HTML oder PDF deaktiviert werden soll. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Ruft einen Wert ab, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Ausgabeformate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Legt einen Wert fest, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Ausgabeformate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Ruft die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll ab. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Legt die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Ruft die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll ab. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Legt die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Ermöglicht das erzwungene Anwenden von Seitenzahlen für das geladene WordProcessing‑Dokument. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Ermöglicht das erzwungene Anwenden von Seitenzahlen für das geladene WordProcessing‑Dokument. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob die Optionen geändert wurden. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initialisiert eine neue Instanz von
WordProcessingOptions
Klasse.
Enthält Optionen zum Rendern von Textverarbeitungsdokumenten. Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Ruft die Seitengröße für das Rendern von HTM- und HTML-Dateien ab.


Bei Verwendung der Standardseitengröße passt möglicherweise nicht der gesamte Inhalt in den Seitenrahmen.
Um den Inhalt anzupassen, können Sie eine größere Seitengröße, z. B. A3, mit [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) festlegen.


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Legt die Seitengröße für das Rendern von HTM- und HTML-Dateien fest.


Bei Verwendung der Standardseitengröße passt möglicherweise nicht der gesamte Inhalt in den Seitenrahmen.
Um den Inhalt anzupassen, können Sie eine größere Seitengröße, z. B. A3, mit [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) festlegen.


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Die Größe der Ausgabeseite. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Gibt an, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean -  true  wenn die Darstellung von nachverfolgten Änderungen aktiviert ist,  false  sonst.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Legt fest, ob das Rendern von nachverfolgten Änderungen (Revisionen) aktiviert ist.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um die Darstellung von nachverfolgten Änderungen zu aktivieren,  false  um sie zu deaktivieren. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Ruft den linken Seitenrand für das HTML-Rendering ab.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - der Wert des linken Seitenrands.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Legt den linken Seitenrand für das HTML-Rendering fest.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | Der zu setzende Wert des linken Seitenrands. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Ruft den rechten Seitenrand für das HTML-Rendering ab.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - der Wert des rechten Seitenrands.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Legt den rechten Seitenrand für das HTML-Rendering fest.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | Der zu setzende Wert des rechten Seitenrands. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Ruft den oberen Seitenrand für das HTML-Rendering ab.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - der obere Seitenrand.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Legt den oberen Seitenrand für das HTML-Rendering fest.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | topMargin | java.lang.Double | Der zu setzende obere Seitenrand. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Unterer Seitenrand (nur für HTML-Rendering)
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - der untere Seitenrand.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Legt den unteren Seitenrand für das HTML-Rendering fest.
Weitere Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | Der zu setzende untere Seitenrand. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Diese Option aktiviert Kerning und andere OpenType‑Funktionen beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften.


**Returns:**
boolean -  True  wenn OpenType‑Funktionen aktiviert sind, false sonst.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Diese Option aktiviert Kerning und andere OpenType‑Funktionen beim Rendern von Arabisch, Hebräisch, indischen Schriften, latinbasierten oder kyrillischen Schriften.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolesch | True, um OpenType‑Funktionen zu aktivieren, sonst false. |
|

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
|  | unlinkTableOfContents | boolesch | Gibt an, ob die Navigation im Inhaltsverzeichnis deaktiviert werden soll. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Ermittelt einen Wert, der festlegt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Formate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. Der Standardwert für diese Eigenschaft ist true \\u2014 Felder werden vor dem Speichern aktualisiert.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolesch
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Legt einen Wert fest, der bestimmt, ob Felder bestimmter Typen vor dem Speichern des Eingabe‑WordProcessing‑Dokuments in die Formate HTML, PDF, PNG oder JPEG aktualisiert werden sollen. Der Standardwert für diese Eigenschaft ist true \\u2014 Felder werden vor dem Speichern aktualisiert.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| updateFields | boolesch |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Ermittelt die horizontale Auflösung für erzeugte Bilder in DPI (dots per inch). Diese Option wird ausschließlich beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Returns:**
int - die horizontale Auflösung in DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Legt die horizontale Auflösung für erzeugte Bilder in DPI (dots per inch) fest. Diese Option wird ausschließlich beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | horizontalResolution | int | die horizontale Auflösung in DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Ermittelt die vertikale Auflösung für erzeugte Bilder in DPI (dots per inch). Diese Option wird ausschließlich beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Returns:**
int - die vertikale Auflösung in DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Legt die vertikale Auflösung für erzeugte Bilder in DPI (dots per inch) fest. Diese Option wird ausschließlich beim Rendern von WordProcessing‑Dokumenten in PNG‑ oder JPEG‑Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | verticalResolution | int | die vertikale Auflösung in DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Ermöglicht das erzwungene Anwenden von Seitenzahlen für das geladene WordProcessing‑Dokument. Standardmäßig ist [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 Dokument bleibt unverändert.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Ermöglicht das erzwungene Anwenden von Seitenzahlen für das geladene WordProcessing‑Dokument. Standardmäßig ist [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 Dokument bleibt unverändert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | der Ort der Seitenzahl. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob die Optionen geändert wurden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | o | java.lang.Object | Das Objekt, das auf Gleichheit verglichen wird. |
|

**Returns:**
boolean –  true, wenn die Optionen dem angegebenen Objekt entsprechen,  false, andernfalls.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Berechnet den Hashcode-Wert für dieses Objekt. Der Hashcode basiert auf
dem internen Zustand des Objekts und wird in hashbasierten Datenstrukturen verwendet
wie z.B. Hash-Maps und Hash-Sets.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - der Hashcode-Wert für dieses Objekt.

