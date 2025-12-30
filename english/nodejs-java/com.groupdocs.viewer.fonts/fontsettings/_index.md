---
title: FontSettings
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides methods for working with sources to look for TrueType fonts.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Provides methods for working with sources to look for TrueType fonts.

The FontSettings class is used to specify and manage sources for locating TrueType fonts. It provides methods to add and reset font sources for the GroupDocs.Viewer API.

Example usage:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Methods

| Method | Description |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Sets the sources to look for TrueType fonts when rendering documents. |
| [resetFontSources()](#resetFontSources--) | Resets the font sources that have been set before. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Sets the sources to look for TrueType fonts when rendering documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | The font sources to set. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Resets the font sources that have been set before.

