---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Definisce la modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML."
type: docs
weight: 46
url: /it/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Definisce la modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML.

L'enum TextOverflowMode rappresenta diversi modi per gestire l'overflow di testo nel componente GroupDocs.Viewer. Fornisce un insieme di opzioni predefinite che possono essere utilizzate per controllare come il testo viene visualizzato quando supera lo spazio disponibile nelle celle durante il rendering dei documenti di foglio di calcolo in HTML. Per i dettagli, vedere la [documentazione][].

Esempio di utilizzo:

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
## Campi

| Campo | Descrizione |
| --- | --- |
| [OVERLAY](#OVERLAY) | Sovrapponi le celle successive anche se non sono vuote. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Sovrapponi le celle successive solo se sono vuote. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Espandi le colonne per adattarle al testo. |
| [HIDE_TEXT](#HIDE-TEXT) | Nascondi il testo in overflow. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Sovrapponi le celle successive anche se non sono vuote. Questa modalità consente al testo di overflow di passare nelle celle adiacenti, indipendentemente dal loro contenuto.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Sovrapponi le celle successive solo se sono vuote. Questa modalità consente al testo di overflow di passare nelle celle adiacenti solo se queste celle sono vuote.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Espandi le colonne per adattarle al testo. Questa modalità regola automaticamente la larghezza delle colonne per accogliere il testo in overflow.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Nascondi il testo in overflow. Questa modalità nasconde il testo in overflow, impedendone la visualizzazione.

Per i dettagli, vedere la [documentazione][].


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
