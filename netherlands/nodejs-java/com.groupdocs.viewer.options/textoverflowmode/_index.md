---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Definieert de tekst-overloopmodus voor het renderen van spreadsheetdocumenten naar HTML."
type: docs
weight: 46
url: /nl/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Definieert de tekst-overloopmodus voor het renderen van spreadsheetdocumenten naar HTML.

De TextOverflowMode‑enum vertegenwoordigt verschillende modi voor het afhandelen van tekst‑overflow in de GroupDocs.Viewer‑component. Het biedt een set vooraf gedefinieerde opties die kunnen worden gebruikt om te bepalen hoe tekst wordt weergegeven wanneer deze de beschikbare ruimte in cellen overschrijdt tijdens het renderen van spreadsheet‑documenten naar HTML. Voor details, zie de [documentation][].

Voorbeeldgebruik:

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
## Velden

| Veld | Beschrijving |
| --- | --- |
| [OVERLAY](#OVERLAY) | Overlay de volgende cellen, zelfs als ze niet leeg zijn. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Overlay de volgende cellen alleen als ze leeg zijn. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Vergroot kolommen zodat de tekst past. |
| [HIDE_TEXT](#HIDE-TEXT) | Verberg de overflow‑tekst. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Overlay de volgende cellen, zelfs als ze niet leeg zijn. Deze modus staat toe dat de tekst overloopt naar de aangrenzende cellen, ongeacht hun inhoud.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Overlay de volgende cellen alleen als ze leeg zijn. Deze modus staat toe dat de tekst overloopt naar de aangrenzende cellen alleen als die cellen leeg zijn.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Vergroot kolommen zodat de tekst past. Deze modus past automatisch de breedte van de kolommen aan om de overlopende tekst te huisvesten.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Verberg de overflow‑tekst. Deze modus verbergt de overlopende tekst, zodat deze niet wordt weergegeven.

Voor details, zie de [documentatie][].


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
