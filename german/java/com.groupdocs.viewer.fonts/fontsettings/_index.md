---
title: "FontSettings"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Methoden zur Arbeit mit Quellen bereit, um nach TrueType-Schriftarten zu suchen."
type: docs
weight: 12
url: /de/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Stellt Methoden zur Arbeit mit Quellen bereit, um nach TrueType-Schriftarten zu suchen.


Die FontSettings-Klasse wird verwendet, um Quellen für das Auffinden von TrueType-Schriften anzugeben und zu verwalten.
Sie bietet Methoden zum Hinzufügen und Zurücksetzen von Schriftquellen für die GroupDocs.Viewer-API.


Beispielverwendung:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Legt die Quellen fest, in denen bei der Dokumentenrenderung nach TrueType-Schriften gesucht wird. |
|
|  | [resetFontSources()](#resetFontSources--) | Setzt die zuvor festgelegten Schriftquellen zurück. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Legt die Quellen fest, in denen bei der Dokumentenrenderung nach TrueType-Schriften gesucht wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Die festzulegenden Schriftquellen. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Setzt die zuvor festgelegten Schriftquellen zurück.


