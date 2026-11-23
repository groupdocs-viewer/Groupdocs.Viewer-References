---
title: "FontSettings"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt methoden om te werken met bronnen om TrueType-lettertypen te zoeken."
type: docs
weight: 12
url: /nl/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Biedt methoden om te werken met bronnen om TrueType-lettertypen te zoeken.


De FontSettings‑klasse wordt gebruikt om bronnen op te geven en te beheren voor het vinden van TrueType‑lettertypen.
Het biedt methoden om lettertype‑bronnen toe te voegen en te resetten voor de GroupDocs.Viewer‑API.


Voorbeeldgebruik:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Stelt de bronnen in om TrueType‑lettertypen te zoeken bij het renderen van documenten. |
|
|  | [resetFontSources()](#resetFontSources--) | Reset de eerder ingestelde lettertype‑bronnen. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Stelt de bronnen in om TrueType‑lettertypen te zoeken bij het renderen van documenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | De in te stellen lettertype‑bronnen. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Reset de eerder ingestelde lettertype‑bronnen.


