---
title: "FontSettings"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Methoden zur Arbeit mit Quellen bereit, um nach TrueType-Schriften zu suchen."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Stellt Methoden zur Arbeit mit Quellen bereit, um nach TrueType-Schriften zu suchen.

Die FontSettings‑Klasse wird verwendet, um Quellen zum Auffinden von TrueType‑Schriften anzugeben und zu verwalten. Sie bietet Methoden zum Hinzufügen und Zurücksetzen von Schriftquellen für die GroupDocs.Viewer‑API.

Beispielhafte Verwendung:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Legt die Quellen fest, in denen nach TrueType‑Schriften beim Rendern von Dokumenten gesucht wird. |
| [resetFontSources()](#resetFontSources--) | Setzt die zuvor festgelegten Schriftquellen zurück. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Legt die Quellen fest, in denen nach TrueType‑Schriften beim Rendern von Dokumenten gesucht wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Die zu setzenden Schriftquellen. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Setzt die zuvor festgelegten Schriftquellen zurück.

