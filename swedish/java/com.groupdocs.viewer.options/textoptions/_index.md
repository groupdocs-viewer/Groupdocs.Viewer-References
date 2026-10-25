---
title: "TextOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Alternativ för att dela upp textfiler i sidor."
type: docs
weight: 32
url: /sv/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Alternativ för att dela upp textfiler i sidor.


Klassen TextOptions tillhandahåller alternativ för att dela upp textfiler i sidor i GroupDocs.Viewer-komponenten.
Den gör det möjligt att kontrollera hur textfiler delas upp i enskilda sidor för renderings- och visningsändamål.


Exempel på användning:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | Initierar en ny instans av |
TextOptions
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Hämtar det maximala antalet tecken per rad på en sida. |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Ställer in det maximala antalet tecken per rad på en sida. |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Hämtar det maximala antalet rader per sida. |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Ställer in det maximala antalet rader per sida. |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Initierar en ny instans av
TextOptions
klassen.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Hämtar det maximala antalet tecken per rad på en sida.


***Note:** The default value is 85.*
Standardvärdet är 85. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - det maximala antalet tecken per rad på en sida.

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Ställer in det maximala antalet tecken per rad på en sida.


***Note:** The default value is 85.*
Standardvärdet är 85. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxCharsPerRow | int | Det maximala antalet tecken per rad på en sida. |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Hämtar det maximala antalet rader per sida.


***Note:** The default value is 55.*
Standardvärdet är 55. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - det maximala antalet rader.

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Ställer in det maximala antalet rader per sida.


***Note:** The default value is 55.*
Standardvärdet är 55. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxRowsPerPage | int | Det maximala antalet rader. |
|

