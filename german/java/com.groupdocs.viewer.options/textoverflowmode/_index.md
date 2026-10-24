---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Definiert den Textüberlaufmodus für die Darstellung von Tabellendokumenten in HTML."
type: docs
weight: 46
url: /de/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Definiert den Textüberlaufmodus für die Darstellung von Tabellendokumenten in HTML.


Das enum TextOverflowMode stellt verschiedene Modi zur Behandlung von Textüberlauf im GroupDocs.Viewer‑Komponente dar.
Es bietet eine Reihe vordefinierter Optionen, die verwendet werden können, um zu steuern, wie Text angezeigt wird, wenn er das verfügbare
Platz in Zellen während des Renderns von Tabellenkalkulationsdokumenten nach HTML überschreitet.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


Beispielverwendung:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | Überlagere nächste Zellen, selbst wenn sie nicht leer sind. |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Überlagere die nächsten Zellen nur, wenn sie leer sind. |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Spalten erweitern, um den Text anzupassen. |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | Den überlaufenden Text ausblenden. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Überlagere nächste Zellen, selbst wenn sie nicht leer sind.
Dieser Modus erlaubt es dem Text, in die angrenzenden Zellen zu überlaufen, unabhängig von deren Inhalt.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Überlagere die nächsten Zellen nur, wenn sie leer sind.
Dieser Modus erlaubt es dem Text, in die angrenzenden Zellen zu überlaufen, nur wenn diese Zellen leer sind.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Spalten erweitern, um den Text anzupassen.
Dieser Modus passt die Spaltenbreite automatisch an, um den überlaufenden Text aufzunehmen.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Den überlaufenden Text ausblenden.
Dieser Modus blendet den überlaufenden Text aus und verhindert, dass er angezeigt wird.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
