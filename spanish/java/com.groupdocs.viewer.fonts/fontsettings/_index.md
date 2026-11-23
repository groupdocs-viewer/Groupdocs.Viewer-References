---
title: "FontSettings"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona métodos para trabajar con fuentes al buscar fuentes TrueType."
type: docs
weight: 12
url: /es/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Proporciona métodos para trabajar con fuentes al buscar fuentes TrueType.


La clase FontSettings se usa para especificar y gestionar fuentes para localizar fuentes TrueType.
Proporciona métodos para agregar y restablecer fuentes tipográficas para la API GroupDocs.Viewer.


Ejemplo de uso:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Establece las fuentes para buscar fuentes TrueType al renderizar documentos. |
|
|  | [resetFontSources()](#resetFontSources--) | Restablece las fuentes tipográficas que se habían establecido anteriormente. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Establece las fuentes para buscar fuentes TrueType al renderizar documentos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Las fuentes tipográficas a establecer. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Restablece las fuentes tipográficas que se habían establecido anteriormente.


