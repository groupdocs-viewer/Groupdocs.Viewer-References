---
title: "FontSettings"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller metoder för att arbeta med källor för att söka efter TrueType-typsnitt."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Tillhandahåller metoder för att arbeta med källor för att söka efter TrueType-typsnitt.

FontSettings-klassen används för att ange och hantera källor för att hitta TrueType-teckensnitt. Den tillhandahåller metoder för att lägga till och återställa teckensnittskällor för GroupDocs.Viewer API.

Exempel på användning:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Ställer in källorna för att söka efter TrueType-teckensnitt när dokument renderas. |
| [resetFontSources()](#resetFontSources--) | Återställer teckensnittskällorna som tidigare har ställts in. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Ställer in källorna för att söka efter TrueType-teckensnitt när dokument renderas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Teckensnittskällorna att ställa in. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Återställer teckensnittskällorna som tidigare har ställts in.

