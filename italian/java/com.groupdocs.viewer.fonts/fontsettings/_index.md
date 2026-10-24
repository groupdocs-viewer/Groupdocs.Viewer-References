---
title: "FontSettings"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType."
type: docs
weight: 12
url: /it/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType.


La classe FontSettings è usata per specificare e gestire le sorgenti per individuare i font TrueType.
Fornisce metodi per aggiungere e ripristinare le sorgenti dei font per l'API GroupDocs.Viewer.


Esempio di utilizzo:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Imposta le sorgenti da cercare per i font TrueType durante il rendering dei documenti. |
|
|  | [resetFontSources()](#resetFontSources--) | Ripristina le sorgenti dei font che sono state impostate in precedenza. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Imposta le sorgenti da cercare per i font TrueType durante il rendering dei documenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Le sorgenti dei font da impostare. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Ripristina le sorgenti dei font che sono state impostate in precedenza.


