---
title: "TextOptions"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Opzioni di suddivisione dei file di testo in pagine."
type: docs
weight: 32
url: /it/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Opzioni di suddivisione dei file di testo in pagine.

La classe TextOptions fornisce opzioni per suddividere i file di testo in pagine nel componente GroupDocs.Viewer. Consente di controllare come i file di testo vengono divisi in pagine individuali per scopi di rendering e visualizzazione.

Esempio di utilizzo:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextOptions()](#TextOptions--) | Inizializza una nuova istanza della classe TextOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Ottiene il numero massimo di caratteri per riga su una pagina. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Imposta il numero massimo di caratteri per riga su una pagina. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Ottiene il numero massimo di righe per pagina. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Imposta il numero massimo di righe per pagina. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Inizializza una nuova istanza della classe TextOptions.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Ottiene il numero massimo di caratteri per riga su una pagina.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - il numero massimo di caratteri per riga su una pagina.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Imposta il numero massimo di caratteri per riga su una pagina.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxCharsPerRow | int | Il numero massimo di caratteri per riga su una pagina. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Ottiene il numero massimo di righe per pagina.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - il numero massimo di righe.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Imposta il numero massimo di righe per pagina.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxRowsPerPage | int | Il numero massimo di righe. |

