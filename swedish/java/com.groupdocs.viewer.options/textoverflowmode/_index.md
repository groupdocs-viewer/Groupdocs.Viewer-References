---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Definierar textöversvämningsläge för rendering av kalkylbladsdokument till HTML."
type: docs
weight: 46
url: /sv/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Definierar textöversvämningsläge för rendering av kalkylbladsdokument till HTML.


Enumen TextOverflowMode representerar olika lägen för att hantera textöverspill i GroupDocs.Viewer-komponenten.
Den tillhandahåller en uppsättning fördefinierade alternativ som kan användas för att styra hur text visas när den överskrider det tillgängliga
utrymmet i celler under rendering av kalkylbladsdokument till HTML.
För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


Exempel på användning:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | Överlagra nästa celler även om de inte är tomma. |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Överlagra nästa celler endast om de är tomma. |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Expandera kolumner för att passa texten. |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | Dölj den överskjutande texten. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Överlagra nästa celler även om de inte är tomma.
Detta läge tillåter att texten flödar över i intilliggande celler, oavsett deras innehåll.
För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Överlagra nästa celler endast om de är tomma.
Detta läge tillåter att texten flödar över i intilliggande celler endast om dessa celler är tomma.
För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Expandera kolumner för att passa texten.
Detta läge justerar automatiskt kolumnbredden för att rymma den överskjutande texten.
För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Dölj den överskjutande texten.
Detta läge döljer den överskjutande texten och förhindrar att den visas.
För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
