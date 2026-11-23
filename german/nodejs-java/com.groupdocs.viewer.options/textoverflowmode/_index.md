---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Definiert den Textüberlaufmodus für das Rendern von Tabellenkalkulationsdokumenten in HTML."
type: docs
weight: 46
url: /de/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Definiert den Textüberlaufmodus für das Rendern von Tabellenkalkulationsdokumenten in HTML.

Das TextOverflowMode‑Enum stellt verschiedene Modi zur Handhabung von Textüberlauf im GroupDocs.Viewer‑Komponente dar. Es bietet eine Reihe vordefinierter Optionen, die verwendet werden können, um zu steuern, wie Text angezeigt wird, wenn er den verfügbaren Platz in Zellen beim Rendern von Tabellendokumenten in HTML überschreitet. Weitere Details finden Sie in der [documentation][].

Beispielhafte Verwendung:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## Felder

| Feld | Beschreibung |
| --- | --- |
| [OVERLAY](#OVERLAY) | Überlagere die nächsten Zellen, selbst wenn sie nicht leer sind. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Überlagere die nächsten Zellen nur, wenn sie leer sind. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Spalten erweitern, um den Text anzupassen. |
| [HIDE_TEXT](#HIDE-TEXT) | Den Überlauftext ausblenden. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Überlagere die nächsten Zellen, selbst wenn sie nicht leer sind. Dieser Modus ermöglicht es, dass der Text in die angrenzenden Zellen überläuft, unabhängig von deren Inhalt.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Überlagere die nächsten Zellen nur, wenn sie leer sind. Dieser Modus ermöglicht es, dass der Text nur in leere angrenzende Zellen überläuft.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Spalten erweitern, um den Text anzupassen. Dieser Modus passt die Spaltenbreite automatisch an, um den überlaufenden Text aufzunehmen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Den Überlauftext ausblenden. Dieser Modus blendet den überlaufenden Text aus und verhindert dessen Anzeige.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

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
