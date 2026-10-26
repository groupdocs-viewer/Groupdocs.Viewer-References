---
title: "FontSettings"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType.

La classe FontSettings è usata per specificare e gestire le fonti per individuare i caratteri TrueType. Fornisce metodi per aggiungere e reimpostare le fonti dei caratteri per l'API GroupDocs.Viewer.

Esempio di utilizzo:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Imposta le fonti da cercare per i caratteri TrueType durante il rendering dei documenti. |
| [resetFontSources()](#resetFontSources--) | Reimposta le fonti dei caratteri che sono state impostate in precedenza. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Imposta le fonti da cercare per i caratteri TrueType durante il rendering dei documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Le fonti dei caratteri da impostare. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Reimposta le fonti dei caratteri che sono state impostate in precedenza.

