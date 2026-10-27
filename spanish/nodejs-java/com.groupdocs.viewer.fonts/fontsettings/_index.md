---
title: "FontSettings"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona métodos para trabajar con fuentes para buscar fuentes TrueType."
type: docs
weight: 12
url: /es/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Proporciona métodos para trabajar con fuentes para buscar fuentes TrueType.

La clase FontSettings se utiliza para especificar y administrar orígenes para localizar fuentes TrueType. Proporciona métodos para agregar y restablecer los orígenes de fuentes para la API de GroupDocs.Viewer.

Ejemplo de uso:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Establece los orígenes donde buscar fuentes TrueType al renderizar documentos. |
| [resetFontSources()](#resetFontSources--) | Restablece los orígenes de fuentes que se habían establecido anteriormente. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Establece los orígenes donde buscar fuentes TrueType al renderizar documentos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Los orígenes de fuentes a establecer. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Restablece los orígenes de fuentes que se habían establecido anteriormente.

